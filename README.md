# 🔍 The Circumstance-to-Context (C2C) Analyzer App

### A Web-Based Pedagogical Tool for Systemic Functional Analysis of Prepositional Circumstances in Newspaper Crime Reports

---

## 🎓 Academic Framework & Research Context
This interactive web tool is developed as a practical component of a PhD pedagogical model. 

* **Thesis Topic:** Systemic Functional Analysis of Prepositional Circumstances in Selected Newspapers' Crime Reports: Discourse Representation and Implications for ESL Grammar Pedagogy.
* **Theoretical Foundations:** Systemic Functional Linguistics (SFL) via M.A.K. Halliday's Ideational Metafunction, Critical Discourse Analysis (CDA), and Communicative Language Teaching (CLT).
* **Target Audience:** Advanced ESL Learners, Applied Linguistics Researchers, and Language Teachers.

### Research Objective
In traditional ESL pedagogy, prepositions are often taught purely through rote memorization or basic spatial decoding (e.g., "the book is *on* the table"). This tool operationalizes a functional shift. It scaffolds learners to see how journalists use prepositional phrases as **circumstances** to strategically construct ideological bias, shift blame, alter agency, or create sensationalism in crime reporting.

---

## 🛠️ App Structure & Pedagogical Workflow
The web application splits the critical reading process into three clear, actionable phases for the student:

1. **Phase 1: Experiential Input:** The learner inputs an authentic crime report excerpt from a selected newspaper.
2. **Phase 2: SFL Mapping Matrix:** The learner isolates up to three prepositional phrases, classifies them using SFL taxonomy (Spatial, Temporal, Manner, Cause, etc.), and writes a qualitative analysis explaining what the choice emphasizes or obscures.
3. **Phase 3: Pedagogical Grammar Manipulation (Theme Shifting):** The student manipulates the syntax by moving a circumstance to the front of the sentence (Theme position) or deleting it entirely to visually observe how structural changes alter the ideological message.

---

## 💻 Technical Setup & Environment

This application is built using **Python** and **Streamlit**. It requires no heavy local installation and is optimized for free, low-code deployment on the web via Streamlit Community Cloud.

### Files in this Repository:
* `app.py`: The core backend script containing the layout, design architecture, and user inputs.
* `requirements.txt`: Specifies the necessary library dependency (`pandas`) needed to generate the student's output matrix table.
* `README.md`: This file, outlining the pedagogical context and usage guide.

---

## 🚀 How to Run the App Locally (For Researchers/Developers)

If you wish to clone this repository and run it locally on your computer rather than using the web version, follow these steps:

1. **Clone the repository:**
```bash
   git clone [https://github.com/YOUR_USERNAME/sfl-tool.git](https://github.com/YOUR_USERNAME/sfl-tool.git)
   cd sfl-tool
