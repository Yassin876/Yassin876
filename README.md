<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:16213e&height=220&section=header&text=Yassin%20Ahmed&fontSize=55&fontColor=e2e8f0&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLMs%20%7C%20Computer%20Vision%20%7C%20Backend&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

[![Portfolio](https://img.shields.io/badge/_Portfolio-0f172a&logo=firefox&logoColor=white?style=for-the-badge)](https://yassin-ahmed-portfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yassinahmad-b471b9344)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yassin876)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yassinahmed6109@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Yassin876&color=6366f1&style=flat-square&label=Profile+Views)

</div>

---

## About Me

```python
yassin = {
 "role" : "AI Engineer | Backend Developer | Data Scientist",
 "school" : "Mobica International School for Applied Technology (USAID IATS)",
 "location" : "Cairo, Egypt ",
 "focus" : ["LLMs", "Computer Vision", "NLP", "Scalable AI Backends"],
 "projects" : "20+ across ML, DL, NLP, CV, Speech & Data Analysis",
 "languages" : ["Arabic (Native)", "English (Intermediate)"],
}
```

I started from Python fundamentals and built up to deploying real AI systems — end-to-end. From lecture summarizers to healthcare AI backends, I turn models into products.

---

## Featured Projects

### [Sugrly](https://github.com/Yassin876) — AI-Powered Diabetic Assistant
> Full-stack healthcare app: blood glucose tracking + AI meal analysis + voice medical guidance

- Built the entire **FastAPI backend** with JWT auth, full REST API docs, PostgreSQL + SQLite
- Integrated **Google Gemini Vision** for food image analysis
- Used **OpenAI Whisper** for voice-to-text medical guidance
- `FastAPI` `PostgreSQL` `Whisper` `Google Gemini` `JWT` `Python`

---

### [The Assistant](https://github.com/Yassin876/ai_summary) — AI Summarization & NLP Platform
> Capstone Project — Production-grade AI platform: summarizes text, translates AR/EN, transcribes audio, and extracts text from documents and images — unified Flask API

**Stats:** 6+ file formats — 3 AI models — Arabic & English — 5GB max file size

**Core Features:**

| Feature | Details |
|---|---|
| Smart Text Summarization | LLaMA3-70B via Groq API, exponential backoff retry logic |
| Bidirectional Translation | Arabic and English, langdetect auto-detection, Google Translate fallback |
| Audio Transcription | Faster Whisper — WAV/MP3/OGG/FLAC/M4A/WebM, SHA-256 caching, 50MB chunking |
| Document Extraction | TXT, DOCX (python-docx), multi-page PDF (PyPDF2) |
| OCR from Images | EasyOCR — Arabic + English, JPG/PNG/GIF |
| Audio URL Support | yt-dlp + ffmpeg — YouTube and remote URLs |

**Processing Pipeline:**
```
Input (File/URL) → File Routing → Extraction → Lang Detection → Summarization → Translation → JSON Response
```

**API Endpoints:**
- `POST /summarize` — raw text → summary + optional translation → returns summary, source_lang, processing_time
- `POST /process` — file upload (audio/doc/image up to 5GB) → extract + summarize + translate
- `POST /process_url` — remote audio URL → yt-dlp download → transcribe → summarize

**System Design:**
- RetryManager with exponential backoff (up to 5 attempts), GROQ_MAX_BACKOFF = 30s
- Singleton ModelLoader with CUDA GPU/CPU auto-selection
- LRU cache on text cleaning and language detection
- ResourceManager monitors free disk (>1GB) and RAM (>500MB)
- ErrorLogger writes timestamped JSON logs to disk

**Stack:** `Python` `Flask` `Groq API (LLaMA3-70B)` `Faster Whisper` `EasyOCR` `PyTorch` `Google Pegasus` `Flax Arabic T5` `PyPDF2` `python-docx` `pydub` `ffmpeg` `yt-dlp` `deep-translator` `Gunicorn`

---

### [Deep Learning Projects](https://github.com/Yassin876/Deep-Learning)
> Collection of CV and generative models

| Project | Description |
|---|---|
| `ASL_YOLO` | American Sign Language detection with YOLO |
| `cnn_xray` | Chest X-ray classification with CNN |
| `covid-19` | COVID-19 detection model |
| `fake_and_real_image` | GAN-based real/fake image classifier |
| `image-genrator` | Image generation model |

---

### [Machine Learning Projects](https://github.com/Yassin876/Machine_Learning_projects)

| Project | Description |
|---|---|
| `netflix_rs` | Netflix recommendation system |
| `courses_recommendation_system` | Course recommendation engine |
| `diabetes` | Diabetes prediction classifier |
| `emails` | Email classification model |
| `defualt_classfier` | Loan default prediction |

---

### [NLP Projects](https://github.com/Yassin876/NLP)

| Project | Description |
|---|---|
| `facknews` | Fake news detection |
| `sentment_analysis` | Sentiment analysis |
| `spam_or_not` | Spam classification |
| `searching_app` | NLP-powered search application |

---

### [Data Analysis Projects](https://github.com/Yassin876/data-analysis)

| Project | Tools |
|---|---|
| Heart Disease Analysis | Python, Pandas, Matplotlib |
| Superstore Power BI Dashboard | Power BI |
| Telco Customer Churn | Python, Scikit-learn |
| Diabetes SQL Analysis | SQL, SSMS |
| Car Sales Power BI | Power BI |
| Students Analysis | Python, Pandas |

---

## Tech Stack

<div align="center">

### AI & Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/_HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

### Backend & Databases
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

### Data & Visualization
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### Frontend & Tools
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Yassin876&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=818cf8&text_color=94a3b8&include_all_commits=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yassin876&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&text_color=94a3b8&langs_count=6" height="165"/>

<br/>

![GitHub Streak](https://streak-stats.demolab.com?user=Yassin876&theme=tokyonight&hide_border=true&background=0d1117&ring=6366f1&fire=818cf8&currStreakLabel=6366f1)

</div>

---

## Courses & Certifications

| Certificate | Provider |
|---|---|
| Machine Learning (Andrew Ng curriculum) | Self-paced / YouTube |
| Deep Learning — CNNs, RNNs, Neural Networks | Self-paced / YouTube |
| AI Model Integration (FastAPI, REST API Deployment) | iSchool |
| Data Analysis — Excel, Power BI, SQL, Pandas | TARA Course |
| BCG X GenAI Job Simulation | Forage |
| BCG Financial Analysis Job Simulation | Forage |

---

## Currently

- Going deep into **LLMs** — architecture, fine-tuning, RAG systems, agents
- Building production-grade **AI backends** with FastAPI
- Exploring **model optimization** and scalable deployment
- Goal: AI Engineer building impactful AI products at scale

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0a0a0a&height=100&section=footer" width="100%"/>

*"From curiosity to code — 20+ projects and still building."*

</div>
