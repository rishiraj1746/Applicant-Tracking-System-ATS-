# 📌 Applicant Tracking System (ATS)

## 📝 Introduction
The **Applicant Tracking System (ATS)** is an AI-powered tool designed to streamline the hiring process by automating resume screening. This project helps recruiters efficiently filter and rank candidates based on job descriptions by extracting and analyzing key resume details. With AI-powered keyword matching and resume parsing, ATS significantly reduces manual effort in the hiring process.

## 🚀 Project Overview
Recruitment is often time-consuming, requiring HR professionals to manually go through resumes. Our ATS solves this problem by:
- **Extracting** text and key details from resumes (PDF format).
- **Analyzing** candidate information using AI.
- **Matching** resumes against job descriptions using keyword-based ranking.
- **Providing insights** into candidate suitability.

## 🔹 Features
✅ **Resume Parsing** – Extracts text and key details from PDFs using `pdf2image` and `PyMuPDF`.
✅ **AI-Powered Analysis** – Uses Google Gemini API for resume assessment.
✅ **Keyword Matching** – Compares resumes against job descriptions.
✅ **User-Friendly Interface** – Simple and interactive UI for easy access.
✅ **Automated Scoring** – Assigns candidate suitability scores.
✅ **Future Scalability** – Supports enhancements like machine learning ranking.

## 📂 Project Structure
```
📦 ATS
 ├── 📜 app.py              # Main application script
 ├── 📜 requirements.txt    # Dependencies list
 ├── 📜 resume_parser.py    # PDF to text conversion and data extraction
 ├── 📜 ats_utils.py        # Resume analysis and keyword matching
 ├── 📜 README.md           # Project Documentation
```

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ATS.git
cd ATS
```
### 2️⃣ Install Dependencies
Ensure you have **Python 3.8+** installed. Then, install the required packages:
```bash
pip install -r requirements.txt
```
### 3️⃣ Install Poppler for PDF Processing
Poppler is required for PDF parsing. Install it and add it to the system **PATH**:
- **Windows**: Download Poppler from [this link](https://github.com/oschwartz10612/poppler-windows/releases) and set the PATH.
- **Linux/macOS**: Install via package manager:
  ```bash
  sudo apt install poppler-utils  # Ubuntu
  brew install poppler  # macOS
  ```

### 4️⃣ Run the Application
```bash
streamlit run app.py
```

## 📌 How It Works
1️⃣ **Upload Resume (PDF)** – The system extracts text and key details from resumes.
2️⃣ **Provide Job Description** – Enter the job description for comparison.
3️⃣ **AI Processing** – The ATS evaluates and matches resumes against job criteria.
4️⃣ **Ranking & Output** – Displays best-matched candidates based on keyword matching and AI insights.

## 🔮 Future Enhancements
🔹 **ML-Based Resume Ranking** – Use machine learning models for intelligent scoring.
🔹 **Data Visualization** – Provide analytics on candidate trends.
🔹 **Multi-Format Support** – Expand support beyond PDFs to DOCX and TXT.

## 🤝 Contributions
Contributions are welcome! Feel free to fork, raise issues, or submit pull requests.

---

This ATS is designed to make **hiring smarter, faster, and more efficient**. 🚀

