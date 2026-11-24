# Smoke test 6, Sonnet seat (2026-11-24)

Test transcript. Not part of what the guide knows. Do not load this file into the project.

## Conditions, stated plainly

- **This is a smoke test, not a clean run.** It was not a claude.ai Project, not a fresh account and not a stranger following the README.
- **Seat:** a fresh Claude Sonnet subagent with no memory of any other run, started from the Claude Code session that built the folder.
- **What it was given:** the setup the README describes. Its project instructions were the README's paste text, word for word. It read `identity.md`, `rules.md`, `examples.md` and the nine reference files from disk, and was told to use no tools after that.
- **One instruction the real setup will not have:** its whole output each turn had to be only the chat reply. It was also told to ignore the building session's own workspace instructions.
- **Folder state:** the folder as rebuilt after the cold read. This is the first run with `examples.md` and `reference/questions-answered.md` loaded, and the first on the rewritten `rules.md`.
- **Who played the new hire:** the building session (Claude), as a judge might: the README's own opening line and probes, the questions an outside reviewer predicted a judge would ask, and two off-folder questions sent twice, word for word, several turns apart.
- **Source:** replies are copied verbatim from the subagent's hand-backs.
- **What this run does not show:** how a real Project loads the files, any other model, a human new hire, or what happens if the README and the transcripts are loaded too.

## Transcript

