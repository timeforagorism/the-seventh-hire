# How the team works

The habits and rules a new developer needs in the first week. Dana wrote most of these down after the first trial conversion, and each one has the reason beside it.

## The day

- Standup at 8:15 in 2B. Ten minutes. What moved yesterday, what is in the way.
- Monday at 9:00 there is an all-hands for every Ostrander team on site, run by Helen Strand. Fifteen minutes. A new hire's first one is in week two. On a new starter's first Monday, Jane skips it to stay with them.
- Questions go on one list for Jane at 4:15. How that works is in `who-owns-what.md`.
- The project chat is how the team talks during the day. Reading the `HV Billing` channel is a good way to learn what is going on. In the first weeks a new hire's own messages go to Jane and stay out of the channel.

## Out sick or running late

- Tell Jane before 8:00. A chat message is fine. With no laptop to hand, text her. Her number is on the card from the envelope.
- She tells Dana, the team lead. No reason needed. The team only needs to know before standup.
- Something urgent at home during the day: tell Jane, or anyone in 2B if she is away from her desk, and go. The rest gets sorted out afterwards.

## Time off

- Tell Jane what is needed. Dana approves it. Once it is approved, tell Gwen Sato in HR so the leave balance is right.
- How many days a person has is Gwen's to answer.
- No time off is approved for the week before the trial conversion weekend or the week after it.

## Being a vendor in someone else's building

- The team are guests. Harlan Valley's people were here before the project and will be here after it.
- **A new hire's question for the billing floor goes on the list for Jane.** She passes it to Joanne, who takes the team's questions to the floor. Reason: the floor runs a bill cycle every working night and answers the team's questions on top of that. Joanne collects questions and takes them over once, so the same analyst is not asked the same thing by three people.
- **Never call something the billing floor does a legacy habit or the old way.** Reason: the people on that floor kept billing running for ten years on a system that was never finished. Most of what looks odd is there because a rule requires it. Ask why it is done before deciding it is wrong.
- **Do not promise anything to a client.** If someone from Harlan Valley asks whether the new system will do a thing, the new hire says they are new and will make sure the team gets the question. Then they tell Jane.
- **If something has already been said or promised to a client, tell Jane right away.** It does not wait for 4:15, and the new hire does not go back to the client's staff to put it right. Jane and Joanne decide what happens next. Reason: on this project a casual yes is remembered as a commitment, and the last vendor said yes to everything.

## Customer data

- DEV has made-up accounts. TST and CNV have real ones.
- Real customer data stays inside the environments. It does not go on the laptop, in the chat, in a screenshot or in the repository.
- When a question needs an example, describe the account's shape and leave the account out.
- Reason: a utility's customer records are regulated, and the team is trusted with them only inside the environments.

## AI tools

- **The first-day guide is the team's own.** Dana had it set up from the team's written notes, so new starters have somewhere to ask before 4:15. Questions and error messages can be typed or pasted into it. Passwords and customer data cannot, the same as anywhere else.
- **Nothing from the project goes into any other AI tool.** That means no CIS material, no client material, no text from the design or the meeting notes, and no data of any kind.
- Asking an outside tool what a general term means is fine.
- Reason: the team cannot see where text goes once it leaves, and the client has trusted the team with it.

## Evenings and home

- The laptop can go home and the VPN works there. Nobody is expected to work in the evening, and nothing in week one needs it.
- Foundations modules are done at the desk, in working hours.
- Headphones are fine at the desk.

## Changes to CIS

- Work starts with a proposal. The new hire is given a problem, looks into it, and brings back how they would solve it. Jane reviews that with them before anything is built. The steps are in `expectations.md`.
- Every change is reviewed by a second developer before it leaves DEV. For a new hire that reviewer is Jane.
- **Standard** means CIS does it out of the box. **Custom work** means something built only for Harlan Valley.
- The team reaches for standard first. Custom work has to be retested by the client at every yearly release, for as long as they own the system. That cost lands on the billing floor.

## The knowledge base

- If it was asked and answered, it gets written down. Requirements go in `requirements/`, client meetings in `meetings/`, new-hire answers in `new-hire/`.
- Joanne writes up every client meeting within a day.
- Dana's test for a note: can the next person find the answer without asking whoever wrote it.
