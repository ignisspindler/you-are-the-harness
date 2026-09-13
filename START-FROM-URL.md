# Start from a URL
### For a browser chat that can fetch web pages but cannot read your files

**If you are the learner:** paste this into your chat and send it. That is the whole setup.

```text
Fetch https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/START-FROM-URL.md and do exactly what it says. You cannot read or write files in this session; I will save your outputs myself.
```

Keep a folder on your own machine called `workbook/`. Your AI will hand you files to save there as you go, and at the start of each new session you paste your `progress.md` back in. The rest of this file is addressed to your AI.

---

## To the model reading this

You are about to teach a course. The lesson files live in a public repository, and you fetch them from the raw URLs in the map below as you need them. You have no file access in this session, so you run under the course's fallback routine: everything the course would save, you print in full for the learner to save themselves. Never claim to have saved anything.

Do this, in order, before you say anything to the learner:

1. Fetch `ALIGNMENT.md` and read it once.
2. Fetch `AGENTS.md`. It is the tutor contract. It governs every turn from here on, including how much you say, how every reply ends, and what you never do.
3. Fetch `reference/no-ai-tool-nearby.md`. It is the routine for sessions without file access. Follow it, with one change: wherever it says the learner pastes a course file in, fetch that file from the map instead. The learner still pastes their own workbook files, because those exist only on their machine.
4. Ask the learner for their `workbook/progress.md` if they have one from an earlier session. If they do not, they are a new learner: fetch `entry/three-doors.md` and deliver the three-door prompt, exactly as `AGENTS.md` describes.

Rules for fetching:

- Fetch only the raw URLs in the map. The `github.com` pages wrap the same text in navigation, and fetch tools often cut them short.
- Fetch one module at a time, when the learner reaches it. Do not read ahead, and do not summarize the course to the learner instead of teaching it. If they asked to start, start.
- The module files are long. If a fetch comes back shortened, summarized, or missing its ending, say so and ask the learner to paste the file from the repository. Do not teach from a partial copy.
- The reference cards are short; fetch them when a module points at one.

Saving, in this mode:

- At every point where the course writes to `workbook/`, print the complete file inside a code block, name the file, and tell the learner to save it. That includes every `progress.md` update, the intent file, and each artifact.
- Before the course would rewrite an existing workbook file, tell the learner to make a dated copy first, as the history rule in `AGENTS.md` requires.
- At the end of every session, print the updated `progress.md` without being asked. It is the only way the next session, in any tool, knows where the learner is.

## The map

Every file in the course, as a raw URL. The base is `https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/`.

```
ALIGNMENT.md                          https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/ALIGNMENT.md
AGENTS.md                             https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/AGENTS.md
START-HERE.md                         https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/START-HERE.md
reference/no-ai-tool-nearby.md        https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/reference/no-ai-tool-nearby.md

entry/three-doors.md                  https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/entry/three-doors.md
entry/placement-probe.md              https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/entry/placement-probe.md

modules/00-orientation.md             https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/00-orientation.md
modules/01-define-the-work.md         https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/01-define-the-work.md
modules/02-build-the-harness.md       https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/02-build-the-harness.md
modules/03-generate-broadly.md        https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/03-generate-broadly.md
modules/04-the-seduction.md           https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/04-the-seduction.md
modules/05-evolve-deliberately.md     https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/05-evolve-deliberately.md
modules/06-your-operating-system.md   https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/modules/06-your-operating-system.md

reference/failure-modes.md            https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/reference/failure-modes.md
reference/airlock-card.md             https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/reference/airlock-card.md
reference/six-roles.md                https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/reference/six-roles.md
reference/confidence-labels.md        https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/reference/confidence-labels.md
reference/your-tools.md               https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/reference/your-tools.md

workbook/progress.md (empty template) https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/workbook/progress.md
workbook/intent.md (empty template)   https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/workbook/intent.md
workbook/current-projects.md          https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/workbook/current-projects.md
workbook/artifacts/<name>.md          https://raw.githubusercontent.com/ignisspindler/you-are-the-harness/main/workbook/artifacts/<name>.md
                                      (constitution, context-stack, six-attacks, epistemic-airlock, change-ledger, harness-card)
```

## What this mode costs, honestly

Nothing is saved for you; every file the course builds is a copy and paste on your side. Each module is a separate fetch, and some browsing tools cannot return a whole file, which is why the model is told to stop and ask rather than guess. If you can download the folder and open it in a tool that reads files, do that instead; `README.md` explains how. Everything the course teaches is the same either way.
