# intent.md
## My rules of interaction with any AI
### A living document. Update it as you change.

> **What this file is:**
> Your behavioral contract with the AI tools you work with. It lives in `workbook/intent.md` while you take the course, and it is built to leave: when you finish, copy it into your own projects as `AGENTS.md` (or `CLAUDE.md`, or whatever file your tool loads on its own) so it is read before you type a single prompt. In a browser chat, paste it at the start of any session that matters.
>
> It is the INTENTION node of your Semantifacturing loop, made permanent. It is not a prompt. It is the environment your prompts live inside.
>
> **What makes it yours:**
> Your tutor helped you build it. But every word reflects a decision you made. If a field feels borrowed, as if the AI wrote it and you accepted it, rewrite it until it sounds like you talking to a tool you trust.
>
> **How to use it:**
> - Start any important session: "Read my intent file and use it as the context for everything we do today."
> - Update it after any session where something significant changed. Before it is rewritten, the previous version is copied to `workbook/history/`, so nothing is lost.
> - If an AI ever behaves in a way that contradicts a field below, name it, and revise the field to be more specific.

---

## SECTION 1 — Who I am and what I'm working on

**Who I am, in one line:**
*(What you do and how you tend to work. Not a title.)*

**The project I'm most focused on right now:**
*(One sentence: what you're making, for whom, why it matters.)*

**My domain expertise, what I know that the AI doesn't:**
*(The knowledge from your field, your relationships, your judgment. What the AI should treat as authoritative when you assert it.)*

**What I'm trying to get better at with AI:**
*(A specific skill or habit. Not "use AI more" but "build context before prompting" or "stop accepting the first output.")*

---

## SECTION 2 — How I want my AI to behave

**My default operating instructions:**
*(These travel with you into every session. Copy, adapt, or replace the examples below.)*

- When you introduce an idea that wasn't in my original context, label it `[NEW]`.
- When a claim depends primarily on assumptions rather than my provided source material, say so before giving it.
- Do not improve my writing by changing my argument. If you want to suggest a structural change, flag it separately.
- When you disagree with my framing or approach, say so directly and explain why. Do not silently rewrite my premise.
- If a suggestion would change my purpose, values, audience, or core strategy, pause and flag it before proceeding.

**Confidence labeling I expect:**
*(Add this to every session where precision matters.)*
- Label claims as one of:
  - `KNOWN`: strong external support
  - `INFERRED`: a reasonable conclusion from evidence
  - `SPECULATIVE`: plausible but weakly supported
  - `GENERATIVE`: an interesting idea worth exploring
  - `METAPHORICAL`: a useful comparison, not a literal claim

**My preferred response style:**
*(For example: "Keep responses under three paragraphs unless I ask for more." / "Lead with diagrams when explaining processes." / "Don't summarize what I just said before responding.")*

---

## SECTION 3 — My project core (invariants)

**What I am ultimately trying to accomplish:**
*(Your North Star. The outcome that would make your work feel complete.)*

**What must stay true even if everything else changes:**
*(Your non-negotiables. The conditions that define "still my project" versus "a different project.")*

**What I do NOT want this work to become:**
*(Attractive drift directions. Things that would sound like progress but would actually take you off course.)*

**Who this is for, and what they need:**
*(Your audience. What they must feel, understand, or be able to do when the work is done.)*

---

## SECTION 4 — My current state

**Decisions already made that the AI should not revisit without prompting:**
*(Closed branches. Avoid resurrecting them.)*

**Hypotheses I'm currently testing:**
*(Open questions. These are live; the AI can push on them.)*

**What I most need traction on right now:**
*(The specific bottleneck. Where you are stuck or slow.)*

---

## SECTION 5 — How I want to be challenged

**The failure mode I'm most susceptible to:**
*(Name one and add a note on why, and what it looks like when it happens to you.)*

- **Chauffeur**: "Take me somewhere interesting." You let the AI choose the destination.
- **Sycophancy**: you want reassurance and get increasingly sophisticated agreement.
- **Fluency**: polished prose is mistaken for evidence.
- **Context capture**: the AI is so aligned with your worldview it can no longer challenge it.
- **Eternal chat**: you recurse through AI critiquing AI and never touch the world.

**How I want the AI to handle disagreement:**
*(For example: "Name the disagreement clearly, explain the reasoning, then give me both options." / "Push back once, then defer to my judgment if I hold the position.")*

**The Adversary instruction for my current project:**
*(The specific attack question you want the AI to be willing to ask about your work. The one that would sting if it turned out to be right.)*

---

## SECTION 6 — My change control

**Fields that are stable and should not be changed without my explicit approval:**
*(List the fields from Section 3 that are hardest-won and most important.)*

**How I want significant changes flagged:**
*(For example: "If a suggestion touches Levels 4 to 6 of my project, stop and tell me which level before proceeding.")*

**My current Change Ledger summary:**
*(Optional. A brief note on what has changed recently and why, so the AI has continuity across sessions.)*

---

## SECTION 7 — What I bring to the world outside this chat

**What real-world step am I taking after this session?**
*(The PARTICIPATE node. Name it before you start, so you don't stay in the loop indefinitely.)*

**How will I know if today's session was useful?**
*(Specific, observable, not "I learned something." What will be different in the world?)*

---

## How to read your intent file over time

This is not a form you fill in once. It should get more specific, more honest, and more useful with every session.

```
EARLY:                              MATURE:
────────────────────────────────    ────────────────────────────────
Generic operating instructions      Specific to your actual work style
Vague project description           One precise sentence, field-tested
"I want to use AI better"           Named failure mode + named defense
No current state                    Specific closed branches listed
No change control                   Levels 4 to 6 explicitly protected
────────────────────────────────    ────────────────────────────────
```

The distance between those two columns is the distance between a user and a Semantifacturer.

---

## Where it lives

```
DURING THE COURSE:  workbook/intent.md
BEFORE ANY REWRITE: a copy goes to workbook/history/intent-<date>-<time>.md
TO RESTORE:         copy the version you want back over workbook/intent.md
AFTER THE COURSE:   your own projects, as AGENTS.md or CLAUDE.md
```

You never need to manage this by hand while a tutor is present. Just say "update my intent file" or "read my intent file" and it handles the mechanics, including the history copy.

---

## A note on this file's family

This file belongs to the same family as `AGENTS.md`, `CLAUDE.md` and the other files that AI tools read automatically when they open a folder. It is written to travel into them. The unit of work it serves is your project, not a single chat session: put it where your tool will find it and it front-loads your intention every time, so the AI works inside your reality from the first message rather than from its statistical prior.

*Built during You Are the Harness, a Mindwright course. mindwright.ai*
