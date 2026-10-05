# Digital Asset and Access Register with Control Dashboard

A sample Excel workbook I designed to show whether a small organisation's critical digital assets are protected, backed up and recoverable.

## Background

I work as an IT support and infrastructure consultant. Many of the organisations I support run mostly on Google Workspace and have very little infrastructure that needs ongoing troubleshooting. For them, a monthly report full of activities and hours says little about real risk.

What management actually needs to know is simple. Does the business own its critical systems? Can it get back in if access is lost? Can it recover its data when something goes wrong?

This workbook is my answer. It turns monthly IT oversight into a small set of measurable controls and a one page executive dashboard.

The structure comes from real client work. Every name, role, date and finding in this repository is fictional or anonymised, and the client has given permission for this sample to be shared. "Example Co" is not a real organisation.

## The questions it answers

1. What does the organisation rely on digitally?
2. Who owns each asset and who administers it?
3. Can the business regain access without depending on the consultant?
4. Is important data backed up, and has recovery actually been tested?
5. What still needs attention, and who is responsible for it?

## What is inside

**Digital Assets** is the master register. For each asset it records the business owner, whether admin access is confirmed, whether the organisation has its own admin or recovery access, the renewal date, current position and any risk.

**Accounts & Security** checks important accounts one by one for access level, MFA status and follow up actions.

**Backup & Recovery** records whether each system is backed up, how often, whether the last backup succeeded and the result of the last recovery test.

**Monthly Control Check** covers ten control areas. For each one it shows what was checked, the current position, the evidence date, the next action, the owner and the due date.

**Open Items** is the risk and action log, so issues are not lost between monthly reports.

**Executive Dashboard** gives a one page view built from the other sheets using formulas.

## Dashboard measures

The dashboard reports five headline measures:

* Critical systems reviewed, shown as a count out of the total
* MFA compliance as a percentage
* Backups successful as a percentage
* Recovery test result (Pass, Fail, Partial or Not tested)
* High risk unresolved issues

A chart also shows open items by priority.

## Design decisions

**Owner and administrator are separate.** The business owner is always a role inside the organisation. The consultant appears as the administrator or support contact. This makes it easy to see whether the business could recover access without the consultant.

**No secrets are stored.** The workbook records the access route and who controls recovery. It never holds passwords, MFA backup codes or API keys.

**A simple status vocabulary.** Every status is one of Good, Needs attention, High risk or Not yet checked, so the report reads the same way every month.

**Evidence over assertion.** Each control is dated, owned and tied to a next action, so a status can be challenged and checked.

## How to use it

1. Download the workbook and save a copy for your own organisation.
2. Replace the sample assets and accounts with your own, using roles rather than personal names where possible.
3. Update the statuses, dates and evidence each month.
4. Review the dashboard first, then go to the Open Items sheet for anything that needs a decision.

## Known limitations

* MFA compliance is calculated per account row, so a single row that covers many users counts once. Listing users individually gives a more accurate percentage.
* Evidence is referenced by date. In real use it is worth adding a link or file reference for each check.
* The recovery test measure reports the result but does not record the date of the test or the time taken to recover.

## Ideas for the next version

* A dedicated row for a second named administrator, with a clear flag when only one exists
* Fields for the recovery email, recovery phone and who controls each
* A security incident log and a short list of continuity scenarios, each with a tested recovery route
* A user level MFA count

## Author

Built by [Your Name], IT Support and Infrastructure Consultant.
