# Audio & Speech AI Prototype (AIPDD Lab 04)

**Name:** Muhammad Umar
**Roll No:** 231243

A small Google Colab project that records your voice, visualizes it, preprocesses it, and converts it to text using a pretrained Whisper model.

## Pipeline

```
Microphone → Recording → WAV → Waveform → Spectrogram → Preprocessing → Whisper ASR → Text
```

## What It Does

1. Records 5 seconds of speech from the browser microphone
2. Loads the audio and prints sampling rate, samples and duration
3. Plots the **waveform** (amplitude vs. time)
4. Plots the **spectrogram** (frequency vs. time using STFT)
5. Preprocesses audio: resamples to 16 kHz and normalizes volume
6. Transcribes speech with `openai/whisper-tiny.en` (Hugging Face Transformers)

## Requirements

- Google Colab (uses the browser microphone)
- Libraries: `librosa`, `soundfile`, `matplotlib`, `transformers`

## How to Run

1. Open `AIPDD_Lab04_Muhammad_Umar_231243.ipynb` in [Google Colab](https://colab.research.google.com)
2. Click **Runtime → Run all**
3. Allow microphone access when asked, then speak for 5 seconds
4. View the plots and the final transcription

## Files

| File | Description |
|------|-------------|
| `AIPDD_Lab04_Muhammad_Umar_231243.ipynb` | Complete solved notebook |
| `README.md` | Project description |

## Tech Used

Python · Librosa · Matplotlib · Hugging Face Transformers · OpenAI Whisper
