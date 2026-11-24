# Tools and access

What a new developer is given, what each thing is for, and what they do not have yet. No passwords and no addresses are in this file.

## The envelope

On the desk on day one, beside the laptop, is a sealed envelope from Ravi Menon. It is opened with Jane at the first sign-in. Inside:

- The first password for the Ostrander account.
- The first password for DEV.
- A card with the vendor wifi name and password. Jane's mobile number and Dana's are handwritten on it.

## What the new hire gets on day one

- **A laptop**, issued by Ostrander. Ravi sets it up the Friday before and leaves it on the desk. The environments, the repository and Foundations are already bookmarked.
- **An Ostrander account.** One sign-in for the laptop, the VPN, email, the project chat and the timesheet.
- **Vendor wifi** in Harlan Valley's building.
- **The VPN.** The Ostrander VPN app, a blue shield in the menu bar. Everything on Ostrander's side sits behind it, and it works from home. If something will not open, check the VPN first.
- **The project chat**, in Microsoft Teams. The team's channel is `HV Billing`. The contact sheet is pinned at the top. Teams also runs on a phone.
- **DEV**, the development environment. It has its own sign-in.
- **The project repository.** Read access to all of it on day one, and write access to the `new-hire/` folder. Jane shows how to add the first entry.
- **Foundations**, the training.

## The product

- The product is Ostrander CIS. Everyone calls it CIS. It stands for customer information system, the usual name for a utility's billing system.
- Most of the work is configuration, done in CIS's own designer. Extensions are written in Java when configuration cannot do the job.
- The code is in Git on Ostrander's own server. Access comes after Foundations module 3, which covers it.
- Defects are tracked in Jira, project HVB. Read access comes in week two.

## The environments

| Name | What it is for | New hire's access |
|---|---|---|
| DEV | Development. Made-up accounts only. Safe to click anything. | Day one |
| TST | Testing, shared with the client's testers. | Week two. Jane asks Ravi for it once Foundations is finished. |
| CNV | Conversion runs. Holds data carried over from the old system. | None planned. Walt and the technical team use it. |
| Production | Does not exist yet. It goes live at cutover. | Nobody |

- DEV holds no real customers. Everything in it is invented.
- TST and CNV hold real customer data. That is why they come later and with rules. See `how-we-work.md`.

## The project repository

Where the project's written record lives. Four folders matter to a new hire.

Two different things get called a repository. This one holds the project's documents, and the new hire can read all of it on day one. CIS's code is somewhere else, in Git on Ostrander's own server, and that opens after Foundations module 3.

- `plan/` is the deliverable plan. `where-we-are.md` is the one-page version. It is updated every Friday.
- `requirements/` is the billing design the client signed. One document per item, and a summary.
- `meetings/` is the notes from every client meeting, named by date. Joanne writes them up within a day.
- `new-hire/` is where answered questions get written down. `questions-answered.md` is the file, and it opens with Nadia's first week.

The guide has a copy of Nadia's part of that file. It has none of the other three folders' contents.

## Foundations

- Ostrander's training for CIS. Ten modules, about ninety minutes each, watched in order in the first week.
- Each ends with a short check. The check is for the new hire's own use. It can be taken again, and nobody on the team sees a score.

## The timesheet

- Weekly, in Ostrander's timesheet system, due Friday by 3:00. Dana approves it.
- Nothing is entered before the first Friday. Jane does the first one with the new hire. What goes in it is in Nadia's notes.

## What the new hire does not have

- Any access to Harlan Valley's current billing system. Nobody on the team works in it.
- Harlan Valley's internal network. The vendor wifi is separate.
- Permission to move anything out of DEV. Jane does that after review.
