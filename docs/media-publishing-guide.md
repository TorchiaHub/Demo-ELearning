# Media Publishing Guide

This repository is meant to be public while the implementation remains private. The media should therefore explain the experience without exposing source code, routes, payloads, credentials or internal debugging screens.

## Recommended Public Assets

- One short walkthrough video, around 45-60 seconds.
- Six screenshots: dashboard, course entry, pairing, lesson map, live interaction, mobile companion.
- One or two short avatar clips.
- One architecture diagram.

For the current capture checklist, use [Demo Content Capture Plan](demo-content-capture-plan.md).

## What Not To Show

- Source code.
- Terminal windows.
- `.env` files.
- Internal logs with real identifiers.
- Private customer data.
- Raw implementation documents.
- Long unedited recordings where local paths or private branch names are visible.

## GitHub README Video Options

GitHub README files are best treated as Markdown pages with images and links. For videos, the most reliable pattern is:

```md
[![Watch the demo](assets/screenshots/course-home.png)](https://your-video-link.example)
```

Good hosting options:

- upload a compressed MP4 to a GitHub Issue or Release and paste the generated link;
- upload to YouTube or Vimeo and link through a thumbnail;
- host the video on a personal portfolio page;
- keep WebM samples in the repository only as optional downloadable media.

Avoid relying on iframe embeds inside the GitHub README. GitHub sanitizes rendered Markdown/HTML and embedded players are not a dependable presentation method in repository READMEs.

## Suggested Walkthrough Script

1. Show the dashboard and explain that this is a prototype for safety training.
2. Start the course and show Elena as the avatar tutor.
3. Pair the phone and desktop with the QR code.
4. Answer one mobile interaction and show the desktop updating live.
5. Show a concept map or lesson block to prove it is not only a quiz app.
6. End with final quiz or event tracking summary.

## Export Settings

Recommended export for GitHub/public portfolio:

- MP4 container.
- H.264 video codec.
- AAC audio.
- 1080p or 720p.
- 45-60 seconds.
- Under 10 MB if using a free GitHub repository attachment workflow.
