Perfect — I’ve updated the README to include proper co-authorship and attribution. Here’s your finalized version:

---

# 🧾 cb-candidateAssessment-tool

### 📋 Overview

**cb-candidateAssessment-tool** is a lightweight candidate evaluation prototype built during an OJT project at **Callbox** by interns **John Lynzee Plaza** and [**xymontroy**](https://github.com/xymontroy). It serves as a custom frontend wrapper for a Google Form, designed to streamline applicant data collection and assist recruiters in role matching.

Although the project was later discontinued in favor of a more scalable solution, this tool remains functional and demonstrates practical integration between Google Forms, Google Sheets, and Google Apps Script for backend processing.

---

## 🚀 What It Does

- 🧩 Recreates a simplified version of a Google Form using custom HTML/CSS
- 📤 Submits applicant responses directly to a Google Sheet linked to the original form
- 🧠 Processes submitted data using **Google Apps Script** to recommend **three possible roles**
- 🔒 Role recommendations are visible **only to the recruiter team** (not to the applicant)

---

## 🧠 Role Matching Criteria

The system analyzes applicant data based on:

- Personal Information  
- Educational Background  
- Qualifications  
- Technical Skills  
- Industry Experience  

Using rule-based logic and keyword matching, it suggests up to **three roles** the applicant may be qualified for. These recommendations are stored in the recruiter’s Google Sheet and are **not visible to the applicant**. Recruiters may choose to share them manually.

---

## 🛠️ Tech Stack

| Layer      | Tools Used |
|------------|------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | Google Apps Script |
| Integration| Google Forms + Google Sheets |

---

## 📦 Project Status

⚠️ **Archived** — This tool was part of an OJT initiative and is no longer actively maintained. It was replaced by a more robust internal system, but the logic and integration still work for small-scale use or prototyping.

---

## 👨‍💻 Authors

| Name               | Role                  |
|--------------------|-----------------------|
| John Lynzee Plaza  | Frontend & Integration |
| [xymontroy](https://github.com/xymontroy) | Backend & Apps Script |
