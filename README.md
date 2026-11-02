# edu-tools

Tools for course design, built by and for higher education professionals. Materials here were shared at the session "Practical AI for Course Design: Applied Activities, Quizzes, Study Tools, and Accessibility" at FVTC Instructional Excellence Day, November 4, 2026.

Start at the landing page for downloads and setup steps: https://drmags.github.io/edu-tools/

## QTI Quiz Tool (Claude skill)

The QTI Quiz Tool builds quiz and exam packages that import into Canvas Classic Quizzes and Blackboard Ultra question banks. You supply your own course sources (objectives, readings, notes, existing questions). Claude asks about your goals, drafts the questions for your review, and then packages them. Each build includes:

- an importable .zip package,
- an answer-key review sheet,
- a spec file you can upload later to revise the quiz,
- a short list of things to check after import.

The tool works in any discipline. It supports formula questions with randomized values, accessibility checks on alt text and instructions, and a privacy check that stops a build when a source appears to contain student data.

**Download:** [qti-quiz-tool.zip](https://github.com/DrMags/edu-tools/releases/latest/download/qti-quiz-tool.zip)

**Set up in Claude:**

1. In Claude, turn on code execution and file creation if it is not already on.
2. Go to Customize > Skills (some versions label this Settings > Capabilities).
3. Choose the option to upload a skill, and upload the .zip file without unzipping it.
4. Start a new chat and ask Claude to build a quiz. Have your course sources ready to upload.

Skill availability depends on your Claude plan, and on Enterprise plans an administrator may need to turn skills on. See [Using skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude) for current details.

## QTI Quiz Tool for Microsoft 365 Copilot Chat

A version of the same tool for the Microsoft 365 Copilot Chat that comes with a college Microsoft account. It works with the free (Basic) Copilot Chat; no upgrade is needed. Copilot runs the same builder scripts, so the packages, review sheets, and spec files match the Claude version.

**Download:** [qti-quiz-tool-copilot-chat.zip](https://github.com/DrMags/edu-tools/releases/latest/download/qti-quiz-tool-copilot-chat.zip)

**Use it in Copilot Chat:**

1. Unzip the download and open "1 - READ ME FIRST.txt".
2. In Microsoft 365 Copilot Chat, start a new chat and attach the three files the READ ME names.
3. Paste the starter prompt from "2 - Starter prompt (paste this).txt" and send it.
4. Copilot runs a self-check, then asks about your goals. Repeat these steps at the start of each new chat.

A package built in the free Copilot Chat has been imported into Canvas Classic Quizzes (Common Cartridge route) and confirmed. Copilot Chat uses OpenAI models, so review the questions and the review sheet carefully. Copilot Studio agents cannot run the builder scripts, so use a regular Copilot Chat.

## Questions and problems

Problems with a tool can be reported through this repository's Issues tab (a free GitHub account is required).

## License

Shared under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You may use, adapt, and share these materials, including adapted versions, as long as credit is given.

---

AI-assisted. Reviewed and revised by me.
