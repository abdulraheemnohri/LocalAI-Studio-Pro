# 🧠 LocalAI Studio Pro

> **Private AI Workspace — Runs Fully in Browser (Offline-First)**
> 
## 🎯 Overview

LocalAI Studio Pro is a self-hosted, browser-based AI platform that runs **100% offline** in your web browser. It's your private AI workspace with chat, file intelligence, code assistance, and knowledge training capabilities—all without sending any data to external servers.

### 🌟 Key Features

- ✅ **Offline AI Models** - No API calls, no data leaves your browser
- ✅ **Multiple AI Modes** - Chat, Code, PDF, Image, and Training
- ✅ **File Intelligence** - Upload and analyze documents (TXT, PDF, code files)
- ✅ **Knowledge Base** - Train AI on your own documents
- ✅ **Code Assistance** - Generate, explain, and debug code
- ✅ **PDF Intelligence** - Summarize and query PDF documents
- ✅ **Image Analysis** - Generate captions for images
- ✅ **Voice Input** - Speak naturally to your AI assistant
- ✅ **Modern Glass UI** - Sleek, responsive design with Glassmorphism
- ✅ **Settings Panel** - Customize AI behavior and manage data

---

## 🚀 Quick Start

### Option 1: Run Locally (Recommended)

```bash
# Clone the repository
git clone https://github.com/abdulraheemnohri/LocalAI-Studio-Pro.git
cd LocalAI-Studio-Pro

# Open index.html directly in your browser
# Or use a local server:
python -m http.server 8000

# Then open: http://localhost:8000
```


## 🧩 AI Modes Explained

### 1. 💬 Chat Mode
General conversational AI with context awareness.

**Use Cases:**
- General Q&A
- Brainstorming ideas
- Learning new topics
- Personal assistance

### 2. 💻 Code AI Mode
Expert code assistant with multi-language support.

**Features:**
- Generate clean, well-documented code
- Explain existing code
- Debug and optimize code
- Multi-language support (JavaScript, Python, HTML, CSS, etc.)

**Supported Languages:**
```
JavaScript (JS), Python (PY), HTML, CSS, JSON, Markdown (MD)
```

### 3. 📄 PDF Intelligence Mode
Upload and analyze PDF documents.

**Features:**
- PDF text extraction
- Document summarization
- Query PDF content
- Chunk-based context retrieval

**Supported:**
- PDF files (.pdf)

### 4. 🖼️ Image AI Mode
Upload images for analysis and caption generation.

**Features:**
- Image captioning
- Object detection (basic)
- Scene description
- Visual analysis

**Supported:**
- JPG, JPEG, PNG (.jpg, .jpeg, .png)

### 5. 📚 Train AI Mode
Build your custom knowledge base.

**Features:**
- Upload training files (TXT, PDF, code)
- Chunk text for efficient retrieval
- Context-aware responses
- Persistent knowledge storage

**Supported File Types:**
```
- Text: .txt
- PDF: .pdf
- Code: .js, .py, .html, .css, .json, .md
```

---

## 📁 File Support

| File Type | Extension | Description |
|-----------|-----------|-------------|
| **Text** | `.txt` | Plain text documents |
| **PDF** | `.pdf` | Portable Document Format |
| **JavaScript** | `.js` | JavaScript files |
| **Python** | `.py` | Python scripts |
| **HTML** | `.html` | HTML documents |
| **CSS** | `.css` | Cascading Style Sheets |
| **JSON** | `.json` | JSON configuration files |
| **Markdown** | `.md` | Markdown documentation |
| **Images** | `.jpg`, `.jpeg`, `.png` | Image files for analysis |

---

## ⚙️ Technical Details

### Frontend Stack
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Glassmorphism
- **Vanilla JavaScript** - No framework overhead
- **Transformers.js** - On-device AI models
- **PDF.js** - PDF parsing in browser
- **Highlight.js** - Code syntax highlighting

### AI Models
| Task | Model | Size | Description |
|------|-------|------|-------------|
| **Text Generation** | `Xenova/LaMini-Flan-T5-783M` | 783M | Recommended model for chat and code |
| **Text Generation (Small)** | `Xenova/flan-t5-small` | 80M | Faster, less accurate |
| **Text Generation (Basic)** | `Xenova/gpt2` | 124M | Basic text completion |
| **Image Captioning** | `Xenova/vit-gpt2-image-captioning` | 184M | Describe images in detail |

### Storage
- **IndexedDB** - Persistent browser storage
- **localStorage** - Fallback for small data
- **Zero external storage** - All data stays in your browser

### Privacy Model
```
✅ 100% Offline Processing
✅ No API Calls
✅ No Data Transmission
✅ No External Tracking
✅ No User Accounts Needed
```

---
