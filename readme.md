# Phidata Video AI Summarizer Agent 🎥🎤🖬

A powerful video analysis tool powered by Google's Gemini 2.0 Flash Exp that provides AI-driven insights and summaries from video content.

## Features

- 🎥 Video Upload & Processing
- 🤖 AI-Powered Video Analysis
- 🔍 Context-Aware Responses
- 🌐 Web Research Integration
- 📝 Detailed Insights Generation

## Prerequisites

- Python 3.8+
- Google API Key (Gemini API access)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd phidata-video-summarizer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root and add your Google API key:
```
GOOGLE_API_KEY=your_api_key_here
```

## Usage

1. Start the application:
```bash
streamlit run app.py
```

2. Open your browser and navigate to the provided local URL (typically http://localhost:8501)

3. Upload a video file (supported formats: MP4, MOV, AVI)

4. Enter your query about the video content

5. Click "Analyze Video" to get AI-generated insights

## Features Breakdown

- **Video Processing**: Handles various video formats and processes them for AI analysis
- **Multimodal Analysis**: Utilizes Gemini 2.0 for comprehensive video understanding
- **Web Research**: Integrates DuckDuckGo search for additional context
- **Interactive UI**: User-friendly Streamlit interface for easy interaction
- **Temporary File Management**: Secure handling of uploaded videos

## Dependencies

- phidata
- streamlit
- google-generativeai
- python-dotenv
- duckduckgo-search
- (and other requirements as listed in requirements.txt)

## Environment Variables

- `GOOGLE_API_KEY`: Your Google API key for Gemini access

## Limitations

- Video file size may be limited by Streamlit's upload constraints
- Processing time depends on video length and complexity
- Requires stable internet connection for API calls




## Acknowledgments

- Built with [Phidata](https://github.com/phidatahq/phidata)
- Powered by Google's Gemini 2.0 Flash Exp
- Uses Streamlit for the web interface