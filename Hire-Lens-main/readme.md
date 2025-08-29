# HireLens: AI-Powered Resume Analysis 📄✨

## OverviewOverview

HireLens is a smart resume evaluation platform powered by AI that helps job seekers enhance their profiles. It checks resumes for ATS (Applicant Tracking System) compatibility, highlights missing keywords, and even offers insights into candidate personality traits to improve hiring prospects.

Built with Python and Streamlit, HireLens delivers a seamless, interactive web experience for users.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.20+-green)
![AI Powered](https://img.shields.io/badge/AI-Powered-orange)

## Features

- 🤖 ATS Score Analysis
- 🧠 Candidate Personality Insights
- 📌 Missing Keywords Detection
- 📑 PDF Resume Support
- 💻 User-Friendly Web Interface

## Prerequisites

- Python 3.8+
- Streamlit
- Google Gemini API Access

## Installation

1. Clone the repository:
```bash
https://github.com/ishita250104/ATS_checker.git
cd app
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Environment Configuration

Create a `.env` file in the project root with the following variables:

```env
# Google Gemini API Configuration
GOOGLE_API_KEY=your_gemini_api_key_here

# PDF Processing Settings
POPPER_DIRECTORY_PATH =/path/to/popper/Library/bin

```

### API Key Setup

1. Go to Google AI Studio

2. Generate a new API key for Gemini

3. Add it to your .env file

## Running the Application

```bash
streamlit run app.py
```


## How To Use

1. Open the web interface
2. Paste a job description
3. Upload your resume (PDF format)
4. Select analysis type:
   - ATS Score
   - Personality Profile
   - Missing Keywords
   

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

