# No AI tool nearby
*How to take this course in a browser chat that cannot read your files.*

The course is designed for a tool that can open this folder. If all you have is a chat window, it still works. You become the file system. Here is the routine.

## Starting a session

Open a new chat and paste, in this order:

1. The whole of `AGENTS.md`, then this file, so the tutor has the routine in front of it. Then add one line of your own: **"You cannot read or write files in this session. I will paste files in and save your outputs myself."** That line switches the tutor into fallback mode.
2. Your `workbook/progress.md`, as it currently stands. On your very first session it is the empty template.
3. Your `workbook/intent.md`, once it has content.
4. Any file in `workbook/artifacts/` that has content. Later modules read the earlier artifacts, and the tutor cannot open them for itself.
5. The file for where you are: `entry/three-doors.md` for your first session, or the module file named in your progress file.

Then say: **"Start the course"** or **"Continue the course."**

## During a session

When the tutor would normally save something, it will instead give you the full text and say so. Copy it into the right file in your `workbook/` folder on your own machine. The tutor will tell you which file.

When it would normally copy a file to `workbook/history/` before changing it, do that yourself: duplicate the file and add the date and time to the copy's name.

When the tutor names a file it needs and does not have (the placement probe, the next module, a card in `reference/`, your current-projects file), paste it in. The modules point to the reference cards rather than repeating them, so this will happen a few times per module.

## Ending a session

Ask: **"Give me my updated progress.md."** Save what comes back over your `workbook/progress.md`. That file is how the next session, in any tool, knows where you are.

## What you lose, honestly

Two things. First, friction: every save is a copy and paste. Second, the tutor cannot read your source material unless you paste it, so Layer 2 of your Context Stack is only as complete as what you bring. Neither changes what the course teaches.

## What you keep

Everything else. The three doors, the modules, the artifacts, the intent file that travels. When you finish, your intent file goes into your own projects exactly as it would for anyone else, and if you later move to a tool that reads files, your `workbook/` folder is already in the shape it expects.
