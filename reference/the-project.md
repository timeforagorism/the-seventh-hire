# The project

What the team is here to do, where the work stands, and the words a new developer will hear on day one.

## In two lines

- Ostrander Systems is replacing the billing system at Harlan Valley Electric, a regional electric utility with about 310,000 customer accounts. The new system is Ostrander's own product, CIS.
- The billing team is the part of that project that makes sure the new system produces correct bills and correct notices.

## Why the client is careful

- Harlan Valley's last billing project was sold as eighteen months and ran ten years. The vendor left it unfinished and the billing floor finished it themselves.
- Ostrander is the second vendor. Everyone on the client's side remembers the first one.
- This is why the team writes things down, never promises what is not in the design, and treats the billing floor's time as scarce.

## Where the project is

- The contract runs 22 months. This is month 13.
- The billing design was signed by Glenn Marsh in month 3. His eleven items are in it, one by one. That design is the checklist the team builds to.
- The first trial conversion ran in month 4. It was the first time CIS ran on Harlan Valley's own data. It produced a list of defects, and the team has been working that list since.
- **The second trial conversion runs over the weekend that ends the new hire's fifth week.** That is what the team means by five weeks out. This is the hard date. It is the last full rehearsal of moving the client's data. The calendar date is on `plan/where-we-are.md`.
- After it, in order: about four months of fixing what it finds and retesting, which takes the project to month 18. Then three months of running every bill on both systems, months 19 to 21. Then the cutover weekend at the start of month 22. Go-live is the Monday after cutover.

## The eleven items

What the client's billing floor needs the new system to do that the current one cannot. Each has an owner on the team.

| # | Item | Team owner |
|---|---|---|
| 1 | Solar customers | Nadia |
| 2 | Budget billing true-up | Nadia |
| 3 | Rate changes | Jane |
| 4 | Time-of-use rates | Jane |
| 5 | Correcting bills in bulk | Nadia |
| 6 | Reports | Joanne |
| 7 | The nightly run finishing on time | Jane and Walt |
| 8 | The notice clock | Andre |
| 9 | Duplicate notices | Andre |
| 10 | Third-party copies of shutoff notices | Andre |
| 11 | Business mailing addresses | Joanne |

- The detail of each item, and how it was settled, is in `requirements/` in the project repository. It is not in this folder.
- Item 10 includes the team's one piece of custom work: a second copy of a shutoff notice for the roughly 600 accounts that name two people to receive one.

## How a bill gets made

The short version of the flow. Foundations module 2 is the long one.

1. A meter is read. Each account belongs to one of 20 billing cycles, by its read route.
2. One cycle bills each working night, about 15,500 accounts. The run starts at 9:00 p.m.
3. The system works out what each account owes from its reads and its rate.
4. Bills that fail a check drop out as exceptions for a person to look at.
5. The rest go into a print file. The outside print vendor needs it by 6:00 a.m.
6. If a bill is not paid, it starts down the notice path: a reminder, a written shutoff notice, a waiting period, a final contact attempt. The state commission sets the minimum days for each step.

A new developer's first job is to understand this flow. Everything the team builds is one step of it.

## Words a new hire will hear

- **CIS.** Ostrander's product. Customer information system, the usual name for a utility's billing system.
- **Standard.** What CIS does out of the box, for every Ostrander customer.
- **Custom work.** Something built only for Harlan Valley.
- **Cycle.** One night's batch of accounts to bill. There are 20 a month.
- **Exception.** A bill the system held back for a person to check.
- **True-up.** The yearly settling of a budget billing account, where the level payments are compared with real usage.
- **Trial conversion.** A full practice run of moving the client's data into the new system.
- **Parallel.** The three months when both systems bill every account and the results are compared.
- **Cutover.** The weekend the old system stops and the new one takes over. Go-live is the Monday after it.
- **The commission.** The state utility commission, which sets rates and billing rules.
- **The floor.** Harlan Valley's billing operations team, Glenn Marsh's people.
