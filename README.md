# Hands-free Audio Test

Simple single-page browser test for continuous listening + text-to-speech.

Uses the Web Speech API (`webkitSpeechRecognition` + `speechSynthesis`).

## Features
- Always-on listening while the page is in the foreground
- Speaks recognized text back (pauses mic briefly while speaking, then resumes)
- Debug log for troubleshooting iOS quirks
- Test Speak button

## Notes
- Requires a secure context (HTTPS) for microphone access
- Works best in Safari on iOS or Chrome on desktop
- On iOS the page must stay in the foreground

Live test (self-signed cert): https://167.99.231.180:8443/
