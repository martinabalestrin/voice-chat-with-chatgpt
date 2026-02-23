### 🎙️  Voice Chat with ChatGPT (Python)

Minimal demo showing a full voice pipeline:

`Microphone → Whisper → ChatGPT → gTTS → Audio`

The script:
1. Records audio from the browser (via Colab + JavaScript)
2. Transcribes speech using Whisper
3. Sends text to ChatGPT (OpenAI API)
4. Converts the response to speech with gTTS

### ⚠️  Environment

Designed for Google Colab. It relies on:
- `google.colab`
- In-notebook JavaScript execution
- Browser microphone access

Running locally requires modifications.

### 🔑  API Key

Replace `client = OpenAI(api_key="YOUR_KEY_HERE")` with your actual key.
