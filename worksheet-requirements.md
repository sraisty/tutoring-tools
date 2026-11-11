# Weekly tutoring worksheet requirements

Status: approved requirements, ready for skill setup. Do not generate worksheets
until the user requests a worksheet run.

## Location and weekly interview

- Tools folder: `/Users/sueraisty/Projects/tutoring-tools`.
- Student materials folder: iCloud Drive / iCloudProjects / Tutoring.
- On this Mac, that folder is under `~/Library/Mobile Documents`, at
  `com~apple~CloudDocs/iCloudProjects/Tutoring`.
- Resolve student paths below relative to the iCloud Tutoring folder. Keep
  student files and personalized worksheet sources outside the tools folder.
- Discover student folders within `students`.
- Ask about one student at a time. Allow students to be skipped.
- Ask for the session date, topics, and quantities for that student.
- Ask about the desired difficulty level.
- Accept a list of topics with practice page counts or problem counts.
- For a page count, choose a problem count that allows suitable work space.
- For a problem count, use enough practice pages for suitable work space.
- If page and problem counts conflict, ask which takes priority.
- Use grade-level requests to guide difficulty, never as handout labels.

## Files

- Create one PDF per topic in `students/<STUDENT NAME>/worksheets`.
- Example filename: `2026-11-18_Maya_Graphing-Linear-Equations.pdf`.
- Use the session date in the filename and document.
- Keep the practice, answer key, and Topic Instructions in the same PDF.
- Requested page counts include practice pages only.
- Keep editable sources in a separate supporting folder, apart from printable
  worksheets, so questions and layouts can be revised without rebuilding them.
- Preserve earlier handouts and editable sources when making revisions.
- Save revised PDFs with version suffixes such as `_v2`; do not silently
  overwrite previous versions.

## Page layout

- Design for single-sided printing. Do not add blank separator pages.
- Include student name, session date, and topic in every page header.
- Include page numbers on every page.
- Leave blank, unruled work space below each problem. Size the space for the
  problem type so the student can choose how to lay out their work.
- Give geometry proofs substantially more space than short calculations.
- Keep each question, its diagram, and its work space together on one page.
- Ensure all text, diagrams, and grids are readable in black-and-white printing.
- Whenever graphing is required, provide an x-y grid with a suitable scale and
  enough room for the student's graph.

## PDF section order

1. Practice pages.
2. Answer Key, beginning on a new page and using as many pages as needed.
3. Topic Instructions, beginning on a new page at the end of the PDF.

## Topic Instructions

- Use the heading "Topic Instructions", not "Cheat Sheet".
- Explain how to solve the types of problems in the handout.
- Prefer concise explanations and a legible one-page layout.
- Use multiple columns and modestly smaller graphs when helpful.
- Exceed one page only when a legible one-page explanation is not feasible.

## Problem wording and personalization

- In word problems involving a child, use the student's name.
- When another person is needed, invent a different child's name.
- Never display grade level anywhere in the handout, including the answer key
  and Topic Instructions.
- Use descriptive topic titles without labels suggesting the student is behind.
- Do not infer a student's printable name from a folder label that also contains
  grade information; confirm the name when needed.
- Progress from easier to harder problems within the requested scope.
- Do not ask about calculators or include calculator language in handouts.
- Include units when relevant, including in the answer key.
- Prefer exact answers unless rounding is part of the skill being practiced or
  is needed for a practical measurement.
- State any rounding requirement explicitly. Do not add rounding instructions to
  problems that do not need them.
- Mark diagrams "Not to scale" only when appropriate.

## Answer keys

- Include essential working, completed graphs for graphing questions, and
  reasoning for proofs.
- For higher-level problems with alternative methods, include a brief sentence
  acknowledging that other valid approaches are possible when appropriate.
- Identify multiple valid answers when applicable.

## Verification

- Double-check all answers before delivering the PDF.
- Check that answer numbering matches the practice problems.
- Check for and eliminate duplicate problems within each handout.
- Inspect the rendered PDF for readable text, suitable work space, usable grids,
  complete headers, page numbers, and section order.
- Do not treat a successful PDF export alone as proof of correctness.

## Setup still to be done

- Package the approved workflow as a reusable skill.
- Configure the project to discover and use the skill.
- Test with one student only after the user authorizes worksheet creation.
- Consider optional Git checkpoints after inspecting existing Git setup.
- Defer scheduling, Notion integration, and subagents for this first task.
