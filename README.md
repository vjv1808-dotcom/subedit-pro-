# SubEdit Pro V2.1

A local-first SRT editor for mobile browsers.

Features:
- Import .srt
- Edit text and start/end times
- Shift all subtitles ±50/100/500 ms
- Shift individual lines ±100 ms
- Split text into two timed entries
- Merge with next subtitle
- Basic overlap / empty text / invalid timing check
- Export a clean .srt
- Join Part 1, Part 2, and more into one continuous SRT
- Split one full SRT into 2–10 equal, timestamp-preserving SRT files
- Merge multiple SRT tracks by timestamp
- Translate English SRT to natural spoken Tamil with Gemini
- Search Tamil/English subtitle listings with OpenSubtitles
- Preview a local video with the current SRT
- PWA manifest + offline cache

To run:
1. Put these files on any static web host (GitHub Pages, Cloudflare Pages, Netlify, etc.).
2. Open the HTTPS URL in Safari on iPhone.
3. Share > Add to Home Screen.

Gemini and OpenSubtitles API keys are stored only in the user's browser. This
static V2 is intended for the owner's personal use. Permanent video burn-in
requires a native or server-side FFmpeg workflow; V2 provides a private local
playback preview instead.
