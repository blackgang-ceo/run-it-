# BLACKGANG Video Studio · Eight Free Creative Tools Edition

A responsive, zero-build browser video maker for CHECK CHASING EMPIRE LLC.

## What works immediately
- Generate moving graphics, audio-reactive music visualizers, teasers, and short videos in your browser, with titles and optional photos, WAV/MP3 audio, or MP4/WebM clips.
- Import Whisper-style `.srt` captions and burn them into exported video.
- Use the director prompt creator to make a detailed Wan 2.2 or LTX-2 prompt; create AI footage externally and import it.
- Download MP4 **if your browser can record MP4**, otherwise WebM; export in 9:16, 16:9 or 1:1.
- Save project metadata to browser local storage and reload later. Reattach your source files.
- Open each of the eight official upstream tools in the integrated hub.

## What this is not
This is a **working browser-based video editor and animated video generator**, **not** a hosted Wan/LTX GPU inference service. It cannot produce photorealistic text-to-video clips from prompts alone. That requires a model worker, GPU hosting, orchestration/job queues, and licensing review. It does not run VoiceStudio, Chatterbox, Whisper, Auto-Editor or Kdenlive inside the browser; those are standalone tools. Nothing in this package implies zero-cost GPU cloud rendering.

## The eight tools (from the provided screenshot)
1. **VoiceStudio:** https://github.com/debpalash/VoiceStudio — local narration and dubbing.
2. **Chatterbox:** https://github.com/resemble-ai/chatterbox — local speech synthesis.
3. **Wan 2.2:** https://github.com/Wan-Video/Wan2.2 — AI video model (GPU).
4. **LTX-2:** https://github.com/Lightricks/LTX-2 — AI video model (GPU; check license).
5. **Whisper:** https://github.com/openai/whisper — automatic captions as `.srt`.
6. **Auto-Editor:** https://auto-editor.com/ — automatic cuts and silence removal (CLI).
7. **Kdenlive:** https://kdenlive.org/ — multi-track video editor (desktop).
8. **Mixkit:** https://mixkit.co/ — stock media; verify per-item license.

## Use
Open `index.html` in Chrome/Edge or host the folder as a static website. Upload artwork, video and music, optionally subtitles. Click Preview; click Generate & export video; download result. A current Chromium browser is recommended for the most reliable WebM export. iOS/Safari MediaRecorder behavior may differ.

## Hosting
This is a static site (the included `vercel.json` is optional). Upload the 3 files (`index.html`, `README.md`, `vercel.json`) to a static-hosting provider to access it online. Example: Cloudflare Pages Direct Upload. The upstream eight tools are not bundled into the host and should be installed/run separately.

## Privacy and licensing
- Inputs and soundtracks are handled locally by your browser, not uploaded by this code.
- Existing project content is saved as metadata only. The website does not store source media across sessions.
- You must hold rights to audio, footage, voices, images, and any Mixkit media used.
- Commercial use of *model weights* and GPU services is subject to applicable terms, independent of this studio's code.