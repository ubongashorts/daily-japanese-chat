# Daily Japanese Chat

A single-page voice app for practising spoken Japanese with a beginner-friendly
AI partner, built on the Gemini Live API.

Every turn comes back in two parts: a short Japanese sentence, then its full
English translation.

## Use it

Open the page, tap **Key**, paste a Gemini API key from
[Google AI Studio](https://aistudio.google.com/api-keys), then tap **Talk**.

The key is stored in your browser's `localStorage` only. It is never uploaded
anywhere and is not contained in this repository.

## Spoken commands

`again` · `slower` · `shorter` · `easier` · `harder` · `no English` · `English please`

## Notes

Requires HTTPS (or localhost) for microphone access. Auto-stops after three
minutes of silence so it never streams in the background.
