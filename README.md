# 📄 ATS-Friendly LaTeX Resume — Parth Deshpande

A clean, modern, and 100% **ATS-friendly LaTeX resume** engineered for Software Engineering, AI/ML, and Computer Science undergraduates. Built using clean TeX formatting for crisp typesetting, machine-readability, and effortless customization.

[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=LaTeX&logoColor=white)](https://www.latex-project.org/)
[![Overleaf Ready](https://img.shields.io/badge/Overleaf-Ready-47A141?style=for-the-badge&logo=Overleaf&logoColor=white)](https://www.overleaf.com/)
[![ATS Friendly](https://img.shields.io/badge/ATS-Optimized-blue?style=for-the-badge)](https://github.com/Parth-bot-crypto26/Resume_VIT)

---

## 🌟 Key Features

- 🎯 **ATS-Optimized**: Uses `glyphtounicode` & `pdfgentounicode=1` to ensure perfect machine readability by Applicant Tracking Systems.
- 📐 **Compact Single-Page Layout**: Perfectly balanced margins and spacing tailored for undergraduate & early-career software developers.
- 🎨 **Minimalist & Professional**: Clear section headers, horizontal dividers, and crisp font hierarchy.
- ⚡ **Overleaf & Local Compatible**: Compiles seamlessly with `pdflatex`, `xelatex`, or on Overleaf without extra dependencies.
- 🔗 **Interactive Links**: Clean, un-cluttered hyperlink integration for GitHub, LinkedIn, and email via `hyperref`.

---

## 📑 Resume Structure

```text
├── Header             # Name, Phone, Email, LinkedIn, GitHub
├── Education          # Degree, University, High School, GPA & Board Percentages
├── Technical Skills   # Categorized by Languages, AI/ML, Web Dev, Databases, & Tools
├── Projects           # Bulleted project breakdowns with Tech Stack & Metrics
├── Achievements       # Hackathons, Competitive Programming, & Program Selections
└── Certifications     # Cloud, AI, and Specialization certifications
```

---

## 🚀 How to Use / Compile

### Option 1: Overleaf (Recommended)
1. Download or copy `resume.tex` from this repository.
2. Go to [Overleaf](https://www.overleaf.com/) and create a **Blank Project**.
3. Paste the contents into `main.tex` and click **Recompile**.
4. Download your compiled PDF!

### Option 2: Local Compilation (Command Line)
Make sure you have TeX Live / MiKTeX installed:

```bash
# Clone the repository
git clone https://github.com/Parth-bot-crypto26/Resume_VIT.git
cd Resume_VIT

# Compile using pdflatex
pdflatex resume.tex
```

---

## 🛠️ Personalization

To adapt this template for your own profile:
1. Open `resume.tex`.
2. Update the contact info in the `%----------HEADING----------` section.
3. Edit the sections (`Education`, `Technical Skills`, `Projects`, `Achievements`, `Certifications`) under their respective `\section{}` blocks.
4. Recompile!

---

## 👤 Author

**Parth Deshpande**
- 🌐 Portfolio: [parth-portfolio-beryl.vercel.app](https://parth-portfolio-beryl.vercel.app/)
- 💻 GitHub: [@Parth-bot-crypto26](https://github.com/Parth-bot-crypto26)
- 💼 LinkedIn: [parth-deshpande](linkedin.com/in/parth-deshpande-93578027b)

---

⭐ *If you find this resume template helpful, feel free to give this repository a star!*