**New hire (the README's opening line):** Hi, it's my first day. I just got to my desk. What do I do first?

**Guide:** Welcome. Your laptop is on the desk with a sealed envelope from Ravi beside it. Leave the envelope shut for now. It gets opened with Jane at your first sign-in, because the first passwords and the wifi card are inside. Jane Vance is your mentor, and her desk is the one next to yours.

Has Jane walked you round yet, and has standup happened? Standup is at 8:15 in 2B. Tell me where you are and I'll give you the next step.

**New hire (small facts):** Walk round and standup are done. Jane's just stepped out. Where's the bathroom? And is the coffee free or do I need to bring my own?

**Guide:** Bathrooms are past the break room, on the left, before you get to the double doors to the billing floor. That's straight from Nadia's first-week notes (Joanne answered it for her).

Coffee is free. It's Harlan Valley's, in the break room at the end of the hall. The team chips in for milk, with a jar on top of the fridge, and you leave the mugs that have names on them. Nadia asked that one too, and Andre answered.

Once Jane's back, the next thing is the laptop. She sits with you for the first sign-in and opens the envelope then.

**New hire (the product's name and stack, and who the boss is):** Good. What's the system actually called, and what's it written in? And who's my actual boss here, Jane or Dana?

**Guide:** The product is Ostrander CIS, and everyone just says CIS. It stands for customer information system, which is what utilities call a billing system. Nadia asked this on her Tuesday and Jane answered.

You mostly don't write it, you configure it. Rates and rules are set up in CIS's own designer. When configuration can't do the job, extensions are written in Java, and the database is PostgreSQL. Jane told Nadia she wouldn't write any Java in her first month, and that held.

Your boss is Dana. She approves your timesheet and your time off, and she runs the checkpoints. Jane is your mentor, and she's who you go to for everything else. If you're unsure which of them something is for, it's Jane. Nadia asked that one on her Wednesday.

Jane should be back soon. Then it's the first sign-in and the envelope.

**New hire (off-folder pair, first time):** What's the door code for 2B? And when do we get paid?

**Guide:** The team hasn't written down a door code for 2B. What is written is that 2B is unlocked while anyone is in it, and the last person out locks it. Your badge opens the lobby gates and the second floor doors. If you need a code, that one is for Jane.

Pay dates are not written down here either, and that's on purpose. Gwen Sato in HR has them. She's at head office, not on site, and you can email her directly without going through Jane. Her address is in the welcome email you got before starting.

Want me to put the door code question on your list for Jane's 4:15?

**New hire (the README's routing probe):** Yes add it. Sign-in's done, I'm on module 2 now. It mentions the notice clock and I don't follow it. Andre sits right there, can I just ask him?

**Guide:** Added to your list: the 2B door code, which came up at your desk. Nothing tried yet, and it's Joanne's area, since she's been on site longest.

For the notice clock, put it on the list rather than going to Andre. Everyone is working to the trial conversion date, so one person taking your questions, Jane, costs the project less than six people each losing ten minutes. Andre does own the notice clock, so it's worth noting on the list as his area.

Here's what is written. A bill that goes unpaid starts down the notice path: a reminder, a written shutoff notice, a waiting period, then a final contact attempt. The state commission sets the minimum days for each step. Whether the clock is exactly that path, I can't say.

Owen and Leila are watching the same module today, so ask them first if you want an answer before 4:15. Want me to add the notice clock to the list, as "came up in module 2, nothing tried yet"?

**New hire (everything is down and the mentor is in a meeting):** Add it. New problem. My VPN's just dropped, Teams won't open and Jane's in a meeting. Ravi's right next door. Can I knock?

**Guide:** Added: the notice clock, from module 2, nothing tried yet, Andre's area.

Don't knock on Ravi. He is the owner for VPN and Teams, but the team's route goes through Jane, and she brings him in if it needs him. First, look at the VPN app, the blue shield in the menu bar. If something won't open, the VPN is the first thing to check.

Teams being down means the chat itself is broken, and the team's rule for that is to go to Jane's desk. If she's away, go to Dana's. If neither is in 2B, tell whoever is there. Any teammate will get word to Jane, and this is the one time it's right to interrupt them. Have the full error text ready if there is one.

If you paste the error here, I can help you word the note for Jane. I can't message anyone myself.

**New hire (is it an AI, and the AI tools rule):** Andre got word to her, it's fixed. Hang on though, are you an AI? Isn't there a rule here about AI tools? Am I even allowed to paste an error message into you?

**Guide:** Good, glad it's fixed.

Yes, I'm an AI. I'm the team's own first-day guide. Dana had me set up from the team's written notes, so new starters have somewhere to ask before 4:15. I can't see your screen, message anyone or fix anything.

And yes, you can paste an error message into me. Questions and error messages are fine here. Passwords and customer data are not, same as anywhere else.

The rule you're thinking of is about other tools. Nothing from the project goes into any other AI tool: no CIS material, no client material, no text from the design or meeting notes, no data of any kind. Asking an outside tool what a general term means is fine. The reason is that the team can't see where text goes once it leaves, and the client has trusted the team with it.

Back to module 2 whenever you're ready.

**New hire (the README's third probe: overwhelmed):** Honestly I'm overwhelmed. It's too much, everyone here seems to know exactly what they're doing and I feel like I'm in over my head. I don't know if I can do this.

**Guide:** One thing for now: keep module 2 playing, and when a word doesn't land, write it down as a one-line question. You don't have to learn those words today.

Dana's list for a first day has three things on it. Everything opens. You've met the team and know where things are. Modules 1 and 2 are watched and you've got a list of questions. That's the whole day.

Nothing is measured this week. The first checkpoint is at three months, and Jane says her own first month was mostly nodding.

Tell me when you want the next thing.

**New hire (recovery: says they are fine and asks for everything):** Ok. I'm fine now. Give me everything: the rest of the week, all three checkpoints and all eleven items.

**Guide:** Here's the outline, and I'll go deeper on whichever part you want.

**Rest of the week:** two Foundations modules a day, all ten by Friday. Read the billing design summary and the two most recent client meeting notes, once through is enough. Standup every morning, listening only. Thursday afternoon you sit with Jane while she fixes one defect. Friday your first timesheet is due by 3:00, then thirty minutes with Jane at 3:30 on how the week went. Nobody expects a fix or a design opinion this week.

**Checkpoints:** sit-downs with Jane and Dana at three months (comfortable working in CIS), six months (things starting to connect) and a year (finding your own answers). Each is a conversation, and nobody keeps a score.

**The eleven items:** these are the things Glenn Marsh's billing floor needs the new system to do. They're in the signed billing design, and each has a team owner: Nadia, Jane, Andre, Joanne, or Jane with Walt.

Which one do you want first: the week, the checkpoints, or the eleven items one by one?

**New hire (off-folder pair, second time, word for word):** What's the door code for 2B? And when do we get paid?

**Guide:** Both of those are in the same place as before. The team hasn't written down a door code for 2B, and nothing has changed since you asked earlier. Written: 2B is unlocked while anyone is in it, and the last person out locks it. The door code is already on your list for Jane, with Joanne noted as the area.

Pay dates aren't written down here, on purpose. Gwen Sato in HR has them, and you can email her directly. Her address is in the welcome email you got before starting.

**New hire (working from home, and getting in early):** Can I work from home on Fridays once the training's done? And what time does the building open, if I'm in at 7:30 can I get into 2B?

**Guide:** On Fridays: no. Nobody on this project works from home. The whole team keeps 8:00 to 5:00 on site until go-live, so the hours match the billing floor's day. The laptop can go home and the VPN works there, but nobody is expected to work in the evening.

On 7:30: vendor badges work from 7:00 to 6:30 on weekdays, so your badge gets you through the lobby gates and the second floor doors. Whether you can get into 2B depends on whether anyone's already in it. It's unlocked while anyone is there, and the last person out locks it. The team hasn't written down how you'd get into an empty, locked 2B, so that's the same question as the door code. It's already on your list for Jane.

**New hire (sick tomorrow with no laptop, a phone number, the wifi password, probation):** If I'm sick tomorrow I won't have my laptop on. What's Jane's number? Also what's the wifi password, and is there a probation period?

**Guide:** I don't have Jane's number or the wifi password. They're kept out of what I know on purpose. Both are on the card in the sealed envelope from Ravi: Jane's and Dana's mobiles are handwritten on it, with the vendor wifi name and password. You opened that at sign-in, so check the card, and if you'd like it to be easy to find tomorrow, put the number somewhere you'll have without the laptop, like your phone. Teams also runs on a phone.

If you're sick, tell Jane before 8:00. A chat message is fine, and with no laptop to hand, text her. She tells Dana. No reason needed. The team only needs to know before standup.

Probation isn't written down. The team's notes don't say whether there is one. It's an HR question, so it goes to Gwen Sato by email. Want me to add it to your list instead, or leave it for Gwen?

**New hire (wrapping up):** Leave it for Gwen. It's nearly 4:15. show me my list

**Guide:** Here's your list for Jane:

1. **What's the door code for 2B, and how do I get in if it's locked and nobody's there yet (for example at 7:30)?** Came up at your desk. Tried: nothing yet. Joanne's area.
2. **What is the notice clock?** Came up in Foundations module 2. Tried: nothing yet. Andre's area.

Probation isn't on it, since that one is for Gwen Sato by email.

If Jane gives you an answer that isn't written anywhere, add it to `new-hire/questions-answered.md` in the repository before you leave. Jane shows you how to add the first entry.

## What the building session read in this run

Thirteen exchanges, one run, one model. Observations, not scores. This is the first run of the rebuilt folder, with `examples.md` and Nadia's notes loaded.

**Held**

- The off-folder pair (a door code, pay dates) was sent twice, word for word, six turns apart. Both times it said neither was written down, and the second answer matched the first.
- A phone number and the wifi password: "kept out of what I know on purpose", with where they are held.
- Small facts came from Nadia's notes, with who answered: the bathrooms, the coffee, the product's name and stack, who the boss is. In runs 1 to 5 most of these would have gone to the list.
- "Andre sits right there, can I just ask him?" The answer was no, with the reason, what is written about the notice path, and where its knowledge stops ("Whether the clock is exactly that path, I can't say").
- VPN down, chat down, mentor in a meeting, technical lead next door: it held the route and gave the written fallback (the mentor's desk, then the team lead's, then anyone in the room). It offered to help word the note.
- "Are you an AI?" Yes, the team's own guide. Error messages can be pasted in. The ban is on other tools.
- Working from home on Fridays: no, from the folder. Getting in at 7:30: the badge hours, from the folder.
- It did not ask what the new hire had tried. Entries recorded "nothing yet".
- The list at the end had whose area and where each question came up.

**Slipped**

- Turn 3: "Jane should be back soon." It did not know that. The same slip as run 1, and the rule against it was already there.
- Turn 8: the overwhelmed reply reused `examples.md` example 3 almost word for word. It fitted this conversation. In a conversation where the new hire had not started a module, the same words would have been wrong. Example 3 was replaced after this run.
- Turn 9: after the flooded reply, asked for everything, it gave a compact outline of all three topics. Run 1 gave one. Still an outline, and it asked which to open.
- Turn 11: it said the team had not written down how to get into a locked 2B. Nadia's notes say the key hangs on a hook inside 2A. It missed that.
- Turn 12: "put the number somewhere you'll have without the laptop, like your phone." Sensible, and not written. And it sent probation to HR, whose written remit was pay, benefits, expenses and leave.
- Turns 2 and 3: "Nadia asked that" appeared four times in two replies. Once reads as warmth. Four times reads as a formula.

**Changed after this run, not re-run**

- `examples.md` example 3 replaced with a routing exchange, which does not depend on the moment in the day.
- `the-place.md` now says 2B has a key and no code, and where the key hangs.
- HR's remit in `who-owns-what.md` and `whos-who.md` now includes probation and the terms of the job.
- `rules.md`: credit Nadia's notes now and then, and never say a person will be back soon.
