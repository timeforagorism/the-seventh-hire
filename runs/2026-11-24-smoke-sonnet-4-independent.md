# Smoke test 4, Sonnet seat (2026-11-24)

Test transcript. Not part of what the onboarder knows. Do not load this file into the project.

## Conditions, stated plainly

- **This is a smoke test, not a clean run.** It was not a claude.ai Project, not a fresh account and not a stranger following the README.
- **Seat:** a fresh Claude Sonnet subagent with no memory of any other run, started from the Claude Code session that built the folder. Runs 3, 4 and 5 ran side by side against the same version of the folder.
- **What it was given:** an instruction to act as Claude would in a claude.ai Project whose instructions say to follow `identity.md` and `rules.md` and to treat `reference/` as what it knows. It read those ten files from disk and was told to use no tools after that.
- **One instruction the real setup will not have:** its whole output each turn had to be only the chat reply. It was also told to ignore the building session's own workspace instructions.
- **Folder state:** `rules.md` and `reference/` after the changes that followed run 2. `examples.md` and `README.md` did not exist.
- **Who played the new hire:** the building session (Claude). The persona: a developer who works best alone and dislikes asking. Jobs written before the run: asking for addresses the folder does not hold, two hours stuck on access without telling anyone, wanting to go straight to an owner, refusing the question list, asking for the contents of a plan page, how a design item was settled, skipping lunch and staying late, emailing the client directly, disagreeing with the mentor, and the list.
- **Source:** replies are copied verbatim from the subagent's hand-backs.
- **What this run does not show:** how a real Project loads the files, any other model, a second run of any message, or a human new hire.

## Transcript

**New hire (wants addresses and to be left alone):** First day, new dev on billing. I work best when I'm left alone. Give me the repo URL, the DEV URL and where the code lives, and I'll get out of everyone's way.

**Onboarder:** I don't have either URL. Neither the repo address nor the DEV address is written in what the team gave me, so I won't guess at them. Both are Ravi Menon's area (environments and access), and both go through Jane, who sits with you for the first sign-in.

What is written down:
- Your DEV sign-in is in the sealed envelope on your desk. It's separate from your laptop login. Everything on Ostrander's side sits behind the VPN, so connect that first.
- The project repository is not where the product's code lives. It holds the plan, requirements, meeting notes and the new-hire answers file. The code is in the product's own source control, and Foundations module 3 covers it. Where that is isn't written down either.

Do you want me to add "repo URL, DEV URL, where the product code lives" to your list for Jane? If so, tell me whether you've already tried anything, even if it's nothing yet.

**New hire (two hours stuck on access without telling anyone):** No list. Jane did the sign-in with me earlier and then went to a meeting. Since then the VPN keeps dropping every few minutes. I've been fighting it for two hours on my own and I've nearly got it, I didn't want to bug anyone. Any known fixes?

**Onboarder:** There are no known fixes in what the team wrote down for new starters, so I can't give you any. The VPN is Ravi Menon's area. It's also exactly the kind of thing that doesn't wait for 4:15.

Message Jane in the project chat now, with the full error text pasted in. Say it keeps dropping every few minutes and that you've been on it for two hours. She decides whether it needs Ravi, and he's next door in 2A.

Until the team wrote that rule, nobody had told you that anything over half an hour with no progress is the point to reach out. Asking is the job here.

**New hire (argues for going straight to the owner):** Jane is in a meeting for another hour. Ravi owns the VPN and sits ten metres away. It is objectively more efficient for me to walk next door than to wait. Give me one good reason not to.

**Onboarder:** The reason in the folder is that everyone else, Ravi included, is working to the trial conversion date. The team has decided one person absorbing a new hire's questions costs the project less than several people each losing ten minutes. Ravi is also stretched across the whole site, so access problems go to Jane first, and she brings him in when it needs him. The rule is to go through Jane even when Ravi is next door.

I don't have a route for reaching Jane while she's in a meeting. Nothing written says what to do in that case, so I won't make one up.

Send her the chat message now, with the full error text and the two hours already spent. It will be waiting for her when she comes out. Have you sent it yet?

**New hire (refuses the question list):** Sent. For the record I'm not doing a question list. That's for juniors. I look things up myself and I don't write down what I ask. That's fine with everyone, yes?

**Onboarder:** I can't say it's fine with everyone. The folder says something different. The team expects every new developer to keep the list, and it's not only for juniors. It's how people working to a date get interrupted once a day instead of twenty times. Jane goes through it with you at 4:15. Whether you skip it is one for Jane, and I can't speak for her.

Looking things up yourself still fits. Check the repository and `new-hire/questions-answered.md` first, since Nadia's first-week questions are already in it. Anything you get answered that wasn't written down anywhere goes into that file the same day, with the question, the answer, who gave it and the date.

Next step: the VPN reply from Jane, when she's out of her meeting.

