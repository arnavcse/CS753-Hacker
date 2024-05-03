# 🎧 🌲 **CS 753: Advanced Neural Techniques for Audio Analysis and Processing under the guidance of Professor Preethi Jyothi**

![Advanced Neural Techniques](2.gif)

![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8%20%7C%203.9-blue)
![License](https://img.shields.io/badge/License-MIT-red)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/arnavcse/CS753-Hacker)

## Contributors 🧑‍🎓🌟

Meet the brilliant minds behind this project:

- **Anuj Attri (23M0808)** 👨‍🎓
- **Arnav Attri (23M0811)** 👨‍🎓
- **Pratham Tarjule (20D110029)** 👨‍🎓

## Introduction 🌟

This repository contains three advanced Jupyter notebooks that demonstrate innovative uses of neural networks for audio analysis, transcription, and processing.

---

## Notebooks Overview 📚

### 1. **Whisper Models with LibriSpeech Dataset** 🗣️

This notebook demonstrates the application of OpenAI's Whisper models (Tiny, Base, Small) for transcribing audio data from the LibriSpeech dataset. Utilizing advanced audio preprocessing techniques and machine learning models, we achieve progressively lower Word Error Rates (WER).

- **Technologies used:** `torch`, `whisper`, `pandas`, `torchaudio`
- **Key features:**
  - Audio data preprocessing 🎚️
  - Utilization of different Whisper model sizes 📏
  - WER calculation and comparison 📉

### 2. **Playing Audio Files and Generating Transcripts with Wav2Vec2** 🔊

Dive into the process of playing audio files and converting them into text using the Wav2Vec2 model. This notebook provides a hands-on approach to handling audio data, processing it with sophisticated models, and generating accurate transcripts.

- **Technologies used:** `torch`, `IPython`, `librosa`, `transformers`
- **Highlights:**
  - Audio playback in Jupyter notebooks 🎧
  - Detailed transcription process with model insights 📝
  - Analysis of transcription accuracy and model warnings ⚠️

### 3. **Temporal U-Net with Squeezeformer Blocks** ⏳

Explore a sophisticated architecture that combines Temporal U-Net with Squeezeformer blocks for enhanced sequence processing. This notebook introduces a powerful model for handling complex sequential data, demonstrating the integration of convolution and attention mechanisms.

- **Technologies used:** `torch`
- **Special features:**
  - Encoder-decoder architecture with Squeezeformer blocks 🔧
  - Depthwise separable convolution subsampling 🌀
  - Application in sequential data processing and analysis 🔍

---

**What was your assigned hacker paper and how does what you've implemented relate to it?**

Paper Assigned: Squeezeformer: An Efficient Transformer for Automatic Speech Recognition 

Our Squeezeformer.ipynb implements several components related to the Temporal U-Net architecture, which is a deep learning model designed for sequence-to-sequence tasks, such as audio source separation or speech enhancement.

1. **Squeezeformer Block**

2. **Squeezeformer**:

3. **Depthwise Separable Convolution Subsampling**:

4. **Unified Activations with Squeezeformer Block**:
   
   

**What did you newly implement, where was the code mainly derived from?**

We have tried with Open source Whisper Model to calculate WER on test-clean dataset from librespeech as there was no training script available for Squeezeformer.

Our code was mainly derived from multiple sources including Github, but is majorly written by us.

***Demo is shown in Wav2Vec.ipynb***


---

## Getting Started 🚀

**Ready to Dive In?** These notebooks are fully implemented and ready to run, offering a seamless experience right out of the box. Simply download, open, and execute to explore the cutting-edge techniques in audio processing:

```bash
git clone https://github.com/arnavcse/CS753-Hacker.git
cd CS753-Hacker
jupyter lab
With everything set up for you, getting started is as easy as pie! 🥧 Enjoy experimenting with advanced neural network techniques for audio analysis and processing.

License 📄
This project is licensed under the MIT License - see the LICENSE.md file for details.

Show Your Support 💖
Give a ⭐️ if this project helped you!
