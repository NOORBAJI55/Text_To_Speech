# Text-to-Speech Converter

This Python program converts text input into speech using the Google Text-to-Speech (gTTS) library. The generated audio is saved as an MP3 file, which can be played back on any compatible media player.

## Features

- Converts user-provided text to speech
- Supports multiple languages (English by default)
- Saves the audio output as an MP3 file

## How It Works

1. The program prompts the user to input text.
2. It initializes a `gTTS` object with the specified text and language.
3. The audio is saved as `voice_note.mp3`.
4. Optionally, the program can play the audio file automatically (commented out for user choice).

### Example
