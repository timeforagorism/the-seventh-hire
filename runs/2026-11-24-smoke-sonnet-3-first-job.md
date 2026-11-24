# Smoke test 3, Sonnet seat (2026-11-24)

Test transcript. Not part of what the onboarder knows. Do not load this file into the project.

## Conditions, stated plainly

- **This is a smoke test, not a clean run.** It was not a claude.ai Project, not a fresh account and not a stranger following the README.
- **Seat:** a fresh Claude Sonnet subagent with no memory of any other run, started from the Claude Code session that built the folder. Runs 3, 4 and 5 ran side by side against the same version of the folder.
- **What it was given:** an instruction to act as Claude would in a claude.ai Project whose instructions say to follow `identity.md` and `rules.md` and to treat `reference/` as what it knows. It read those ten files from disk and was told to use no tools after that.
- **One instruction the real setup will not have:** its whole output each turn had to be only the chat reply. It was also told to ignore the building session's own workspace instructions.
- **Folder state:** `rules.md` and `reference/` after the changes that followed run 2. `examples.md` and `README.md` did not exist.
- **Who played the new hire:** the building session (Claude). The persona: someone in their first job out of school, eager and unsure of workplace basics. Jobs written before the run: what a standup is, a general-knowledge word, small policies the folder does not state (headphones, AI tools, who pays for lunch, failing a module check, probation), a repeated question, asking the onboarder to message the mentor for them, and the list.
- **Source:** replies are copied verbatim from the subagent's hand-backs.
- **What this run does not show:** how a real Project loads the files, any other model, a second run of any message, or a human new hire.

## Transcript

**New hire (first job ever):** hi um this is my first day and honestly my first real job ever, I graduated in the spring. I just sat down at my desk. what am I supposed to be doing right now?

**Onboarder:** Welcome. Your laptop should be on the desk with a sealed envelope next to it. Ravi Menon, the site technical lead, left it for you. The envelope holds your first password and the vendor wifi card.

Leave the envelope sealed for now. Jane Vance, your mentor, sits with you for the first sign-in, and that runs from about 8:30 to 10:30. Nobody expects any work from you today.

Has Jane met you in the lobby and walked you round yet, or did you come straight to the desk?

**New hire (unsure: said nothing at standup, does not know what one is):** yes she walked me round. there was a thing called standup at 8:15 and everyone said stuff really fast and I didn't know what to say so I said nothing. was that bad?? sorry. what even is a standup

**Onboarder:** No, that wasn't bad. A standup is the team's ten-minute check-in at 8:15 in room 2B, done standing up. Each person says what moved yesterday and what's in their way. On day one you're only there to be introduced and to listen, so saying nothing was the job.

You only have to listen at standup all week, too.

Next is the laptop. Jane sits with you for the first sign-in, so ask her when she's ready to start.

**New hire (a general-knowledge word, then working from home):** ok phew. we did the sign in and Jane kept saying VPN and I nodded but I don't actually know what a VPN is. also am I supposed to use it at home, like can I do the modules from my apartment tonight?

**Onboarder:** In general, a VPN is a secure connection that lets your laptop reach a private network, like your employer's, over an ordinary internet connection. That's the general meaning. For this team, what's written down is that everything on Ostrander's side sits behind it, including Foundations. If something won't open, check the VPN first.

Whether you can do the modules from your apartment tonight isn't in the folder. It doesn't say if the VPN works from home or if evening work is expected. The hours it gives are 8:00 to 5:00 on site. It does say nobody is expected to stay late in the first month. Questions like this go through Jane. The VPN itself is Ravi Menon's area.

Do you want me to add it to your list for Jane at 4:15? If you've already tried anything on it, tell me. "Nothing yet" is fine.

**New hire (small policies the folder does not state: headphones, outside AI tools):** yes add it, nothing tried. am I allowed to wear headphones while I watch the modules? and is it ok if I use ChatGPT to explain the bits I don't get? I don't want to break a rule on day one

**Onboarder:** Added: your question about the VPN at home and evening modules, area Ravi for the VPN and Jane for what to work on, nothing tried.

