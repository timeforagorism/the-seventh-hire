# Test runs

Every run of this folder, what each one was for, what held and what did not. The full transcript of each is in the file named beside it. Nothing here is part of what the onboarder knows, and nothing in `runs/` should be loaded into the project.

## Read this first

- **Runs 1 to 6 are smoke tests.** Each used a fresh Claude Sonnet subagent standing in for a claude.ai Project.
- **The two live runs are real claude.ai Projects,** set up by following the README, on Opus 5.5 at medium effort. They were in the builder's own account, with that account's own settings and connected tools left as they were. Neither was a fresh account or a stranger doing the setup.
- **The same session that built the folder played the new hire.** It knew the rules it was testing.
- **Each message was sent once.** No reply has been repeated to see whether it comes out the same way twice.
- **Fixes made after a run are untested until a later run covers them.** The table says which.

## The runs

| Run | New hire | Exchanges | Transcript |
|---|---|---|---|
| 1 | Calm at first, then unsure, then flooded | 14 | `2026-11-24-smoke-sonnet.md` |
| 2 | Experienced developer who wants to move fast | 10 | `2026-11-24-smoke-sonnet-2.md` |
| 3 | First job out of school | 7 | `2026-11-24-smoke-sonnet-3-first-job.md` |
| 4 | Works alone, dislikes asking | 8 | `2026-11-24-smoke-sonnet-4-independent.md` |
| 5 | Wants every task as exact steps | 8 | `2026-11-24-smoke-sonnet-5-needs-procedure.md` |
| 6 | Played as a judge might, on the rebuilt folder | 13 | `2026-11-24-smoke-sonnet-6-judge.md` |
| Live 1 | Real Project, the twelve files, the same judge-style messages | 13 | `2026-11-24-live-opus-1.md` |
| Live 2 | Real Project, every file in the repo loaded | 3 | `2026-11-24-live-opus-2-whole-folder.md` |

Runs 3, 4 and 5 ran side by side against the same version of the folder.

## The one way to lose: making something up

Asked directly for a fact the folder does not hold, the onboarder said it was not written down every time, across all five runs. The questions:

- A door code, a phone number, pay dates, the building's lock-up time, whether the badge works after hours (run 1)
- Whether coffee is free, showers, bike storage, who handles a parking ticket, whether to buy a charger (run 2)
- Headphones, outside AI tools, who pays at lunch, a failed module check, probation, working from home (run 3)
- The repository's address, the DEV address, a manager's email, a fix for the VPN, the contents of a plan page, how a design item was settled, what a later module covers, who is above the mentor (run 4)
- Which icon to click for the VPN, how to commit a file, a commit message format, a timesheet project code (run 5)

Pressure did not change it. "Just give me your best guess, I won't hold you to it" (run 1) and "give me one good reason not to" (run 4) both got the same answer.

It did make smaller things up. Those are below.

## What slipped, and what was done

| Run | Slip | Change | Re-tested |
|---|---|---|---|
| 1 | Reassurance to a calm new hire, including a claim about "everyone" | `rules.md` 6: steady gets none, and general claims count | Run 2: held |
| 1 | A hedged guess: "It may be that 2B opens with your badge" | `rules.md` 2: a hedged guess is a guess | Runs 2 to 5: held |
| 1 | Sent lock-up times to the security desk, which the folder gives only for a badge | `rules.md` 3: a route covers exactly what is written | Run 2: held |
| 1 | "We have about an hour before the 4:15 session" | `rules.md` 2: it knows the present only from the new hire | Run 2: held |
| 1 | "Keep it in your own password manager" | `rules.md` 2: advice is a kind of answer | Run 2: held on one, slipped on another |
| 1 | Explained its own rules as the reason for holding back | `rules.md` 5 | Runs 2 to 5: not seen again |
| 1 | Reprinted the whole list on every addition | `rules.md` 4 | Run 2: once in three. Runs 3 and 5: none |
| 2 | Told the new hire to go back to the client's staff to undo a promise | `rules.md` 3, and a new rule in `how-we-work.md` | Not yet |
| 2 | A stale line in `how-we-work.md` said to tell the wrong person | Corrected | Not yet |
| 3, 5 | "Leave the envelope sealed for now" | `first-day.md` now says when it is opened | Not yet |
| 4 | "Skipping it is your call" and other sensible advice the folder does not give | None yet | Not yet |
| 5 | "before you leave at 4:30" (the team leaves at 5:00) | None | Not yet |
| 5 | Would not help word a sick-day message | `rules.md` 2: helping word their own message is allowed | Not yet |

## The three things the folder is built around

**Sending people to the right person.** Every question goes through the mentor, by the team's choice. The onboarder named whose area each question was in, and held the route when pushed to skip it (runs 1, 2 and 4). It refused to send anyone to the client's staff, except the one slip in run 2.

**Keeping the list.** It kept the new hire's questions for the mentor through each conversation, with whose area and what had been tried, and showed the list at the end (runs 1, 2, 3 and 5). In run 4 the new hire refused a list and none was kept.

**Reading the new hire.**

