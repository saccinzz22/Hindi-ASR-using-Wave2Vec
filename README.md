# Hindi-ASR-using-Wave2Vec2
 

# Hindi Speech Recognition with Wav2Vec2  

This project fine-tunes the `facebook/wav2vec2-large-xlsr-53` model for Hindi speech recognition using the Common Voice dataset.  

## Overview & Applications  

Automatic Speech Recognition (ASR) enables machines to understand and transcribe spoken language into text. This project trains a deep learning model to convert Hindi speech into text, making it useful for:  

- **Voice Assistants**: Enhancing AI-driven virtual assistants with Hindi language support.  
- **Transcription Services**: Automating Hindi audio-to-text conversion for interviews, lectures, and media content.  
- **Accessibility Tools**: Assisting users with hearing impairments by providing real-time speech transcription.  
- **Language Learning**: Helping learners improve pronunciation and comprehension through speech-to-text feedback.  
- **Voice-Controlled Applications**: Integrating with smart devices to process spoken Hindi commands.  

## Features  

- **Data Preprocessing**: Cleans and prepares audio-text pairs, removing special characters and normalizing text.  
- **Tokenization & Feature Extraction**: Uses a custom vocabulary and `Wav2Vec2Processor` to convert speech into model-ready input.  
- **Model Fine-tuning**: Trains the pre-trained Wav2Vec2 model on Hindi speech data to improve speech-to-text accuracy.  
- **Saving & Loading Model**: Saves trained model weights for reuse in inference or further training.  

## Usage  

Train the model in Google Colab and download the weights locally after training. The trained model can be used for inference on new audio samples.  

## Model Checkpoint  

After training, the model weights are saved and can be loaded for further fine-tuning or inference.  

## Acknowledgments  

- Mozilla Common Voice Dataset  
- Hugging Face Transformers Library  

