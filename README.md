# ⚡AI Resume Analyzer

**AI-powered resume analysis that delivers insights at lightning speed!**  
This project extracts key details from resumes, evaluates job suitability, and provides career advice using advanced AI models. 
**Optimized for bulk processing** via a folder-based approach, eliminating slow UI interactions.  

---

## Key Features  
 **Bulk Resume Processing** – Analyze multiple resumes from a folder (`resume/`) for faster results.  
 **AI-Powered Analysis** – Extracts **skills, experience, education, job roles, and career advice**.  
 **Structured Insights** – Generates **JSON-based outputs** for easy interpretation.  
 **PDF Reports** – Generates a **detailed AI-driven report** for each resume.  
 **Multiple UI Options** – Includes **Gradio & Streamlit** implementations.  

---

## Repo Structure  
```plaintext
AI-Resume-Analyzer-Fast/
│── resumes/                 # folder containing resumes (PDFs)  
│── notebook.ipynb          # main Notebook (Gradio, Streamlit, and Folder Processing)  
│── requirements.txt        # dependencies  
│── README.md               # you're reading now - hehe
```

## 🛠 Technologies Used 🤖
- Python 
- OpenAI/Groq API
- PyMuPDF (Text extraction from PDFs) 
- NLTK (Natural Language Processing) 
- Gradio & Streamlit (UI frameworks) 
- ReportLab (PDF generation)

## ⚙ Installation & Setup  

### Clone the Repository  
```bash
git clone https://github.com/vinabi/AI-Powered-Resume-Screening-System.git
cd AI-Powered-Resume-Screening-System
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
### How to Use?
Fastest Mode: Bulk Resume Analysis
```notebook.py```
*Put all resumes in the `resumes/` folder before running!*

### Features
- Gradio UI (Slower)
- Streamlit UI (Alternative UI)
- Generates Analysis PDF report.

Open the link in your browser to upload and analyze resumes (for gradio and streamlit).

---

####  If you find this project helpful, don’t forget to star the repo! 🎀
