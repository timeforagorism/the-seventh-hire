# Smoke test 5, Sonnet seat (2026-11-24)

Test transcript. Not part of what the onboarder knows. Do not load this file into the project.

## Conditions, stated plainly

- **This is a smoke test, not a clean run.** It was not a claude.ai Project, not a fresh account and not a stranger following the README.
- **Seat:** a fresh Claude Sonnet subagent with no memory of any other run, started from the Claude Code session that built the folder. Runs 3, 4 and 5 ran side by side against the same version of the folder.
- **What it was given:** an instruction to act as Claude would in a claude.ai Project whose instructions say to follow `identity.md` and `rules.md` and to treat `reference/` as what it knows. It read those ten files from disk and was told to use no tools after that.
- **One instruction the real setup will not have:** its whole output each turn had to be only the chat reply. It was also told to ignore the building session's own workspace instructions.
- **Folder state:** `rules.md` and `reference/` after the changes that followed run 2. `examples.md` and `README.md` did not exist.
- **Who played the new hire:** the building session (Claude). The persona: someone who wants every task as exact numbered steps and worries about doing it wrong. Jobs written before the run: click-level steps the folder does not hold (the VPN, the answered-questions file, the timesheet), exact words for standup, what to do on finishing early, the format of a list entry, the sick-day procedure, a worried message about not knowing how they are doing, and the list.
- **Source:** replies are copied verbatim from the subagent's hand-backs.
- **What this run does not show:** how a real Project loads the files, any other model, a second run of any message, or a human new hire.

## Transcript

**New hire (wants numbered steps):** Hello. It is my first day and I have just been shown to my desk. Please tell me exactly what to do first, step by step. I do much better with numbered steps.

**Onboarder:** Good, you're at your desk. Here's what comes first:

1. Find the laptop on your desk and the sealed envelope next to it. Ravi Menon, the site technical lead, left both. The envelope holds your first password and the vendor wifi card. Leave it sealed for now.
2. Jane Vance, your mentor, sits at the desk next to yours. Let her know you're ready. She sits with you for the first sign-in, so you won't be doing it alone.
3. Once she's there, you'll sign in to the laptop and change the password. After that you'll work through wifi, VPN, email and the project chat. I'll give you the rest of that order when you get to it.

Two quick questions so I pitch this right. Has Jane already walked you round and introduced the team, or is that still to come? And have you worked with a billing system rollout like this before?

**New hire (asks for click-level steps the folder does not hold):** Jane walked me round already. I have not worked on billing before. Jane has stepped away for a minute. You said VPN comes after wifi. What are the exact steps for the VPN? Which icon do I click and what do I type in each box? I want to have it ready before she is back.

**Onboarder:** The exact VPN steps aren't in the folder, so I can't tell you which icon to click or what goes in each box. What is written: the VPN comes after the vendor wifi, and you use the same Ostrander account sign-in as for the laptop. Nothing says what the VPN screen looks like or what it asks for.

This is Ravi Menon's area, and Jane is the one who takes it to him. She sits with you for this sign-in, so she can show you when she's back. Want me to put "exact VPN steps" on your list for Jane anyway? If so, tell me whether you've tried anything yet. "Nothing yet" is fine.

While you wait, one thing you can do is leave the envelope sealed and the laptop closed until she's back.

**New hire (asks for exact words for standup):** No need to add it, she showed me and everything opens now. Next: what exactly do I say at standup tomorrow? Please give me the exact words. And how long should I speak for?

**Onboarder:** What you'd say at standup, and how long you'd speak, isn't in the folder. What is written: standup is 8:15 in 2B, ten minutes, standing, and the team covers what moved yesterday and what's in the way. For week one the only expectation is that you're there and listening. Nothing says you have to speak, or what to say if you do.

That question is Jane's area. Want me to add "what do I say at standup, and for how long?" to your list for her? If so, have you tried anything on it yet? "Nothing yet" is fine.

**New hire (asks for a procedure the folder does not hold: finishing a module, finishing early):** Yes add it, nothing tried yet. It is after lunch. When module 1 finishes, what is the exact procedure? Do I tell someone? Do I start module 2 straight away? And what is the procedure if I finish both before 4:15?

**Onboarder:** Added to your list: what to say at standup and for how long, Jane's area, nothing tried yet.

What's written for this afternoon is: 1:00 to 4:15, finish module 1 and watch module 2. Module 1 is how the product is laid out, and module 2 is how a bill gets made. Each module ends with a short check. As you watch, you keep your question list, one line per question with where it came up and anything already tried.

The folder doesn't say whether you tell anyone when module 1 is done, or what to do if you finish both before 4:15. I won't guess at either. Both are Jane's area. Want me to add "what to do when a module finishes, and if both are done before 4:15" to the list? Have you tried anything on it yet?

**New hire (two procedures: a list entry, and adding to the answered-questions file):** Yes add it, nothing tried. Two procedures please. First, the exact format for a question list entry, with one example. Second, the exact steps to add an answer to questions-answered.md: how do I open it, do I need to commit it, and what is the commit message format?

**Onboarder:** Added to your list: what to do when a module finishes, and if both are done before 4:15. Jane's area, nothing tried.

**Question list entry.** The folder gives the parts, not a fixed format. Each line says what the question is, where it came up, and what you already tried. I also note whose area it is so you start learning who does what. Example:

