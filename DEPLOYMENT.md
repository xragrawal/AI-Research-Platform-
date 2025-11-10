# 🚀 Deployment Guide

## GitHub Setup

1. **Create GitHub Repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name: `ai-research-platform`
   - Description: `Production-ready multi-agent AI research platform powered by Groq`
   - Make it public for Streamlit Cloud

2. **Upload Files**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: AI Research Platform"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/ai-research-platform.git
   git push -u origin main
   ```

## Streamlit Cloud Deployment

1. **Connect to Streamlit Cloud**
   - Go to [share.streamlit.io](https://share.streamlit.io)
   - Sign in with GitHub
   - Click "New app"

2. **App Configuration**
   - **Repository**: `YOUR_USERNAME/ai-research-platform`
   - **Branch**: `main`
   - **Main file path**: `app.py`
   - **App URL**: Choose your custom URL

3. **Add Secrets**
   In Streamlit Cloud dashboard, go to "Secrets" and add:
   ```toml
   GROQ_API_KEY = "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"
   OPENAI_MODEL = "llama-3.1-8b-instant"
   SMTP_PASSWORD = "dvtwgcwdyspudcrf"
   ```

4. **Deploy**
   - Click "Deploy"
   - Wait for deployment to complete
   - Your app will be live at: `https://YOUR_APP_NAME.streamlit.app`

## Environment Variables

The app uses these environment variables:
- `GROQ_API_KEY`: Required for AI analysis
- `OPENAI_MODEL`: Model name (llama-3.1-8b-instant)
- `SMTP_PASSWORD`: Gmail App Password for email functionality

## Features Available

✅ AI-powered research analysis
✅ PowerPoint generation and download
✅ LinkedIn post creation
✅ Email delivery with attachments
✅ Professional web interface
✅ Mobile responsive design

## Support

For issues or questions:
- **Developer**: Jayesh Kothavale
- **Email**: kothavalejayesh003@gmail.com