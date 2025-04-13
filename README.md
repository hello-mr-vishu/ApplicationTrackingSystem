# ATS Resume Expert 🧠📄

**ATS Resume Expert** is a powerful web application built using **Streamlit** and **Google's Gemini Pro Vision API** that helps job seekers evaluate how well their resumes match a given job description.

With the help of AI, the app provides:
- **Professional feedback** on how the resume aligns with a job description.
- **Percentage match** analysis with missing keyword identification.
- Insightful strengths and weaknesses to help you improve your resume to beat ATS (Applicant Tracking Systems).

---

## 🔍 Features

- ✅ Upload your resume in PDF format.
- ✅ Paste any job description you're applying to.
- ✅ Get expert-level review and match percentage using Google Gemini Pro Vision.
- ✅ See missing keywords and personalized final thoughts on your resume's effectiveness.
- ✅ Simple and interactive UI with Streamlit.

---

## 🧠 Powered By

- [Streamlit](https://streamlit.io/) — for the interactive web app interface.
- [Google Gemini Pro Vision](https://ai.google.dev/) — for powerful resume and job description analysis.
- [pdf2image](https://github.com/Belval/pdf2image) — for converting PDF resumes into images (required for Gemini Vision model).
- [Poppler](http://blog.alivate.com.au/poppler-windows/) — required backend utility for `pdf2image`.

---

## Run the Streamlit app:
streamlit run app.py
