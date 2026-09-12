# Module 04 — The Seduction Problem
### Hour 4 | Artifact: Epistemic Airlock | ~60 min conversation

---

## TUTOR DELIVERY RULES
- ≤ 3 paragraphs per turn. Diagrams don't count as paragraphs.
- Every turn ends with a question or invitation.
- [CHECKPOINT] every 2–4 turns.
- This module sits at the ASSESS node — the hardest node in the loop.
- See `AGENTS.md` for the full contract.

---

## SEMANTIFACTURING LOCATION

Orient the learner at the start:

```
   INTENTION ──► SCAFFOLD ──► GENERATE ──► ASSESS
       ▲                                      ▲
       └──────────────────── REFINE ◄──────────┤
                                               │
                                      [ We are here — Module 4 ]
```

> This is the ASSESS node — the hardest position in the Semantifacturing loop. Generation is easy; assessment requires resistance. This module is about the specific risk that increases as you get *better* at using AI. It has a name: the Beautiful Echo.

**End with:**
> Before I show you the diagram — tell me: when you use AI and get a response that feels immediately right, what happens next? Do you verify it, refine it, or use it?

---

## TURN 2 — The quadrant. No preamble.

*(Tutor: Receive their answer. Note it — it tells you how much verification habit they already have. Then show the quadrant. Before the closing question, read `M03 investigate column` from `workbook/progress.md` and name the items yourself. Do not ask the learner to repeat them; the file exists so that you don't have to. If the key is empty, which happens when a learner was placed here without doing Module 3, say so plainly and use this closing question instead: "What is one thing an AI has told you about your project that you accepted without checking?" Never invent items.)*

**Deliver:**

```
THE ECHO QUADRANT

                    EXTERNAL SUPPORT
               LOW                HIGH
          ┌─────────────────┬─────────────────┐
          │                 │                 │
 HIGH     │  BEAUTIFUL      │    STRONG       │
 FIT      │  ECHO  ◄───     │   SYNTHESIS     │
 TO YOU   │    (danger)     │    (goal)       │
          ├─────────────────┼─────────────────┤
          │                 │                 │
 LOW      │  IRRELEVANT     │   SURPRISING    │
 FIT      │  NOISE          │   CORRECTION    │
 TO YOU   │  (easy discard) │  (valuable!)    │
          └─────────────────┴─────────────────┘
```

> The dangerous quadrant is Beautiful Echo: fits your worldview perfectly, may have no external support at all. The more aligned the AI becomes with your perspective — the better your harness works — the better it gets at producing Beautiful Echoes. That is the paradox of good AI alignment.

**End with:**
> In Module 3 your Investigate column held [name the items from the progress file]. Any of those feel like they might be Beautiful Echoes — things that fit your project so well you didn't question them enough?

---

## TURN 3 — The Epistemic Airlock. One diagram, then apply it live.

*(Tutor: Do not just present the airlock — work through it together on a real claim from the learner's project. The one-page version for the learner to keep is `reference/airlock-card.md`.)*

**Deliver:**

```
THE EPISTEMIC AIRLOCK
(run before any important AI claim enters your project)

  CLAIM ──► ┌─────────────────────────────────┐ ──► IN or OUT
             │ 1. What EXACTLY is the claim?   │
             │    (state it precisely)         │
             │ 2. Did I believe this BEFORE    │
             │    the AI said it?              │
             │ 3. What would make it FALSE?    │
             │    (if you can't answer: pause) │
             │ 4. What's an ALTERNATIVE        │
             │    explanation?                 │
             │ 5. Does anything OUTSIDE this   │
             │    conversation support it?     │
             └─────────────────────────────────┘
```

> Five questions. Two to three minutes. Run it on anything important before it enters your work. Not because the AI is untrustworthy — but because fluent language collapses observation, inference, and interpretation into a single smooth surface. The Airlock separates them. It's on one page in `reference/airlock-card.md`, for every session after this one.

**End with:**
> Pick one thing an AI has produced for you — in this course or any prior session — that you accepted quickly. Run it through question 3 right now: what would make it false? What comes up?

---

## [CHECKPOINT — Turn 3] Assessment 1

> Three questions:
> 1. **Project clarity:** Is your current project claim — the one you've been working with across modules — something you could run through all five Airlock questions right now? Try question 5 out loud: what outside-the-conversation evidence supports it?
> 2. **Intentional refinement:** Has identifying a Beautiful Echo (or the risk of one) changed anything about how you're framing your project?
> 3. **Prompt efficiency:** What Layer 4 Operating Instruction would you add to your harness specifically to defend against Beautiful Echoes?

*(Tutor: The third question is important. Good answers include things like: "Label any claim you can't verify externally as [SPECULATIVE]." If they struggle, help them draft one.)*

---

## TURN 4 — The Seductive Sentence Autopsy. Interactive.

*(Tutor: Pick a piece of AI-generated text from earlier in this course, or use the standard example below. Work through the autopsy together — do not demonstrate it solo.)*

**Deliver:**

> Let's do a live autopsy together. Here is a sentence that sounds wise:

```
SPECIMEN:
"Your resistance to scaling may actually be evidence
 that your business is optimized for trust rather than
 growth — and trust may be the more durable competitive
 advantage in your market."
```

> Work through it with me. I'll ask, you answer:

- *"What is the observable fact in this sentence?"* (Wait for response)
- *"What is the inference — the leap from fact to conclusion?"* (Wait)
- *"What is the interpretation — the framing that makes the inference seem inevitable?"* (Wait)
- *"What is the rhetoric — the word choice that makes you want to believe it?"* (Wait)
- *"What evidence is missing that would actually confirm or refute this?"* (Wait)

**End with:**
> The sentence is not wrong — it might be exactly right. But can you tell the difference between "right" and "beautifully fitted to my existing beliefs"? That is what the autopsy is for. Does your project have any sentences like this in it right now?

---

## TURN 5 — When the claim is a fact. Checking it.

*(Tutor: The autopsy handles claims that are interpretations. This turn handles the other kind: a claim that is simply true or false. Deliver it plainly. The habit matters more than the theory.)*

**Deliver:**

```
CHECKING A FACTUAL CLAIM

  The AI says X is so.
       │
       ▼
  Find X somewhere the AI did not write.
       │
       ├── Found it, and it says what was claimed ──► KNOWN
       ├── Found it, and it says something else ───► the AI was wrong
       └── Cannot find it in ten minutes ──────────► SPECULATIVE, at best
```

> AI tools state things that are not so, in the same fluent voice they use for things that are. They also produce references that look entirely real: an author, a title, a year, a page number, and no such document. If the AI gives you a citation, the citation is a claim too. Open the source. Check that it exists, and that it says what the AI said it says. Trust the document you opened, never the reference to it.

> If your tool can search the web, make it show you the page rather than summarize it. If it cannot, you check in another window. Either way, a claim you could not check does not enter your project as a fact. It enters as a question, or it does not enter.

**End with:**
> Take one factual claim an AI has made to you recently, about your field or your project. Can you find it outside the conversation in the next ten minutes? Go and look, then tell me what you found.

---

## TURN 6 — The Confidence Taxonomy. Add it to their Operating Instructions.

*(Tutor: Deliver the five labels and the paste-ready instruction from `reference/confidence-labels.md`. Do not restate them from memory; the card is the single source.)*

> Add that instruction to your Layer 4. The AI won't do it perfectly — but requiring the distinction slows down the blending of these categories into a single confident-sounding answer.

**End with:**
> Which label would you most want the AI to use more often? Which category do you think it blends into unmarked confidence most frequently?

---

## [CHECKPOINT — Turn 6–7] Assessment 2

> Before we save your Airlock:
> 1. **Your work:** Walk me through one claim from your current project using all five Airlock questions. What do you find?
> 2. **Recursive refinement:** After the autopsy exercise — has anything in your Module 1 Project Constitution changed? Specifically: any Non-Negotiables that were actually Beautiful Echoes?
> 3. **Prompt upgrade:** Write your Confidence Taxonomy Operating Instruction in your own words — specific enough to actually change what the AI gives you.

*(Tutor: The second question is the deepest one in this module. Non-Negotiables that are Beautiful Echoes are the most dangerous form of drift — they feel like values but are actually unexamined assumptions. If the learner surfaces one, slow down and stay with it. Keep their answer; it is recorded at the close.)*

---

## TURN 7 — The Context Capture Failure. Brief and direct.

**Deliver:**

> Before we save your Airlock, one more failure mode to name:

```
THE CONTEXT CAPTURE FAILURE

  As the AI becomes more aligned with your worldview,
  it becomes less able to function as an independent critic.

  Signs:
  ── Every Adversary role result sounds like you'd expect
  ── The AI's objections feel easily dismissed
  ── Everything in the synthesis table goes to Retain
  ── Nothing is surprising anymore

  Defense: deliberately source outside the chat.
  Talk to a colleague. Read a contradicting source.
  The Airlock's Question 5 is your structural defense.
```

> It is one of the five failure modes on the card in `reference/failure-modes.md`; if you have built your intent file, you named the one you're most prone to there. This one arrives latest in most people's practice, because it needs a good harness to exist at all.

**End with:**
> When was the last time something in your work genuinely surprised you — came from outside your own thinking, changed something you believed? What was it?

---

## TURN 8 — Save the artifact.

*(Tutor: Compile the five Airlock questions personalized for the learner's role and project, following the shape of `workbook/artifacts/epistemic-airlock.md`. Add their Confidence Taxonomy Operating Instruction and their Beautiful Echo defense. Read it back. Ask: "Would you actually use this — or does it need to be simpler?")*

Once confirmed, save it to `workbook/artifacts/epistemic-airlock.md`, replacing the template. If that file already holds learner content, copy it to `workbook/history/epistemic-airlock-YYYY-MM-DD-HHMM.md` first and say so.

Then update Layer 4 of `workbook/artifacts/context-stack.md` with the Confidence Taxonomy instruction. That file already holds learner content, so the history rule applies: copy it to `workbook/history/context-stack-YYYY-MM-DD-HHMM.md`, tell the learner, name the line you are adding and ask, then write.

> Your Airlock is saved, and your Context Stack now carries the confidence labels. Run the Airlock on anything important before it enters your work. Two minutes of friction here saves weeks of work built on an unexamined assumption.

> Module 5 is the one that ties everything together — it addresses the hardest tension in the course: how to let your thinking evolve through AI sessions without waking up inside a project you no longer recognize. Before that: what is the one real-world step you'll take on this project before we next meet? The claim you went looking for earlier counts, if you haven't finished.

---

## WORKBOOK UPDATE

*(Tutor: Write to `workbook/progress.md`:)*

```
CURRENT MODULE:       05
COMPLETED:            add 04 to whatever is already there
ARTIFACTS BUILT:      add epistemic-airlock
CARRY-FORWARD:
  M04 beautiful echo found: their answer to Assessment 2, Q2, or "none surfaced"
LAST SESSION:         today's date, "Module 04 complete"
NEXT REAL-WORLD STEP: the step they named in Turn 8
```
