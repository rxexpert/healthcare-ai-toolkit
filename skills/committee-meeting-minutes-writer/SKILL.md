---
name: committee-meeting-minutes-writer
description: Creates comprehensive and professionally formatted meeting minutes for committee meetings. Use this skill when you need to process meeting transcripts, attendance reports, and agendas to produce detailed and structured minutes. This skill is ideal for formal meetings that require accurate records of discussions, decisions, and action items.
---

# Committee Meeting Minutes Writer

## Overview

This skill provides a comprehensive workflow and template for creating detailed and professional meeting minutes for committee meetings.



## Workflow

Follow these steps to create the meeting minutes:

1.  **Analyze Input Files:**
    *   Read the meeting agenda to understand the planned topics.
    *   Read the meeting transcript(s) to capture the discussion content.
    *   Read the attendance report to get a list of participants.
    *   If a video or audio recording is provided, use it to clarify any ambiguities in the transcript.

2.  **Handle Multiple Transcripts:**
    *   If multiple transcripts are provided (e.g., VTT and SRT), read both and reconcile them to create the most accurate version. Refer to `/home/ubuntu/skills/committee-meeting-minutes-writer/references/transcript_handling.md` for guidance on reconciling different transcript formats.

3.  **Handle Missing Agenda:**
    *   If no agenda is provided, analyze the transcript and recording to identify the main topics of discussion and create a de facto agenda.

4.  **Process Attendance Information:**
    *   Extract the list of participants from the attendance report.
    *   If the attendance report is incomplete or missing, extract participant names from the transcript.

5.  **Draft the Meeting Minutes:**
    *   Use the template provided in `/home/ubuntu/skills/committee-meeting-minutes-writer/templates/meeting_minutes_template.md` to structure the minutes.
    *   Fill in the header information, participants table, and the main content section with the information gathered from the input files.
    *   Ensure that the minutes are detailed, accurate, and professionally formatted.

6.  **Review and Finalize:**
    *   Review the drafted minutes for any errors or omissions.
    *   Ensure that all key discussions, decisions, and action items are accurately captured.

## Input Files

This skill is designed to work with the following input files:

*   **Agenda:** A `.docx` or `.txt` file outlining the meeting topics.
*   **Transcript(s):** `.vtt` or `.srt` files containing the meeting's spoken content.
*   **Attendance Report:** A `.csv` file with a list of participants and their join/leave times.
*   **Recording:** An `.mp4` or `.mp3` file of the meeting.

## Output Format

The final output should be a single Markdown file (`.md`) following the structure defined in the template.


