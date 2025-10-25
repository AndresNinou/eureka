# Learn Anything - Roadmap and Anki-style Flashcard Learning App

A comprehensive learning application that generates personalized roadmaps and interactive flashcard systems to help users learn any topic effectively.

## Features

### 🎯 Core Learning Features
- **Personalized Learning Roadmaps**: Generate custom learning paths with modules, milestones, and resources
- **Anki-style Flashcard System**: Interactive flashcards with spaced repetition and progress tracking
- **Learning Dashboard**: Comprehensive progress tracking and session management
- **Multi-source Content Integration**: YouTube videos, academic papers, books, and articles

### 🛠️ Technical Implementation
- **Backend**: FastAPI with MCP server architecture
- **Frontend**: Modern HTML5 with CSS3 animations and responsive design
- **Integrations**: YouTube Data API, academic search, content extraction
- **Async Processing**: Full async/await implementation for performance

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- uv package manager
- Dependencies listed in requirements.txt

### Installation
```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
cd learn_anything_app
uv sync

# Run the application
uv run python main.py
```

### Deployment
The application runs on port 9000 and can be accessed via Cloudflare tunnel for ChatGPT integration.

## 📚 App Structure

```
learn_anything_app/
├── main.py                 # Main MCP server application
├── youtube_integration.py    # YouTube video search and integration
├── content_extraction.py   # PDF/book/article content extraction
├── assets/                  # Frontend HTML components
│   ├── learning-roadmap.html
│   ├── flashcard-session.html
│   └── learning-dashboard.html
├── pyproject.toml           # Project configuration
├── requirements.txt          # Python dependencies
└── README.md               # This file
```

## 🔧 MCP Tools

### 1. Generate Learning Roadmap
- **Input**: Topic, current level, learning style, time commitment
- **Output**: Personalized roadmap with modules, resources, milestones

### 2. Start Flashcard Session
- **Input**: Topic, difficulty, card count
- **Output**: Interactive flashcard interface with progress tracking

### 3. Learning Dashboard
- **Input**: User ID (optional)
- **Output**: Progress stats, recent sessions, achievements

## 🎨 UI Features

### Roadmap Interface
- Gradient backgrounds and modern design
- Interactive resource cards with thumbnails
- Progress bars and milestone tracking
- Responsive design for all devices

### Flashcard Interface
- 3D flip animations
- Color-coded difficulty indicators
- Real-time progress tracking
- Keyboard shortcuts support
- Session completion analytics

### Dashboard Design
- Animated statistics cards
- Achievement badges
- Visual progress indicators
- Interactive session management

## 🌐 Integration Capabilities

### YouTube Integration
- Educational video search and integration
- Video metadata extraction (duration, views, likes)
- Embeddable video URLs
- Content filtering by duration and relevance

### Content Extraction
- Academic paper search and integration
- Book search with metadata
- PDF and article content extraction
- Key concept identification
- Study question generation from content

## 📱 Usage in ChatGPT

1. **Generate Roadmap**: "Create a learning roadmap for [topic]"
2. **Flashcard Session**: "Start flashcard practice for [topic]"
3. **Dashboard**: "Show my learning progress"

The app provides personalized learning experiences with beautiful, modern interfaces that make learning engaging and effective!
