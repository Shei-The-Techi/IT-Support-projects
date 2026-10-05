# Documentation

This folder holds the guides, checklists and runbooks I write for the systems I support. Good documentation means someone else can follow the steps, recover a system or take over the work without needing me.

## What belongs here

* **Runbooks** for recurring tasks, such as onboarding a new user or restoring a file from backup
* **Checklists** for routine reviews, such as a monthly security check
* **How to guides** for configuration tasks
* **Policies and standards**, such as an access control standard or backup policy
* **Recovery procedures** for failure scenarios, such as losing admin access

## Documentation index

Add each document to this list as you create it, with a one line description.

* [Document name](file-name.md) and a short description

## How I write documentation

1. Each document has one clear purpose and a stated audience.
2. Steps are numbered and written so someone unfamiliar with the system can follow them.
3. Every procedure ends with a way to confirm it worked.
4. Each document shows a last reviewed date, so readers know whether to trust it.
5. No passwords, recovery codes, API keys or client identifying details ever appear in a document. I record where access is held and who controls it instead.

## Template

Copy this into a new file such as `documentation/restore-google-drive-file.md`.

```
# Document title

**Audience:** who this is for
**Last reviewed:** date
**Owner:** role responsible for keeping it current

## Purpose
Why this document exists.

## Before you start
Access, tools or approvals needed.

## Steps
1. First step
2. Second step
3. Third step

## How to confirm it worked
What you should see when it is done.

## If something goes wrong
How to roll back or who to contact.
```
