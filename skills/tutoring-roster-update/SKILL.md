---
name: tutoring-roster-update
description: Update the tutoring roster document that contains the contact details, regular schedule, rate, and referral source for each active student.
---

# Tutoring roster PDF requirements

## Update workflow

- Read the latest versioned roster PDF and apply the requested additions, removals, and edits. Support changes to names, subjects, locations, recurring sessions, rates, referral sources, and contact details. Identify an existing student unambiguously before changing or removing their row.
- Store or recover each session’s weekday, Pacific start time, and duration or end time. A student can have multiple weekly sessions. Preserve existing durations when changing only a start time. Ask when a required duration or another material input cannot be recovered reliably.
- For new students, look up missing student and parent names, emails, and phone numbers in Google Contacts. Search by the student’s name and by any known parent name. A parent’s record may include the student’s name in parentheses or notes. Verify the relationship before using a match. Leave unverified fields blank.
- For a new in-person student with a missing tutoring address, check the matched contact record and Google Calendar tutoring events. Use an explicitly supplied session location when available. If sources conflict and the session location cannot be established, ask. Mark missing street addresses as pending. Use the venue name for sessions at a named public location and show Remote for online sessions. A known city can appear with either a pending street address or a remote location.
- Sort each student’s sessions Monday through Sunday, then by Pacific start time. Sort student rows by their first session using the same order. Use student name to break ties.
- Use the confirmed roster schedule for the PDF. When asked to audit Google Calendar, check each listed weekly slot for a corresponding recurring series. Report missing series, placeholders, duplicate series, and material schedule differences. Compare the lesson time with both event titles and the reserved blocks when they differ. Calendar checks are read-only.

## PDF layout

- Use US Letter landscape and the current roster as the visual reference. The roster may span multiple pages. Add pages as needed to preserve legibility. Repeat the table header on each page and keep each student’s row together.
- Use the columns Student, Subject, Location, Day & time, Rate, Source, and Parents. Keep one row per student, with one line per session in Day & time. Include end times when recorded. Include the hourly rate and identify the currency when needed.
- In both Student and Parents, put the name on line 1, email on line 2, and phone on line 3. Leave a missing line blank. Use the verified primary email and phone when there are multiple values. Use the Location column for the session venue or address and wrap it within the cell.
- Show the student count, total scheduled lesson hours per week, and gross scheduled revenue per week. Compute revenue from lesson duration and hourly rate before fees, expenses, and cancellations. Report separate currency totals if rates use different currencies and no conversion is authorized. Use lesson times rather than calendar buffers for these calculations.
- On every page, show the actual generation date in America/Los_Angeles as `Created Nov 11, 2026` and the page number as `Page 1 of 1` using the actual page count. Keep print instructions off the page.

## Output and versioning

- Save the final PDF in `iCloud Drive/iCloudProjects/Tutoring`.
- Name each PDF `Tutoring_Clients_YYYY-MM-DD_NNN.pdf` using the Pacific generation date. Start each date at `001` and assign the next available revision above the highest existing revision for that date. Preserve all prior PDFs. Use a write that fails on a filename collision and retry with the next revision.
- In Finder, sort by Name in descending order to show the newest date and revision first.
- Verify the requested edits, sort order, weekly totals, footer, and readable rendering before delivery. Confirm the final file exists at the requested destination. Report any missing fields or save failure.

## Source of truth

The latest versioned roster PDF is the sole source of truth for roster data. Select it by the highest date and revision in the filename. Use Google Contacts and Google Calendar to fill missing information as described above. If a value needed for an update cannot be recovered reliably, ask for it before publishing the new version.

A Notion database is a possible future source of truth. It is outside the scope of the current workflow.
