# 🤖 AI Resume Analyzer using n8n

An AI-powered Resume Analyzer workflow built using **n8n**, **Google Gemini AI**, and **PDF Extraction**. This workflow automatically extracts text from uploaded resumes, analyzes ATS compatibility, and provides detailed improvement suggestions.

## 🚀 Features

- 📄 Upload resumes in PDF format
- 🤖 AI-powered ATS resume analysis
- 📊 Generate ATS Score (0–100)
- ✅ Identify resume strengths
- ❌ Detect weaknesses
- 💡 Suggest improvements for better ATS compatibility
- 🧠 Google Gemini AI-powered feedback
- 💾 Conversation memory support

## 🛠️ Technologies Used

- n8n
- Google Gemini API
- AI Agent
- Extract from File Node
- Form Trigger
- Simple Memory

## 📂 Project Files

- `AI Resume Analyzer.json` – Complete n8n workflow

## ⚙️ Workflow

```
Form Submission
       │
       ▼
Extract Resume from PDF
       │
       ▼
Google Gemini AI Agent
       │
       ▼
ATS Score + Feedback + Suggestions
```

## ▶️ How to Use

1. Import `AI Resume Analyzer.json` into n8n.
2. Configure your Google Gemini API credentials.
3. Execute the workflow.
4. Upload a resume in PDF format.
5. Receive ATS analysis with improvement suggestions.

## 📈 Sample Output

- ATS Score
- Resume Strengths
- Weaknesses
- Missing Skills
- Improvement Suggestions
- Final Verdict

## 🔮 Future Improvements

- DOCX Resume Support
- Google Drive Integration
- Email Report Generation
- Resume Keyword Optimization
- LinkedIn Profile Analysis
- Multi-language Resume Support

  ## 📸 Workflow Screenshot

![Workflow](./AI%20Resume%20Analyzer.png)

 
## 👨‍💻 Author

**Ansh Thakare**


