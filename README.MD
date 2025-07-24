# 🧠 AI-Powered Image-Driven Multilingual Assistant 

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow.svg)

---

## 🔍 Overview

An intelligent AI assistant that allows users to upload images (documents, product photos, forms, signs, diagrams, etc.) and ask questions about them. The assistant supports multiple Indian languages and uses state-of-the-art vision-language models to provide rich, contextual responses in the user's preferred language.

Designed with accessibility in mind for diverse regions and linguistic backgrounds across India.

---

## 🎯 Key Features

### 🖼️ Image Intelligence
- **Image Upload & Parsing** – Support for JPG, PNG, PDF screenshots
- **Vision Transformer Models** – Extract semantic meaning from images
- **Multimodal Embeddings** – Enable natural-language Q&A about image content

### 🌐 Multilingual Support
- **Language Detection** – Identify user language automatically
- **Translation Pipeline** – Translate user questions into English and answers back
- **Indian Language Coverage** – Supports Hindi, Tamil, Telugu, Bengali, Kannada, Malayalam, Gujarati, Marathi, Punjabi, and more

### 💬 Text Interaction Interface
- **Streamlit App** – Simple UI for uploading images and typing questions
- **Text-Based Q&A** – Input your query and get a translated response
- **Language Selector** – Choose or auto-detect your preferred language

---

## 🧪 Use Cases

| Sector         | Example Application                                           |
|----------------|---------------------------------------------------------------|
| Agriculture    | Ask questions about crop disease images in your native language |
| Government     | Understand scanned ration cards or ID documents in Hindi/Tamil |
| Education      | Students can ask about diagrams in local language              |
| Retail         | Product image Q&A for rural sellers                            |
| Healthcare     | Understand medical scan info or prescription images            |

---

## 🔧 Technology Stack

### Core AI & Vision

| Component      | Technology        | Purpose                          |
|----------------|-------------------|----------------------------------|
| Vision Model   | CLIP / LLaVA      | Extract meaning from images      |
| LLM            | Mistral / DeepSeek| Answer generation                |
| Embeddings     | SentenceTransformers | Text-image alignment         |
| Vector Store   | FAISS             | Image similarity search          |

### Multilingual Support

| Component        | Technology             | Purpose                         |
|------------------|------------------------|---------------------------------|
| Language Detection| `langdetect`           | Auto-select input language      |
| Translation API | Google Translate API    | Translate to/from English       |

### UI & App

| Component         | Technology            | Purpose                         |
|-------------------|------------------------|---------------------------------|
| Web Interface     | Streamlit             | Browser-based app               |
| File Handling     | PIL, OpenCV           | Image preprocessing             |
| Deployment        | HuggingFace Spaces / Streamlit Cloud | Public access     |

---

## 🚀 Development Phases

### ✅ Phase 1: Image Upload + Multilingual RAG  
- Image input + preprocessing  
- Multimodal embedding using CLIP  
- Basic LLM-powered RAG logic  
- Query translation + response translation  
✅ **Deliverable:** Users upload image + ask questions in Indian language

---

### ✅ Phase 2: Streamlit Interface 
- Build multilingual image chat interface  
- Include file uploader, language selector, text chat  
✅ **Deliverable:** Web app that allows image-driven multilingual Q&A

---

### ✅ Phase 3: Dataset Expansion + Evaluation  
- Add regional language datasets for testing  
- Evaluate accuracy across multiple Indian scripts  
✅ **Deliverable:** Verified results and performance insights

---

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8+
- Git
- Google Translate API key (optional for offline mode)

### 🌐 Acknowledgements
- HuggingFace, OpenAI, Google Translate
- CLIP, LLaVA, DeepSeek, Mistral
- Streamlit + Indian language NLP community
