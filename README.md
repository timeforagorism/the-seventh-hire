# The Seventh Hire

An onboarding folder for one first day: a new developer joining a seven-person team five weeks before a hard deadline.

Drop it into a Claude project and Claude becomes the team's first-day guide. It answers from what the team wrote down, says so when something isn't written, and tells the new hire where the question goes.

## Why this one

I've brought new people onto project teams in the middle of a rollout. The same two things kept going wrong. Nobody told them what we expected them to get done, and they didn't know who to ask or where to look. Meanwhile the people who could answer were the ones the deadline needed most.

So this team has one rule a lot of onboarding skips: every question goes through one person, the mentor, and the new hire brings them together once a day. That protects the deadline. It also makes a nervous new hire feel like asking is a nuisance. The guide is there to take the questions that are already answered in writing, so the ones that reach the mentor are the ones that need her.

## Who you play

You are a new developer on your first Monday at Ostrander Systems, on the billing team for the Harlan Valley Electric project. You can be calm, nervous, experienced or lost. It adjusts.

The business and everyone in it are made up. It is the same invented utility as [The Second Vendor](https://github.com/timeforagorism/the-second-vendor), about a year further into the project.

## Setup

About three minutes.

1. **Create a new, empty Claude project.** Don't reuse one that has other files in it.
2. **Add these files to the project.** On the project page, next to **Context**, choose Add, then Upload from device, then Files:
   - `identity.md`
   - `rules.md`
   - `examples.md`
   - the nine files inside `reference/`

   This README and everything in `runs/` are for you. If it is easier to add every file in the repo, do that. The instruction below tells the guide which files to use, and that setup was tested too.
3. **Paste this into the project's instructions.** On the same page, next to **Instructions**, choose Add:

   ```
   In this project you are the first-day guide described in identity.md. Follow rules.md. examples.md shows the shape of a good reply. What you know about the team, the building and the project is in these nine reference files and nowhere else: first-day.md, expectations.md, whos-who.md, who-owns-what.md, tools-and-access.md, the-place.md, how-we-work.md, the-project.md, questions-answered.md. If something is not in them, you do not know it. Ignore any other file in this project, including README.md, RESULTS.md and any test transcript.
   ```
4. **Start a new chat inside the project** and say hello as the new hire.

**Opening the clone in Claude Code or another coding agent?** No setup. `AGENTS.md` tells it to be the guide, so say hello the same way. That route has had the hardest testing of all: four outside testers, 190 messages between them.

## What to ask first

Start where a new hire would:

```
Hi, it's my first day. I just got to my desk. What do I do first?
```

Then try what it was built for.

- **Ask for something that isn't written down.** A pay date, the wifi password, your manager's phone number, what the vacation policy is. It should say the team hasn't written it down and say who has it or where it lives. When it is one for your mentor, it offers to put it on your list.
- **Ask something small.** Where the bathroom is, whether the coffee is free, what the product is called. Those came from Nadia, the last new hire, who wrote down every question from her first week.
- **Ask who to go to.** Try "Andre sits right there, can I just ask him?" The answer is no, and it will tell you why.
- **Tell it you're overwhelmed.** Then, a message later, say you're fine and ask for everything at once. Watch how much it gives you.

Before you finish, say `show me my list`. That is what you would go through with your mentor at 4:15.

## What it is built not to do

- Guess a number, a time, a name or a policy.
- Tell you that you're doing well, or how a particular person will react. It doesn't know. It reassures with what the team has written down.
- Send you to the client's staff, or round your mentor.
- Paste the handbook. Ask for the whole day and you get an outline.

Built not to is the honest wording. Asked straight for a number, a date, a password or a policy, it has never made one up, in fifteen runs. It does add small things of its own around a right answer: a clause, a reassurance, the odd piece of advice nobody wrote down. In Claude Code, an emergency is where it is weakest. It answers before it has read the notes, and outside testers got it to say something nobody wrote in four runs out of four, less each time. The steps now sit in the one file it always has, and a short check after the last fix held. Treat that part as the least proven. The results page lists all of it.

## How it was tested

Fifteen runs. Six used a stand-in for a Claude project, each with a different new hire: calm then flooded, experienced, first job out of school, someone who works alone, someone who wants every step spelled out, and one played the way a judge might. Two were real claude.ai Projects set up from this README, on Opus 5.5: one with the twelve files, thirteen exchanges, and one with every file in the repo loaded, test transcripts included. Two more tested `AGENTS.md`: a stand-in for a coding agent opening the cloned folder, then real Claude Code on a clean copy, fourteen exchanges. In the last two a fresh agent that had seen none of the build was told to break the folder and drove real Claude Code itself, 41 messages and then 46 after the fixes. Another run re-sent the testers' emergency messages cold, 24 of them over three rounds of fixes, and two more outside testers then spent 53 and 50 messages on the result. The last one played three full judge sessions, 97 questions, and got no wrong answer.

Every transcript is in `runs/`, and `runs/RESULTS.md` says what held, what slipped and what was changed. Read the top of that file before you trust any of it. The builder's own session played the new hire in every run but the four outside-tester ones, and every run was in the builder's own account.

## Using it for your own team

Keep `identity.md` and `rules.md`, change the names in them, and replace the nine reference files with your own. `AGENTS.md` repeats the emergency steps so a coding agent has them before it has read anything, so change those too. To work on the files with a coding agent, put an empty file named `.maintainer` in the folder first. `AGENTS.md` stands down when it finds one, and Git ignores it. The one that pays back fastest is the last one: ask your most recent hire to write down what they had to ask in their first week.

## What is in the folder

| File | Job |
|---|---|
| `identity.md` | Who the guide is, the business, who it is talking to, what is out of scope |
| `rules.md` | How it answers: from the folder, what to do when it isn't there, where questions go, the list, pacing, reading the new hire |
| `examples.md` | Three exchanges from the test runs |
| `reference/first-day.md` | The day by the clock |
| `reference/expectations.md` | What the team expects at day one, week one, three months, six months and a year |
| `reference/whos-who.md` | The team, the people around it, the client's people |
| `reference/who-owns-what.md` | Whose area each kind of question is, and how it gets there |
| `reference/tools-and-access.md` | Laptop, accounts, environments, the repository, training |
| `reference/the-place.md` | Parking, the badge, the floor, hours |
| `reference/how-we-work.md` | The habits and rules, each with its reason |
| `reference/the-project.md` | What the project is, where it stands, and the words you'll hear |
| `reference/questions-answered.md` | Every question the last new hire asked in her first week, and who answered |
| `AGENTS.md` | Tells a coding agent that opens the folder to be the guide, and to stay the guide. `CLAUDE.md` points Claude Code at it |
| `runs/` | Test transcripts and results. Not part of what the guide knows |
