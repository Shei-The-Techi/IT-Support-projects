# Service Desk Simulator Practice

I use ServiceDesk Simulator to practise ticket handling outside my client work. The platform recreates a service desk queue. Each ticket arrives with a user, a priority, a business impact and the troubleshooting the user has already tried. I take the ticket, connect to the user's machine through a remote desktop tool, check the internal documentation, fix the problem and confirm the result with the user in a chat window.

This folder holds my case notes. Each one covers what the ticket said, what I checked, what I changed, how I communicated and what I would do differently.

## Read this first

This is practice, not production work. The company, the users, the machines and the tickets are fictional and belong to the platform. I include them as evidence of how I troubleshoot and communicate, and I do not present them as client experience. My real client work appears in anonymised form in the other projects in this repository.

## Why I practise

The part of the job I most want to keep sharp is hands on troubleshooting with a user waiting at the other end. A simulated queue lets me repeat that cycle often, under realistic pressure such as a high priority ticket and a deadline, without any risk to a live system.

## Cases

| Case | Ticket | Priority | Problem | What I found | Result |
|---|---|---|---|---|---|
| [01](case-01-shared-drive-unreachable.md) | INC0012847 | High | Marketing user working from home could not open the shared drive | Mapped drive offline and the VPN tunnel down | Drive remapped, user confirmed |
| [02](case-02-wrong-time-zone-and-clock-drift.md) | INC0012865 | High | Sales user's clock was wrong and meetings showed at the wrong times | Wrong time zone, plus a separate two minute clock drift | Zone corrected and clock synced, user confirmed |

More cases will be added as I work through the queue.

## Skills practised

* Remote support over a remote desktop session
* Network and VPN troubleshooting for remote users
* Mapped network drives and UNC paths
* Using internal documentation to confirm the right answer before changing anything
* Time zone and time synchronisation settings
* Confirming the right user and machine before connecting
* Clear communication with the user, from acknowledgement to closure

## How I work a ticket

1. Acknowledge the ticket quickly and tell the user what to expect.
2. Read the description for impact, what has already been tried and what has been ruled out.
3. Confirm the right user and the right machine before connecting.
4. Check the documentation instead of guessing at names, paths or settings.
5. Fix the cause, then check the result and not only the setting I changed.
6. Ask the user to confirm it works, and close the ticket only after that.
7. Write down the cause and the fix so the next person does not start from zero.

## About the screenshots

The screenshots are resized for the repository. I left out the remote login screens on purpose, because the simulator shows its practice account details there.

## Platform

ServiceDesk Simulator is a third party training platform. Its name, interface and scenarios belong to its owners, and I am not affiliated with it.
