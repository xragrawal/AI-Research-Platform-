# 🔬 AI Research Platform

A production-ready multi-agent AI research platform powered by **Groq's Llama-3.1-8b-instant** for comprehensive market analysis, tech stock research, and competitive intelligence.

## ✨ Features

- **🤖 Advanced AI Analysis**: Powered by Groq's ultra-fast Llama model
- **📊 Multi-Domain Research**: Market, Stock, Investment, and Technology analysis  
- **📧 Email Integration**: Professional reports sent directly to recipients
- **📈 Professional Outputs**: PowerPoint presentations and LinkedIn content
- **🎯 High Accuracy**: 85%+ confidence scores with data-driven insights
- **🌐 Professional UI**: Modern web interface with header navigation

## 🚀 Live Demo

**Streamlit Cloud:** [Coming Soon]

## 📋 Quick Start

### Local Development

1. **Clone Repository**
```bash
git clone <repository-url>
cd ai-research-platform
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Configure Environment**
```bash
cp .env.example .env
# Edit .env with your API keys
```

4. **Run Application**
```bash
streamlit run app.py
```

### Streamlit Cloud Deployment

1. **Fork this repository**
2. **Connect to Streamlit Cloud**
3. **Add secrets in Streamlit Cloud dashboard:**
   - `GROQ_API_KEY`: Your Groq API key
   - `OPENAI_MODEL`: "llama-3.1-8b-instant"
   - `SMTP_PASSWORD`: Gmail App Password (optional)

## 🔧 Configuration

### Required API Keys

- **Groq API Key**: Get from [console.groq.com](https://console.groq.com/keys)
- **Gmail App Password**: For email functionality (optional)

### Environment Variables

```bash
GROQ_API_KEY=your_groq_api_key
OPENAI_MODEL=llama-3.1-8b-instant
SMTP_PASSWORD=your_gmail_app_password
```

## 📊 Usage Examples

### Market Analysis
```
Query: "AI market trends and growth projections for 2024"
Output: Comprehensive market analysis with trends, opportunities, and forecasts
```

### Tech Stock Analysis
```
Query: "Tesla stock analysis and investment outlook"
Output: Financial analysis with recommendations and risk assessment
```

### Investment Intelligence
```
Query: "Renewable energy investment opportunities"
Output: Investment thesis with portfolio allocation recommendations
```

### AI Tools Research
```
Query: "Best machine learning platforms for enterprises"
Output: Tool comparison with implementation recommendations
```

## 🏗️ Architecture

```
Streamlit UI → Groq Llama-3.1-8b → Structured Analysis → Professional Outputs
```

### Core Components

- **AI Research Agent**: LangChain-powered analysis engine
- **Professional Outputs**: PowerPoint and LinkedIn content generation
- **Email Integration**: SMTP-based report delivery
- **Modern UI**: Professional web interface with responsive design

## 📁 Project Structure

```
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── secrets.toml          # Streamlit Cloud secrets template
├── .env.example          # Environment variables template
├── README.md             # Project documentation
└── .gitignore           # Git ignore rules
```

## 🚀 Technology Stack

- **Frontend**: Streamlit with custom CSS
- **AI Model**: Groq Llama-3.1-8b-instant
- **Document Generation**: python-pptx
- **Email Service**: SMTP (Gmail)
- **Deployment**: Streamlit Cloud

## 📧 Email Features

- **Comprehensive Reports**: Analysis + PowerPoint + LinkedIn content
- **Professional Formatting**: Business-ready email templates
- **Attachment Support**: PowerPoint files included
- **Multi-domain Support**: Gmail, Outlook, corporate emails

## 🎯 Output Formats

### PowerPoint Presentation (6 Slides)
1. Title slide with analysis overview
2. Executive summary with key metrics
3. Key findings with data points
4. Strategic recommendations
5. Detailed analysis insights
6. Next steps and contact information

### LinkedIn Post
- Optimized for social media engagement
- Professional tone with relevant hashtags
- Key insights summary
- Call-to-action for discussions

### Email Report
- Executive summary
- Complete analysis
- PowerPoint attachment
- LinkedIn content included

## 🔒 Security & Privacy

- **API Key Security**: Environment-based configuration
- **Data Privacy**: No data stored permanently
- **Secure Communication**: HTTPS and encrypted email
- **Rate Limiting**: Built-in API usage controls

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

**Developer**: Jayesh Kothavale  
**Email**: kothavalejayesh003@gmail.com  
**Version**: 1.0.0

## 📄 License

This project is licensed under the MIT License.

---

**Powered by Groq & Streamlit** | **© 2024 AI Research Platform**