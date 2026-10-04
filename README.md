# scoop-voxscribe

A [Scoop](https://scoop.sh) bucket for [VoxScribe](https://github.com/ahmedhmam1994/voxscribe-ai-voice-dictation), a free, open-source voice dictation app for Windows. Hold a hotkey, talk, release, and the text is typed into whatever app has focus. Transcription runs locally with Whisper, so nothing is uploaded.

## Install

```
scoop bucket add voxscribe https://github.com/ahmedhmam1994/scoop-voxscribe
scoop install voxscribe
```

Update later with `scoop update voxscribe`.

On first launch VoxScribe downloads its speech model (a few hundred MB), so it needs an internet connection once. After that it works fully offline.

## About

- App: https://github.com/ahmedhmam1994/voxscribe-ai-voice-dictation
- Website: https://getvoxscribe.vercel.app
- License: MIT
