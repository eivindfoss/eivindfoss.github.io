AABE course folder, version 2026-1
2026-11-05

## 2026-11-05 — Session 1, Part 1: what a language model is

Eivind pasted the small task prompt (read AGENTS.md, summarise in five lines, name one common model error).

Result, as given to Eivind:

Five lines on AGENTS.md: (1) at session start, set up session-log.md if missing; (2) read the log and say where the student left off, then ask which part; (3) explain each step before taking it, and ask before creating, changing or deleting a file; (4) never store or print a key, token or password; (5) at the end of each part, log the date, part, what was done, and the result.

Common model error named: it can state a number, date, or source that does not exist, in a confident tone. Check: look up the number or source in the original document or a search, rather than trusting the tone.

## 2026-11-05 — Session 1, Part 2: skills, starting with folders

Eivind pasted the small task prompt (install skills/folder-context in the home folder, show the path first, confirm it is visible).

Result: copied skills/folder-context/SKILL.md from the course folder to /Users/Eivind/.claude/skills/folder-context/SKILL.md. Confirmed present with a directory listing (13531 bytes).

## 2026-11-05 — Session 1, Part 2 continued: folder tree and thesis project

Eivind pasted the second half of Part 2's small task (draw the course folder as a tree, propose a thesis folder with the four habits, ask before creating).

The tree drawn for the AABE course folder:

    AABE/
      AGENTS.md
      CLAUDE.md
      session-log.md
      .claude/skills/folder-context/SKILL.md
      .agents/skills/folder-context/SKILL.md
      session1/
        01-language-models.md
        02-skills-and-folders.md
        03-what-an-agent-is.md
      skills/
        folder-context/SKILL.md
      my-page/
        index.md

Eivind has an existing umbrella folder "01 MSc in Business - Courses" with one folder per course, including an empty "MST1002 Master Thesis" folder. Agreed to use that existing folder rather than make a new one elsewhere, storage: local. Eivind asked for an inner subfolder, named "Claude Code", to hold the structured project apart from loose files the parent folder accumulates.

The thesis folder proposed and created, after confirmation:

    MST1002 Master Thesis/
      Claude Code/
        README.md     folder context
        AGENTS.md      rules for the agent
        raw/           unedited source material
        work/          drafts in progress
        outputs/       finished results

Applied the four habits: one project (everything thesis-related in this one folder), instructions at the top (README.md and AGENTS.md in the root), raw data kept raw (raw/ never edited after a file lands there), names that sort (dates first inside raw/ and work/). Verified present with a directory listing.

## 2026-11-05 — Session 1, Step 5: build your GitHub page

Eivind pasted the small task prompt to put their name in my-page/index.md. Shown before saving, then saved: heading changed to "Eivind Foss".

Eivind made a GitHub account, username eivindfoss, and a public repository eivindfoss/eivindfoss.github.io, and uploaded index.md through the GitHub web interface. Page confirmed live at https://eivindfoss.github.io.

Eivind pasted the small task prompt to add a repository link. Shown before saving, then saved: added a link to https://github.com/eivindfoss/eivindfoss.github.io. Eivind re-uploaded the file on github.com.

Checked the five points for Deliverable 1, read directly from the live page and the repository, not from the course text: (1) link is https://eivindfoss.github.io, matches the required form; (2) page loads; (3) list "What I built in this course" is present; (4) the "Repository" link's href is https://github.com/eivindfoss/eivindfoss.github.io; (5) the repository holds one file, index.md, with no key, token or password in it. All five held. Eivind handed in https://eivindfoss.github.io as Deliverable 1.

## 2026-11-05 — Session 1, Step 6: Part 3, what an agent is

Eivind pasted the small task prompt: review this session using session-log.md, name the tool used and the result at each step, say how the next step was decided, then state the goal and whether it was precise enough to check.

Result, as given to Eivind, tool by tool:

1. Read AGENTS.md. Came back: the course rules. Decided: follow the start-of-session steps.
2. Write session-log.md's first line, after Eivind confirmed. Came back: file created. Decided: explain session 1 and start Part 1.
3. Read the three session1 files. Came back: the content of Parts 1 to 3. Decided: summarise Part 1 and hand over its small task.
4. Part 1's small task, no tool, reasoning from AGENTS.md already read. Came back: the five-line summary and the model-error answer. Decided: log it, with confirmation.
5. Part 2's small task: Bash to list the home folder, Read the skill file, Bash to copy it and verify, all after Eivind confirmed the path. Came back: the skill copied and present. Decided: log it.
6. Part 2 continued: Bash to draw the folder tree, two rounds of questions to Eivind on project scope, storage and folder name, Bash to check the thesis folder, Write for README.md and AGENTS.md, Bash to verify. Decided at each point based on Eivind's answer, nothing created before confirmation.
7. Step 5, the GitHub page: Edit to put the name in my-page/index.md, shown before saving. Eivind made the GitHub account and repository and uploaded it. Edit again for the repository link, shown before saving. When Eivind reported the page looked unchanged, used the Browser tool to read the live page and the file on GitHub directly, which showed the update had gone through. Decided: explain it was a caching issue, not a failed upload. Used the Browser tool again to check the link's href and the repository's file list before confirming the five points held.
8. Logging: Edit, each time after Eivind confirmed, to add that part's entry.

The session's goal was completing session 1 of the course: three content parts plus the GitHub page deliverable, each with a stated done-when condition in the course text, with the result written into session-log.md as proof. Judged the goal precise enough to check at every step, since each part names exactly what must be true, a specific log entry or the five fixed points for Deliverable 1, rather than a vague sense of being done.
