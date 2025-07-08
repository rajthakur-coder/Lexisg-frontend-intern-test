# Lexisg Frontend Intern Test – Legal Assistant Interface with Citations

This project is a simulated frontend interface for a **Lexi-like legal assistant**. The app mimics an AI-powered legal query system that provides answers with verifiable legal citations, referencing paragraphs inside real legal documents (PDFs).


## 🌐 Live Demo

Check out the live demo here:  
👉 [Lexi Legal Assistant – Live App](https://lexisgfrontend.netlify.app/)


## 🚀 Features

- Ask a legal question via input panel
- Simulated AI-generated answer
- Citation displayed below the answer
- Clickable citation opens PDF in a popup (or new tab)
- Simulated highlight of specific paragraph in the PDF (bonus UI)
- Styled with modern UI (chat-like interface)

---

## 🧠 Simulation Logic

On form submission, a **mock API response** is returned containing:
- The legal answer
- Citation details with a source PDF link

Example simulated query:

> “In a motor accident claim where the deceased was self-employed and aged 54–55 years at the time of death, is the claimant entitled to an addition towards future prospects in computing compensation under Section 166 of the Motor Vehicles Act, 1988?”

---

## 📸 Screenshot

Below is a sample screenshot of the Lexi Legal Assistant Interface:


![Screenshot 2025-07-08 224730](https://github.com/user-attachments/assets/7240efb3-7371-4878-891d-b31194036e13)




![Screenshot 2025-07-08 224842](https://github.com/user-attachments/assets/37a70bdd-6605-4138-8c7c-37b7944d2b90)



![Screenshot 2025-07-08 224814](https://github.com/user-attachments/assets/edd7a46e-50c5-4983-86a6-b30da501219b)



## 🖥️ Tech Stack

- React.js (Vite + React or CRA)
- Tailwind CSS (for optional styling)
- No backend required (simulated logic only)
- PDF popup handled using `react-pdf` or native browser tab

---

## 🛠️ Setup Instructions

### Run Locally

```bash
git clone (https://github.com/rajthakur-coder/Lexisg-frontend-intern-test.git)
cd lexisg-frontend-intern-test
npm install
npm start
