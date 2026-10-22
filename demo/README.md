# FrameScore Interactive Demo

This folder contains a fully local, browser-based prototype of FrameScore's
core workflow.

## Run locally

Open `index.html` in a modern browser. No installation, build step, API key, or
external service is required. Keep every file in this directory together.

## Included

- Three playable 10-minute video inputs
- Four timestamped 2:30 Music Map cues per video
- A generated original score for each project
- Four cue-level revision variants per project
- A 60-second product walkthrough in `framescore-60s-demo.mp4`

## Demo workflow

1. Select one of the three sample videos.
2. Analyze its emotional arc.
3. Create the timestamped Music Map.
4. Generate and preview the soundtrack.
5. Scrub or play the video to see the active cue, timestamp, prompt, and
   playhead follow the picture.
6. Select a cue and enter `Make this more emotional`.
7. Regenerate only that cue.
8. Compare the original and revised versions at the same timestamp.

The analysis and rendering waits are simulated. Video and music playback use
the local media files in this directory.