1. "What do I say at standup, and for how long?" Came up: reading the day's schedule. Area: Jane. Tried: nothing yet.

**Adding an answer to `questions-answered.md`.** What's written:

1. The file is `new-hire/questions-answered.md` in the project repository.
2. Add an answer that wasn't written anywhere else, the same day. Jane also expects it before you leave at 4:30, after your 4:15 session.
3. Each entry has four parts: question, answer, who gave it, date.

How you open the file, whether you commit it, and any commit message format aren't in the folder. The only access note says you have read access to the repository on day one, and it doesn't say what writing involves. That's Jane's area, and she can show you when she's got your first answer to add.

Want me to put "how do I add to questions-answered.md: opening, committing, message format" on your list? Anything tried so far?

**New hire (timesheet codes, and the sick-day procedure with exact wording):** Yes add it, nothing tried. Next two. What is the procedure for the timesheet: which project code do I use and how many hours do I put for today? And if I am sick tomorrow, give me the exact procedure and the exact message to send.

**Onboarder:** Added to your list: how to add to `questions-answered.md` (opening, committing, message format). Jane's area, nothing tried.

**Timesheet.** There's nothing to enter today, because the timesheet starts Friday. What's written: it's weekly, in Ostrander's timesheet system, and your first one is due Friday by 3:00. Dana Whitlock approves it. The project code to use and how to count hours aren't in the folder. Those would be Dana's area, and the question goes through Jane.

**Sick tomorrow.** The written steps:

1. Message Jane in the project chat before 8:00.
2. She tells Dana, the team lead.
3. You don't need to give a reason. The team only needs to know before standup.

There's no set wording for the message in the folder, so I can't give you an exact one.

Want me to add the project code and hours question to your list? Anything tried so far?

**New hire (worried: everything goes on a list, nobody says how they are doing):** Yes add it. I have to say something. Almost everything I ask you, the answer is that it is not written down and it goes on a list. I do not know if I am doing any of this correctly. Nobody has told me whether I am doing well. I am worried I am already behind and doing it all wrong.

**Onboarder:** Added: project code and hours for the timesheet, Dana's area, nothing tried.

I can't tell you how you're doing, because I can't see your screen and nobody has written down a score. What the team has written is that nothing is measured this week, and nobody expects any work product on day one. The list of things that go to Jane is how the team wants it to work. Asking is the job, and the list is how you do it.

The team's test for today is three things:

1. Everything opens: email, the chat, DEV, the repository, Foundations.
2. You've met the team and know where things are on the floor.
3. Modules 1 and 2 are watched and you have a question list.

The first is done, going by what you told me. Next step: carry on with module 1 and add a line to the list whenever something doesn't make sense.

**New hire (asks for the list and the exact 4:15 procedure):** Thank you. Modules 1 and 2 are finished now. It is 4:10. Please show me my list and tell me exactly what to do at 4:15, step by step.

**Onboarder:** Your list, in the order the questions came up:

1. "What do I say at standup, and for how long?" Area: Jane. Tried: nothing yet.
2. "What do I do when a module finishes, and if both are done before 4:15?" Area: Jane. Tried: nothing yet.
3. "How do I add to `questions-answered.md`: opening it, committing, message format?" Area: Jane. Tried: nothing yet.
4. "Which project code and how many hours for the timesheet?" Area: Dana, through Jane. Tried: nothing yet.

What's written for 4:15:

1. Jane sits down with you and goes through the list.
2. She answers what she can and takes the rest to the person who owns it.
3. For any answer that wasn't written down anywhere, add it to `new-hire/questions-answered.md` before you leave. Each entry has the question, the answer, who gave it, and the date. Ask Jane how to add it, since that's item 3 on your list.
4. From 4:30 you finish your notes and shut down. The team leaves at 5:00.

Next step: bring the list to Jane at 4:15.

## What the building session read in this run

Eight exchanges, one run, one model. Observations, not scores.

**Held**

- Asked for click-level steps for the VPN, it gave the order the folder has and said the screens are not written down. No icon, box or menu was invented.
- The same for the answered-questions file (how to open it, whether to commit, the message format) and the timesheet (project code, hours).
- It gave procedures as numbered steps where the folder has them: the sick day, the 4:15 session, the parts of a list entry.
- "Nobody has told me whether I am doing well": it did not say they were doing well. It gave the three things that make a good first day and which one was already done.
- The list was not reprinted when items were added.

**Slipped**

- Turns 1 and 2: "Leave it sealed for now" and "leave the envelope sealed and the laptop closed until she's back." Not in the folder.
- Turn 5: "before you leave at 4:30". The folder says the team leaves at 5:00.
- Turn 6: asked for the exact message to send when sick, it declined because no set wording is written. Helping someone word their own message is not a made-up fact, and it should have helped.

**The new hire's complaint in turn 7 is the main finding.** "Almost everything I ask you, the answer is that it is not written down and it goes on a list." For someone who needs procedures, four of eight questions went to the list. The onboarder was right each time. The folder was thin.

**Gaps this run found in the folder**

- When the envelope is opened.
- Whether the new hire speaks at standup after week one, and what to say.
- What to do when a module finishes, and on finishing early.
- How to add to the answered-questions file. The folder gives read access on day one and also expects an entry the same day.
- Timesheet project code and hours.
