# voice-bubble-models

Model files for **Voice Bubble** — Deep's on-device Hindi voice → English Android app
(package `com.deep.voicebubble`).

## What's here

| File | Size | Purpose |
|------|------|---------|
| `gemma3-1b-it-int4.task` (via Release `models-v1`) | ~529 MB | On-device LLM used to polish Whisper's raw English transcription (grammar, punctuation, capitalisation; filler-word removal). Runs 100% on-device via LiteRT-LM; no server, no API cost. |

The app downloads this file once from the
[models-v1 release](https://github.com/deepresearcher25/voice-bubble-models/releases/tag/models-v1)
and verifies its SHA-256 before use.

## Licence

"Gemma is provided under and subject to the Gemma Terms of Use found at ai.google.dev/gemma/terms"

- Full terms: see `GEMMA_TERMS.md` in this repo (copy of https://ai.google.dev/gemma/terms)
- Prohibited uses: see `GEMMA_PROHIBITED_USE_POLICY.md` (copy of https://ai.google.dev/gemma/prohibited_use_policy)
- Third-party notices (sherpa-onnx, Whisper, Silero VAD, Gemma): see `NOTICE`
