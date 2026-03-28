# Deep Learning for Speech

A collection of presentation slides covering three key areas where deep learning intersects with speech and audio processing. These were prepared as part of academic coursework exploring state-of-the-art architectures for speech-related tasks.

## Topics Covered

### 1. Text-to-Speech — FastSpeech2
`TTS-FastSpeech2.pptx`

Covers the FastSpeech2 architecture for non-autoregressive text-to-speech synthesis. FastSpeech2 improves on the original FastSpeech by directly predicting pitch, energy, and duration from text, enabling faster and more expressive speech generation compared to autoregressive models like Tacotron2.

### 2. Keyword Spotting using Conformer
`KeyWord Spotting using Conformer.pptx`

Explores the Conformer architecture (Convolution-augmented Transformer) applied to keyword spotting — the task of detecting specific trigger words in a continuous audio stream. The Conformer combines self-attention for global context with convolution for local patterns, achieving strong performance on speech tasks.

### 3. Speech Emotion Recognition
`Emotion Recognition.pptx`

Covers deep learning approaches to recognizing emotional state from speech signals. Includes feature extraction strategies (MFCCs, spectrograms) and neural network architectures for classifying emotions such as happiness, sadness, anger, and neutrality.

## Tech Stack

- Deep Learning frameworks (PyTorch / TensorFlow)
- Librosa for audio feature extraction
- Transformer / Conformer architectures
