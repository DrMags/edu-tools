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

The skill is built for Claude. It relies on scripts that Claude runs while building a package, so it is not designed for other AI tools.

## Questions and problems

Problems with a tool can be reported through this repository's Issues tab (a free GitHub account is required).

## License

Shared under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You may use, adapt, and share these materials, including adapted versions, as long as credit is given.

---

AI-assisted. Reviewed and revised by me.
