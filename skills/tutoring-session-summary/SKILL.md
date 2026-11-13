---
name: tutoring-session-summary
description: Create parent-facing tutoring session summaries from Sue’s lesson notes. Ask the template questions one at a time, then generate a searchable PDF after Sue approves the draft.
---

# Tutoring session summary requirements

## Purpose

Turn Sue’s post-lesson notes into a searchable PDF she can share with a parent
and find again later. Use Tutoring_Session_Summary_v2.pdf as the reference for
the questions and section order.

## Collect the session details

- Sue supplies the student’s name, subject or course, and lesson date. Accept
  “today” and “yesterday” in Pacific time and convert them to the actual date.
  Ask for any missing item. Default the session length to one hour unless Sue
  specifies a different duration.
- Ask one template question at a time, in this order:
  1. What did you cover?
  2. What went well?
  3. What are the areas to keep working on?
  4. What should the student practice before the next session?
  5. What is the planned focus for the next session?
  6. Are there any upcoming tests or assignments?
  7. What preparation do you recommend?
  8. Is there anything else you’d like the parent or student to know? Accept a
     free-form response.
- Allow Sue to skip any question. Omit skipped fields in the parent PDF,
  including the section heading when all its fields are skipped.

## Review and approve

- After collecting all answers, suggest specific edits for repetition or
  clarity. Preserve the facts, observations, and plans Sue supplied. Ask for
  clarification when needed and use only confirmed details.
- Show the full parent-facing summary in chat. Incorporate Sue’s edits and wait
  for her approval of the wording before generating the PDF. Use the approved
  wording in the PDF.

## Generate and save

- Include the student, session date, subject or course, and duration. Use the
  template’s headings for answered sections. Group planned focus, upcoming tests
  or assignments, and recommended preparation under **Next Session**.
- In the chat draft and PDF, use concise bullets for the main sections. Give
  each distinct topic its own bullet under **What We Covered** where possible.
  Write the final **Notes for Parent & Student** as a short paragraph in Sue’s
  voice, using the observations she supplied.
- Generate a text-based PDF so the contents can be selected and searched.
- On every page, include a footer with
  `Tutor: Sue Raisty, sraisty@gmail.com, 650-270-1024` aligned left and
  `After Three Learning LLC` aligned right. Reserve enough space so both sides
  are legible and clear of the body text.
- Save it in the existing session notes folder inside the student’s iCloud Drive
  directory. Use the existing folder name. If the folder can’t be identified or
  written to, provide the generated PDF and report where it still needs to be
  filed.
- Name the file `YYYY-MM-DD Student Name Session Summary.pdf`, using the lesson
  date. Preserve an existing file if the proposed filename is already taken and
  use a numbered suffix for the new file.
- Confirm the filename and where the PDF was saved.

## Sharing and reminder

- Sue shares the PDF with the parent herself.
- Optional. If an existing scheduler and notification channel can do this with
  little setup, remind Sue once, one hour after a successful save, to share the
  summary. Use SMS if readily available, or an existing notification channel.
  The PDF workflow is complete once the file is saved and its location reported.

## Acceptance checks

- A summary for “yesterday” uses yesterday’s Pacific date in the PDF and
  filename. The duration defaults to one hour and accepts an explicit override.
- A skipped question leaves no empty prompt in the PDF. A partially answered
  **Next Session** section shows only answered items.
- The PDF contains the approved wording and its text is searchable. It lands in
  the correct student’s session notes folder, or the workflow reports the save
  issue and returns the PDF.
- If the optional reminder is enabled, a successful save schedules one reminder
  to Sue an hour later. Sue handles delivery to the parent.
