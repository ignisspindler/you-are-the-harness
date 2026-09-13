# Contributing

This file is for anyone editing the curriculum, including its author. If you are here to *take* the course, close this and open `START-HERE.md`.

## For AI tools: author mode

If the person you are working with is editing these files rather than learning from them, you are not the tutor. Do not run the session start protocol, do not open the three doors, do not write to `workbook/`. Work on the files as asked, and keep the rules below.

## Rules that keep the course working

**Tool-agnostic, always.** The course runs in any AI tool. Never name a product or a vendor-specific command in the lessons. Describe capabilities (reading files, searching the web, remembering across sessions) and let the learner map them to whatever they use. `reference/your-tools.md` is the one place that discusses tools, by category.

**The tutor speaks in the first person.** Inside quoted delivery text the tutor says "I". Prose about the learner's own future work says "your AI" or "your AI tool". The tutor never has a name.

**Three paragraphs, then a question.** Every turn in every module ends with a question or an invitation, and never runs past three paragraphs. Diagrams do not count. If you add teaching text, split it into turns.

**One source of truth for each concept list.** The five failure modes, the Airlock questions, the six roles and the confidence labels each live in one card in `reference/`. Modules teach them in dialogue and link to the card; they do not restate the list. Two exceptions, on purpose: `workbook/intent.md` and `workbook/artifacts/harness-card.md` carry their lists in full, because those files are copied out of this repo and a link would go dead.

**The history rule is load-bearing.** Any change to `AGENTS.md` must keep the copy-before-rewrite behavior, the append-versus-rewrite distinction, and the write-once baselines. Learners rely on never losing a version of their work.

**The workbook ships empty.** Templates in `workbook/` describe shape, not content. Never commit a filled-in workbook.

**Plain text diagrams.** ASCII only, as the modules do now.

## Proposing changes

Open an issue describing what a learner would experience differently, then a pull request. Contributions are accepted under the same license as the course, CC BY-NC-SA 4.0.

## A note on the placement probe

The assessment door is the most nuanced of the three, because it requires the tutor to synthesize across multiple probes rather than follow a script. The critical discipline is: **don't reveal the rubric, don't reward AI vocabulary, only reward specificity and self-awareness about real experience.**

A learner who says "I've heard about the Beautiful Echo problem" but can't describe a personal example of confirmation bias in their AI use is not at Module 4. A learner who describes exactly that experience without knowing the term is.

The diagnostic works because Semantifacturing competence is behavioral, not conceptual. It shows in how people talk about their actual work, not in whether they know the course vocabulary.
