# YouTube Summarizer

An AI-powered web application that generates concise and meaningful summaries of YouTube videos using advanced natural language processing techniques. This tool enhances productivity by saving users time and effort in understanding the key points of video content.

---

## ✨ Features

- **Automatic Summarization**: Generates video summaries by analyzing transcripts and metadata using AI.  
- **YouTube Video URL Integration**: Users can input video links to extract and summarize content effortlessly.  
- **Multi-Language Support**: Summarizes content in various languages for global accessibility.  
- **Customizable Summary Length**: Allows users to choose short, medium, or detailed summaries based on their needs.  
- **Keyword Extraction**: Highlights essential keywords and phrases for quick reference.  

---

## 🔧 Tech Stack

- **Frontend**:  
  - Streamlit for building an interactive and user-friendly interface.  

- **Backend**:  
  - Python for processing and API integration.  
  - YouTube Data API for video data retrieval.  
  - Natural Language Processing models for text analysis and summarization (e.g., Hugging Face transformers).  

- **AI Models**:  
  - GPT-based summarization models for generating accurate and concise summaries.  

---

## 🚀 How It Works

1. **Input YouTube URL**: Users provide a video link through the application interface.  
2. **Transcript Analysis**: The app extracts the video's transcript using the YouTube Data API.  
3. **Summarization Process**: AI models analyze the transcript and generate a summary tailored to the user's preferred length.  
4. **Display Results**: The summary and extracted keywords are presented in an intuitive format for quick comprehension.  

---

## 💻 Installation

### Prerequisites  
- Python 3.8+  
- Streamlit  
- Access to YouTube Data API  

### Steps  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/Ratnendra-creates/youtubesummarizer.git  
   cd youtubesummarizer  
   ```  

2. Install required libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Set up your API key:  
   - Obtain an API key from the [YouTube Data API](https://console.cloud.google.com/apis/).  
   - Add it to a `.env` file in the project directory:  
     ```  
     YOUTUBE_API_KEY=your_api_key_here  
     ```  

4. Run the application:  
   ```bash  
   streamlit run app.py  
   ```  

5. Access the app on your browser at `http://localhost:8501`.  

---

## 📈 Use Cases

- Quickly understand long educational or informational YouTube videos.  
- Extract key points from interviews, podcasts, and seminars.  
- Enhance research efficiency by summarizing video content.  





