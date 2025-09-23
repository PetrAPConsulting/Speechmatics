# Transcription Web Apps

A simple, browser-based applications for transcribing audio files using the Speechmatics API or AssemblyAI API. Both companies have leading models for speech2text including speaker labelling (diarization).
## Features

- Record your meeting or conversation with client on phone
- Upload recording and transcribe audio files using Speechmatics API or AssemblyAI API
- Support for multiple languages (Czech, English, Spanish, you could simply add many others)
- Speaker diarization (identifies different speakers in transcription and label them for further processing)
- Enhanced transcription quality
- Download transcripts as text files
- Encrypted API key storage (optional local storage)
- Clean, responsive user interface

## How to Use

1. Download the HTML file
2. Open the HTML file in your web browser
3. Enter your API key. API Key is stored locally but encrypted.
4. Upload an audio file
5. Select the language of the audio
6. Click "Transcribe Audio"
7. Download the resulting transcript

## Requirements

- A Speechmatics API key (sign up at [Speechmatics](https://www.speechmatics.com/))
- A AssemblyAI API key (sign up at [AssemblyAI](https://www.assemblyai.com/))
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Audio files in a supported format (MP3, M4A, WAV, FLAC, etc.)

## Setup

This is a standalone HTML file with embedded JavaScript and CSS. No server setup is required.

1. Get your API key from [Speechmatics](https://portal.speechmatics.com/settings/api-keys)
2. Get your API key from [AssemblyAI](https://www.assemblyai.com/dashboard/api-keys)
3. Open the HTML file in any web browser
4. Enter your API key in the designated field

## Security Notes

- Your API key is stored encrypted in your browser's local storage if you select "Remember API key"
- All processing is done via the Speechmatics API or AssemblyAI API; no audio data is stored elsewhere
- The application works entirely in your browser

## Limitations

- Transcription quality depends on the Speechmatics or AssemblyAI models
- Large audio files may take longer to process
- The free tier of Speechmatics API has usage limits (4 hours each month)
- The free tier of AssemblyAI give you one time credit $50
## License

MIT License

## Created By

[Petr Adamek AP Consulting](https://www.apconsulting.cz/)

---

Feel free to contribute to this project by submitting pull requests or reporting issues.