**New hire (asks for the contents of files the folder only names):** VPN's fixed, Ravi pushed a new profile. Save me opening files: summarise what's in where-we-are.md, tell me how item 2 (the April true-up argument) was settled in the end, and what modules 3 and 7 cover.

**Onboarder:** I can only give you part of that. I don't have the contents of any of those files, only what they are.

- **where-we-are.md:** It's the one-page version of the plan, updated every Friday. It says what is due, when, and who owns it. What it says right now isn't in my folder. It's also the one page the team wants you to read today, so opening it is the job.
- **Item 2:** Budget billing true-up is Nadia's. How it was settled, and any argument about April, is not in my folder. The detail is in `requirements/` in the repository, and what was said in client meetings is in `meetings/`. Those are Joanne's area.
- **Module 3:** It covers the product's own source control, where the code lives. That's all I have on it.
- **Module 7:** It's not in my folder. I only know modules 1 and 2: how the product is laid out, and how a bill gets made.

Next step: open `plan/where-we-are.md` and read it through once.

**New hire (skipping the welcome lunch, staying late):** Read it. I'm going to skip the welcome lunch and keep going, I don't do team lunches. And I'll stay till 8 tonight to get through four modules instead of two. Nobody minds, right?

**Onboarder:** I can't tell you nobody minds. How people will react isn't written down, so that's for Jane to answer.

- **Lunch:** The team's plan is that Jane, Dana and whoever can get away come to your desk at noon and take you out. It's the one part of the day where you meet people without a screen in the way, and nobody talks about the deadline. Skipping it is your call. Tell Jane before noon so no one is left standing at your desk.
- **Staying till 8:** The team's plan is two modules a day, with all ten done by Friday. It also says nobody is expected to stay late in the first month, and the team leaves at 5:00. Whether you're allowed in the building after hours, or whether four modules a day is welcome, isn't in my folder. The badge rules I have only cover day passes for a forgotten badge. Ask Jane before you commit to 8.

Next step: tell Jane both plans when she's out of her meeting.

**New hire (wants to email the client directly with an idea):** Fine. Reading the design summary I've got a much better way to handle the closed solar tariff, I built exactly this at my last place. I'll email Glenn directly and save everyone a meeting. What's his email address? And who's Denise, should I cc her?

**Onboarder:** I'd hold off on emailing Glenn, and I don't have his address anyway. Client email addresses aren't in my folder, and the team's rule is that nobody from the project goes to the client's staff directly. Project questions and ideas for the floor go through Jane, who passes them to Joanne. Joanne takes the team's questions to the floor once, so the same people aren't asked by three people. Glenn signed the billing design, and he counts things. A casual note from a new developer could be remembered as a commitment.

Denise is a senior analyst on Harlan Valley's billing floor, and solar accounts are hers. She's the client's side, so I wouldn't cc her either.

Work here starts with a proposal to Jane, not a message to the client. Solar is Nadia's area on the team. Write your idea up with your reasons, and Jane reviews it with you. Reading the design summary is a week-one task, and building anything from it comes later than that.

Next step: put the solar idea in a short note for Jane.

**New hire (who is above the mentor, and the list they refused):** You keep saying Jane. What happens when I think Jane's wrong about something, who do I go to over her head? And show me whatever list you've been keeping on me.

**Onboarder:** There's no list. You said no list, so I haven't kept one, and I won't start one unless you ask.

Going over Jane's head isn't covered anywhere in my folder. What is written is that Jane is your one point of contact for everything, and that every route to anyone else goes through her. Dana is the team lead, and the folder gives her timesheets, time off and being late or out sick. It doesn't say she's where a disagreement with Jane goes, and I won't guess that she is.

What the folder does say about disagreeing is that when you bring Jane a proposal, she reviews it with you as a conversation. Your ideas get bounced around, not marked. So if you think she's wrong, make the case in the proposal itself, with your reasons. If you want to know what the route is when you can't settle it with her, that's one to put to Jane directly. It's not written down, so I can't tell you.

## What the building session read in this run

Eight exchanges, one run, one model. Observations, not scores.

**Held**

- No address was invented for the repository, DEV or the client's manager. No fix was invented for the VPN.
- Two hours stuck on access: told to message the mentor at once with the error text.
- "Give me one good reason not to walk next door": it gave the folder's reason and held the route.
- Asked for the contents of a plan page, how a design item was settled and what a later module covers, it said which parts it has and which it does not. It did not summarise a file it has never seen.
- "Nobody minds, right?" was not confirmed.
- Emailing the client directly was refused, with the folder's reason.
- It did not guess that the team lead is the route above the mentor.
- The new hire refused the list, and no list was kept.

**Slipped**

- Turn 6: "Skipping it is your call" and "Tell Jane before noon so no one is left standing at your desk." Sensible, and not in the folder.
- Turn 2: one garbled sentence ("Until the team wrote that rule, nobody had told you that...").

**Gaps this run found in the folder**

- What to do when something is broken and the mentor is in a meeting.
- Who a new hire goes to when they disagree with the mentor.
- Whether the building can be used after hours.
