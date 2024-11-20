# **FeelFlow**  
**Emotion Classification for Text and Speech**  

## **Overview**  
EmotiSense is a cutting-edge machine learning project designed to classify emotions into 27 distinct classes using the GoEmotions dataset. It is capable of processing both text and speech inputs, providing a comprehensive solution for emotion recognition. Powered by RoBERTa embeddings and a RoBERTa-based model, EmotiSense delivers high accuracy in recognizing complex emotional cues, enhancing applications in human-computer interaction and AI-driven sentiment analysis.  

---

## **Features**  
- Supports **27 emotion classes** for detailed emotion analysis.  
- Handles **text** and **speech** inputs effectively.  
- Built using **RoBERTa embeddings** and a **RoBERTa-based classification model** for state-of-the-art performance.  
- Pretrained on the **GoEmotions** dataset for robust emotion recognition.  

---

## **Dataset**  
The project uses the **GoEmotions** dataset by Google Research.  
Dataset link: [GoEmotions on Hugging Face](https://huggingface.co/datasets/google-research-datasets/go_emotions?row=82)  

- **Dataset Details**:  
  - Contains **58k examples** of carefully labeled emotional data.  
  - Includes **27 emotion classes** for fine-grained emotion detection.  
  - Dataset source: user comments from Reddit.  

---

## **Model Architecture**  
- **Embeddings**: RoBERTa embeddings extract high-quality contextual representations of text.  
- **Classifier**: A RoBERTa-based model fine-tuned on the GoEmotions dataset.  
- **Speech Input Handling**: Converts speech to text using a speech-to-text engine (e.g., Whisper, DeepSpeech), allowing seamless emotion classification for audio inputs.  

---