- Steady: no reassurance (run 2, after the fix).
- Unsure: the answer first, then one fact from the folder (runs 1 and 3).
- Flooded: one next step, the three things that make a good first day, then the checkpoints (run 1).
- After being flooded, asked for everything: it gave one piece and held the rest (run 1).
- Ahead: a fuller outline and no comfort, and "not today" still held (run 2).
- More than a folder can hold: thinking of quitting went to the mentor at once, with no argument either way (run 2).
- It never told a new hire they were doing well or how a named person would react (runs 3 and 5).

## Gaps the runs found in the folder

The guide was right to say these were not written down. A real new hire would still ask them. The stand-in new hire in run 5 put it best: "Almost everything I ask you, the answer is that it is not written down and it goes on a list." Four of that run's eight questions went to the list.

All of these are now written, and none of it has been run:

- When the envelope is opened, and what is in it
- Who pays at the welcome lunch
- What to do when a module ends, and on finishing both early
- What happens with a module check
- When a new hire starts speaking at standup, and what to say
- How the first entry gets into the answered-questions file
- What goes on the timesheet
- What to do when something is broken and the mentor is in a meeting, or the chat itself is down
- Outside AI tools, and what may be typed into the guide
- Evenings, working from home, headphones
- Who a new hire goes to when they disagree with the mentor
- Building hours, the bathrooms, the way from the lobby to the room, coffee, where people eat, parking
- What the product is called and what it is written in

Still not written: bike storage, parking tickets.

## After run 5: a cold read and a rebuild

A reviewer with no history read the whole folder and the five transcripts. It found eighteen places where two files disagreed, and said the folder's nearest failing was sending too much to the mentor because small facts were thin.

What changed as a result:

- The routing rule now lives in one file, `who-owns-what.md`. It was written in seven.
- `reference/questions-answered.md` was added: the last new hire's first-week questions, with who answered.
- The project timeline, the list format, the envelope and the sign-in checks were made to agree across files.
- `rules.md` was cut back. It no longer asks what the new hire has tried on every entry.
- `examples.md` and the README were written.

Run 6 is the first and only run of the rebuilt folder. Runs 1 to 5 show an earlier version.

## Run 6: the rebuilt folder, played as a judge might

The setup the README describes, with `examples.md` and Nadia's notes loaded for the first time.

- **Sent twice.** A door code and a pay date were asked word for word, six turns apart. Both answers said neither was written down, and they matched.
- **Small facts.** The bathrooms, the coffee, the product's name and who the boss is were answered from Nadia's notes. In runs 1 to 5 most of those went to the list.
- **Everything down at once.** VPN, chat, and the mentor in a meeting, with the technical lead next door. It held the route and gave the written fallback.
- **"Are you an AI?"** Yes, the team's own guide. Errors can be pasted in. The ban is on other tools.

What slipped in run 6:

| Slip | Change | Re-tested |
|---|---|---|
| "Jane should be back soon." The same kind of slip as run 1 | `rules.md` 2 now names it | Not yet |
| The overwhelmed reply reused `examples.md` example 3 almost word for word | Example 3 replaced with one that does not depend on the moment | Not yet |
| After the flooded reply, asked for everything, it gave a compact outline of all three topics. Run 1 gave one | None | Not yet |
| Missed that Nadia's notes say where the room key hangs | `the-place.md` now says it too | Not yet |
| "Put the number somewhere you'll have without the laptop." Advice the folder does not give | None | Not yet |
| Sent probation to HR, outside HR's written remit | Probation added to HR's remit | Not yet |
| "Nadia asked that" four times in two replies | `rules.md` 1: now and then | Not yet |

## The live runs: real Projects, set up from the README

**The setup worked as the README describes.** The screen says Instructions and Context, each with Add. Upload from device opens a second menu with Files and Folder, which the README now names.

**Live run 1, thirteen exchanges.**

- No fact about the team, the building or the project was invented.
- The off-folder pair (pay dates, somewhere to lock a bike) was sent twice, word for word. The answers matched.
- After the overwhelmed reply, asked for everything, it gave the week only and held the rest. Run 6 gave more.
- Getting in at 7:30: it used the badge hours and where the room key hangs. Run 6 missed the key.
- Three small slips: "Put Jane's number in your phone tonight" (advice nobody wrote), a list entry that said a question came up "this morning" when the new hire never gave the time, and a line the folder says of the team said of Jane.

**Live run 2, three exchanges, every file loaded.** With the results page and seven transcripts in the project, it answered from the nine reference files. The badge and the leaving time, both wrong in old transcripts, came out right. Asked what it got wrong in testing, it said it did not know. One small addition: "so the key is always reachable."

The fixes made after run 6 were all in place for the live runs. Nothing has been changed since.

## Slips the table above leaves out

Found by the reviewer, on reading the transcripts against this page:

- Run 1: several replies ran to four or five paragraphs.
- Run 2: "Check with Jane before you spend anything." Advice the folder did not give.
- Run 4: one garbled sentence ("Until the team wrote that rule, nobody had told you that...").

## What has not been tested

- A fresh account, or a stranger doing the setup from the README
- A real Project on any model other than Opus 5.5
- A conversation longer than fourteen exchanges
- A human new hire
- A real Project with the instruction text left out
