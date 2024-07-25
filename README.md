# 📚 llm-english-study-audio-sentence-creator

Welcome to the **llm-english-study-audio-sentence-creator** project! 🎉 This prototype is designed to assist students in learning English by listening to and practicing sentences in various contexts. Our goal is to expand beyond common topics like food and travel and dive into the tech industry vocabulary. 💻

## 🚀 Problem Addressed

The primary challenge we tackle is the lack of English sentences related to programming and technology in our existing audio resources. To bridge this gap, we've developed this project to generate and convert tech-related sentences into audio format.

## 💡 Project Overview

Here's how we approach the solution:

1. **Transcribe Audio Files**: We use the Whisper model from OpenAI on Hugging Face to transcribe existing audio files into text. 📝
   
2. **Sentence Separation**: Properly separate the transcribed sentences for better understanding by language models. 🧩

3. **Generate Tech Vocabulary Sentences**: Utilize the LLM to adapt sentences from the original course content to incorporate tech vocabulary, rather than generating new sentences from scratch. 🛠️

4. **Convert Text to Speech**: Employ Microsoft's `speecht5_tts` model to convert the generated sentences into audio speech. 🎙️

5. **Process Audio Files**: Convert the generated audio into MP3 format for easy use. 🎵

## 🔑 Key Points

### 1. **Transcription Accuracy**: 
   - **Challenge**: Ensuring high accuracy when transcribing audio files with complex or varied sentence structures.
   - **Solution**: Using the Whisper model for its robustness in handling diverse audio inputs.

### 2. **Sentence Separation**: 
   - **Challenge**: Properly separating sentences from the transcribed text for better comprehension by language models.
   - **Solution**: Developing a prompt method to cleanly segment and organize sentences to improve processing.

### 3. **Tech Vocabulary Adaptation**:
   - **Challenge**: Generating sentences that accurately reflect tech industry vocabulary while maintaining naturalness.
   - **Solution**: Adapting existing sentences to include tech terms rather than generating new content from scratch.

### 4. **Speech Conversion**:
   - **Challenge**: Ensuring the generated text-to-speech audio sounds natural and clear.
   - **Solution**: Utilizing Microsoft's `speecht5_tts` model for high-quality speech synthesis.

### 5. **Audio Processing**:
   - **Challenge**: Converting audio to MP3 format while maintaining audio quality.
   - **Solution**: Implementing a streamlined process for converting and optimizing audio files.


## Dependencies
  - FFMPEG dependency  
```bash
sudo apt-get update  
sudo apt-get install ffmpeg libavcodec-extra  
```
