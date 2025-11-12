---
language: 
- en
license: apache-2.0
tags:
- multimodal
- speech-to-text
- vision-language
- empathy-ai
- transformers
pipeline_tag: audio-text-to-text
library_name: transformers
base_model: openai/whisper-small
datasets:
- custom
metrics:
- bleu
- rouge
---

# Neuro-MindTalker 🧠🎙️ — Multimodal Emotional Dialogue Model

**Neuro-MindTalker** is an innovative multimodal AI system that combines **speech**, **text**, and **visual** understanding to generate empathetic, human-like dialogue.  
It integrates **Whisper** for speech-to-text, **CLIP** for image emotion recognition, and a fine-tuned **Flan-T5** for text generation.

### 🚀 Features
- Understands speech tone & transcribes it intelligently  
- Detects visual emotion cues from faces or art  
- Generates empathetic, context-aware responses  
- Supports real-time conversation interface (`app.py`)

### 🧩 Use Cases
- Emotional companion AI  
- AI-driven therapy assistant  
- Smart art critic (interprets image mood + describes it)  

### 🧠 Model Architecture
1. **Audio Processing** → Whisper (speech-to-text)  
2. **Visual Understanding** → CLIP (image embeddings)  
3. **Language Response** → Flan-T5 (response generator)

### ⚖️ License
Apache-2.0

---

### 🧪 Example Input
Speech: “I’m feeling tired lately.”  
Image: A dark painting.  

**Output:**  
“I can sense exhaustion in your tone and from the mood of the image. Maybe take a short walk or do something relaxing tonight.”
