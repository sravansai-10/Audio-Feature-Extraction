🎧 Audio Feature Extraction Using Python & Librosa
This project is a complete implementation of an Audio Feature Extraction System for Rhythm Classification, developed as part of a final semester Machine Learning assignment. It uses Python and the librosa library to analyze audio signals and extract meaningful rhythmic features.

Objective
The main objective is to:

Load audio files (e.g., MP3)

Extract rhythm-related features such as tempo, beat frames, and onset strength

Perform time-frequency analysis

Estimate pitch and visualize musical patterns for classification tasks

📌 Key Features
🎵 Load Audio Files: MP3 input via librosa.load()

🧩 Rhythm Feature Extraction: Beat tracking, tempo estimation, onset strength analysis

📊 Visualization: Waveform, onset strength, tempo histograms, spectrograms

🎚️ Pitch Estimation: Frequency analysis over time using STFT and piptrack

📈 Spectrogram Generation: Convert audio amplitudes to dB scale

📁 Project Structure
bash
Copy
Edit
audio-feature-extraction/
│
├── audio_feature_extract.ipynb       # Main notebook
├── audio_files/                      # Sample audio tracks
│   └── *.mp3
├── requirements.txt                  # Python dependencies
├── LICENSE                           # MIT License
└── README.md                         # Project overview

📷 Sample Outputs

🔊 Onset Strength & Detected Beats

🎼 Spectrogram (STFT)

🎵 Pitch Estimation

This project is licensed under the MIT License © 2025 Sravan Sai Methuku.
You are free to use, copy, modify, and distribute this software with attribution.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

