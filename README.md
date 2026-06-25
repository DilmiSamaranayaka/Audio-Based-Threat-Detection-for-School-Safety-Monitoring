# Audio-Based Threat Detection for School Safety Monitoring

## Overview

This project is a Python-based audio analysis system designed to detect potential threats in school environments by processing sound patterns in real time. It combines machine learning, audio signal processing, and a Flask API to support monitoring and analysis workflows.

## Project Purpose

The system is intended to assist with early awareness of suspicious audio events while maintaining a privacy-conscious approach. It focuses on real-time processing rather than long-term audio recording.

## Key Features

- Real-time audio threat detection
- Noise-aware preprocessing and calibration
- Pretrained audio analysis support
- Flask-based API for integration
- Training, evaluation, and testing utilities

## 🛠️ Tech stack

- Python 3.10+
- Flask
- PyTorch and torchaudio
- Librosa, pydub, and SoundFile
- scikit-learn, pandas, and NumPy
- SpeechRecognition

## 🚀 Quick start

1. Create and activate a virtual environment
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Install FFmpeg
   - Windows: `winget install ffmpeg`
   - Linux: `sudo apt install ffmpeg`
   - macOS: `brew install ffmpeg`

4. Start the server
   ```bash
   python app.py
   ```

5. Open the API endpoints and begin testing

## 📁 Project structure

- [app.py](app.py) — application entry point
- [api/](api/) — API routes and request handling
- [models/](models/) — threat detection and classification logic
- [training/](training/) — data loading and model training flow
- [utils/](utils/) — audio processing and feature extraction helpers
- [tests/](tests/) — validation and regression checks
- [Documentations/](Documentations/) — detailed project documentation

## 🔗 Main API endpoints

The server exposes endpoints for:

- health and status checks
- audio analysis
- calibration
- detection sessions
- sensitivity tuning

## 🧪 Training and evaluation

Useful commands include:

```bash
python run_training.py
python retrain_model_fixed.py
python display_model_accuracy.py
```

## 📚 Documentation

Detailed documentation is available in the [Documentations/](Documentations/) folder, including guides for:

- privacy handling
- audio processing
- calibration
- model training and fixes
- integration guidance

## 🌱 Notes

This project is best viewed as a practical research prototype for intelligent school safety monitoring. It is designed to be adaptable, explainable, and extendable as the system evolves.

If you want to improve it further, the next natural steps would be better model tuning, expanded threat classes, and stronger deployment integration.
