# AI-Powered Meeting Summarizer and Q&A Assistant

This project is an AI-driven system designed to automatically summarize meetings or lectures and allow users to query their content. It supports input from YouTube videos or plain text transcripts, returning structured summaries, insights, and answers using a Retrieval-Augmented Generation (RAG) pipeline.

## 🚀 Features

- 🎥 **YouTube Transcription** via Whisper
- 📄 **Text Transcript Support**
- 🧠 **Multi-format Summarization**
  - Bullet points
  - Numbered list
  - Executive summary
  - Highlights
- ❓ **Question Answering** using RAG
- 📄 **PDF Report Generation** with optional full transcript

## 📂 Input Types

- YouTube video URL (audio is transcribed)
- Raw transcript (text input)

## 🛠️ Technologies Used

| Component         | Technology or Library         |
|------------------|-------------------------------|
| Programming       | Python                        |
| Transcription     | Whisper via whisperx          |
| Embedding Model   | all-MiniLM-L6-v2              |
| Summarization     | flan-t5-base                  |
| Vector Store      | FAISS                         |
| QA Framework      | LangChain                     |
| Report Generation | ReportLab                     |
| Interface         | Streamlit or CLI              |

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YoussefYasserAbdelkader/AI-Powered_Meeting_Summarization_Analysis_Tool.git
   cd ai-meeting-summarizer