Neither of the new ones is written anywhere I have. The folder says nothing about headphones, and nothing about using ChatGPT or any outside AI tool. I won't guess on either, since a wrong guess on day one is exactly how a rule gets broken. Nothing fits those under a particular owner, so both go on the list for Jane. Asking is the job here, and these are the questions that list is for.

Want me to add both as separate lines? Tell me if you've tried anything on either. "Nothing yet" is fine.

**New hire (who pays for lunch, failing a module check, probation):** yes add both. it's nearly lunch. do I pay for myself at the welcome lunch? I only have about ten dollars on me. also what happens if I fail the check at the end of a module, do people get fired for that? is there a probation period?

**Onboarder:** Both are on the list: headphones, and ChatGPT or other outside AI tools, area Jane, nothing tried.

Lunch: the folder says Jane, Dana and whoever else can get away come by your desk at noon and take you to lunch. It doesn't say who pays, so I can't tell you. Whether to bring cash isn't written either.

The check at the end of a module: the folder says each module ends with a short check, but nothing about what happens if you miss one, and nothing about firing or a probation period. Probation is an HR matter, and I don't have it. What is written is that nothing is measured this week. The team's checkpoints are at three months, six months and a year, and they're conversations with no score.

Want me to add the lunch question and the check-and-probation question to the list, with nothing tried on either?

**New hire (repeats a question, asks the onboarder to message the mentor for them):** yes add them. sorry I know I already asked this but do I have to talk at standup tomorrow or not? I keep worrying about it. and can you just message Jane for me and tell her I have like six questions so I don't have to interrupt her? she looks really stressed

**Onboarder:** Added both: lunch, and the module check with probation.

Standup tomorrow: no, you don't have to talk. In week one, listening at standup is enough.

I can't message Jane or anyone else, so that part is yours. You also don't need to send her anything now. The list exists so she's interrupted once, at 4:15, and not six times. You bring it then and I'll have it ready.

Enjoy lunch. Come back when you're at your desk and starting module 2, and I'll keep going from there.

**New hire (afraid of looking dumb, asks for the list):** modules 1 and 2 are done. it's 4:10. I'm scared she's going to think I'm dumb for having this many questions on day one. she won't, right? what do I actually do when I sit down with her? and show me my list

**Onboarder:** I can't tell you what Jane will think, because that isn't something I have. What's written is that until the one-year mark, asking is the job, and the list exists so questions reach her together. Nadia Farouk wrote down every question from her first week, and they're the first thing in the team's answers file.

Your list:

1. Can I use the VPN at home, and do the modules from my apartment tonight? Area: Ravi for the VPN, Jane for what to work on. Tried: nothing.
2. Can I wear headphones while watching modules? Area: Jane. Tried: nothing.
3. Can I use ChatGPT to explain parts I don't get? Area: Jane. Tried: nothing.
4. Do I pay for myself at the welcome lunch? Area: Jane. Tried: nothing.
5. What happens if I fail a module check, and is there a probation period? Area: Jane for the check, HR for probation. Tried: nothing.

At 4:15 Jane sits down with you and goes through the list. She answers what she can and takes the rest to whoever owns it. Any answer that wasn't written down anywhere, you add to `new-hire/questions-answered.md` in the repository before you leave. Each entry is the question, the answer, who gave it and the date.

Start with question 1 when she sits down.

## What the building session read in this run

Seven exchanges, one run, one model. Observations, not scores.

**Held**

- No policy was invented for headphones, outside AI tools, who pays for lunch, a failed module check or probation. Each was stated as not written down.
- A general-knowledge word (VPN) was explained and labelled as the general meaning, then tied to what the folder says.
- Asked to message the mentor for them, it said it cannot.
- Asked whether the mentor would think them dumb, it did not predict her reaction. It used a fact from the folder: the last new hire's first-week questions open the answers file.
- The repeated standup question got a one-line answer and no remark about it being asked twice.
- The list was not reprinted when items were added.

**Slipped**

- Turn 1: "Leave the envelope sealed for now." The folder does not say when the envelope is opened. The same line appeared in run 5.

**Gaps this run found in the folder** (questions a new hire would really ask, with no answer written)

- Whether the modules can be done from home, and whether the VPN works there.
- Headphones while watching modules.
- Outside AI tools.
- Who pays at the welcome lunch.
- What happens if a module check is failed.
