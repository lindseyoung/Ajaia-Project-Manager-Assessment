# Ajaia-Project-Manager-Assessment
SidelineReel — Roster Tagging Prototype

A working prototype for improving roster tagging accuracy in SidelineReel, an AI-powered youth sports video platform.

The prototype focuses on the human-in-the-loop workflow for low-confidence player identification:

High-confidence jersey numbers are tagged automatically.
Low-confidence clips are flagged for coach review.
Coaches can confirm the AI's suggested player or select a different rostered player.
Corrections are saved and reflected in the game results.
The prototype demonstrates how human corrections can provide labeled data to improve future tagging.

Why this prototype matters:

Incorrect player attribution is a core product failure; a highlight assigned to the wrong child undermines trust in the entire product. This workflow is designed to automate the common case while giving coaches a lightweight way to resolve ambiguous cases rather than silently making incorrect assignments.

Note: This is a product/UX prototype. It simulates the AI tagging and video-analysis components rather than performing actual computer vision.
