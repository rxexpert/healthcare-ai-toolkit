# Transcript Handling Guide

When multiple transcripts are provided, it is important to reconcile them to create the most accurate version. This guide provides instructions on how to handle different transcript formats.

## VTT (.vtt) Files

VTT files are plain text files that contain the transcript of a meeting, along with timestamps. The format is as follows:

```
WEBVTT

00:00:01.000 --> 00:00:05.000
<v Speaker 1> Hello everyone.

00:00:06.000 --> 00:00:10.000
<v Speaker 2> Hi there.
```

## SRT (.srt) Files

SRT files are also plain text files that contain the transcript of a meeting, along with timestamps. The format is as follows:

```
1
00:00:01,000 --> 00:00:05,000
Speaker 1: Hello everyone.

2
00:00:06,000 --> 00:00:10,000
Speaker 2: Hi there.
```

## Reconciliation Process

1.  **Read Both Transcripts:** Read the contents of both the VTT and SRT files.
2.  **Compare Timestamps:** Compare the timestamps of the two transcripts to identify any discrepancies.
3.  **Compare Content:** Compare the content of the two transcripts to identify any differences in the spoken text.
4.  **Merge and Reconcile:** Merge the two transcripts, giving preference to the one that appears to be more accurate. If one transcript is known to be more accurate (e.g., from a more reliable source), give it preference. If there are still discrepancies, use the meeting recording to determine the correct content.
