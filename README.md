# Deutsch Daily — Colorful A1–B2 + Zürich Edition (v1.2)

A free, offline-friendly German practice progressive web app (PWA), with no account or paid AI services.

## Included
- 20 short lessons: 3 A1 + 8 A2 + 3 B1 + 3 B2 + 3 Swiss German (Zürich-flavoured)
- 5 scripted dialogues, including a Zürich bakery scenario
- Multiple-choice exercises, spaced-repetition vocabulary, error logging, streaks and backup/restore
- Swiss German phrases accompanied by Standard German equivalents. Swiss German spelling varies and written phrases only approximate pronunciation; Zürich expressions also vary by speaker.

This is an introductory sample curriculum, **not** a full CEFR A1–B2 course. It includes basic writing, listening playback and optional speech-to-text practice, but cannot reliably grade free-form answers or pronunciation and cannot certify B2 proficiency. All dialogues are scripted; there is no AI tutor.

## Install on Samsung for free
Unzip the archive. Upload the **contents** of the deutsch-daily folder (not the parent folder) into a public GitHub repository. Enable GitHub Pages under Settings > Pages > Deploy from a branch > main > /(root). Wait for the published HTTPS link. Open it in Chrome on Samsung and use the menu > Install app (or Add to home screen). It needs HTTPS hosting for offline caching and PWA install.

## Privacy
Progress stays in that browser's localStorage. Clearing app/browser storage or uninstalling can delete it. Export a backup regularly from Progress. GitHub Pages is public hosting, but your stored answers are not uploaded to GitHub.


## Version 2: write, listen, speak (no paid AI)
- Choose, Write, or Speak modes are available in lesson questions and guided dialogues.
- Speaker controls use available German voices on your device via the Web Speech synthesis API. Swiss German text uses de-CH when supported, but a genuine Zürich dialect voice is not guaranteed.
- Microphone transcription uses browser SpeechRecognition if available (may require network processing and browser permissions). It is not pronunciation scoring.
- Typed responses are compared with model answers. Open-ended answers are self-assessed; valid alternatives cannot be graded reliably without AI.
- Existing progress is preserved by retaining the original localStorage key. Back up progress in the Progress tab before updating.
- To update GitHub Pages, upload all six files at repository root, choose replace where prompted, commit, and reload the website. Existing URLs remain unchanged.
