# 🏠 AI-Powered Rent vs Buy Financial Advisor (UK Edition)

> A full-stack web application that helps users in the UK make informed housing decisions by comparing renting vs buying through personalized, explainable AI-powered financial analysis.

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
![Made with React](https://img.shields.io/badge/Made%20with-React-blue)
![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-yellow)
![Flask](https://img.shields.io/badge/Backend-Flask-lightgrey)
![Vertex AI](https://img.shields.io/badge/AI-Google%20Vertex%20AI-red)

---

## 📌 Table of Contents

- [Overview](#overview)  
- [Key Features](#key-features)  
- [Live Demo](#live-demo)  
- [Tech Stack](#tech-stack)  
- [System Architecture](#system-architecture)  
- [Installation & Setup](#installation--setup)  
- [Usage Guide](#usage-guide)  
- [Known Limitations](#known-limitations)  
- [Planned Features](#planned-features)  
- [Contributors](#contributors)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  
- [Academic Note](#academic-note)

---

## 🧠 Overview

This project addresses the need for smarter rent vs buy decision-making tools in the UK by combining robust financial models with conversational AI.

Unlike traditional calculators, this tool adapts to personal financial inputs, explains outcomes in natural language, and allows users to simulate future housing scenarios with transparency and ease.

---

## ✨ Key Features

- 🔄 **Dynamic Rent vs Buy Comparisons** using real-time user inputs  
- 💬 **Conversational AI Assistant** powered by Google PaLM 2 (Vertex AI)  
- 📊 **Visual Cost Breakdown** of long-term ownership vs renting  
- 💡 **Explainable AI** responses tailored to financial literacy needs  
- 📐 **UK-specific Modelling**: stamp duty, council tax, rent inflation  
- 🔐 **Secure Backend** using Flask with environment-based credential management  
- 🧪 **Tested for Accuracy** within ±1% of spreadsheet-grade calculations

---

## 🚀 Live Demo
  
🔗 [GitHub Repository](https://github.com/your-username/rent-vs-buy-analysis)

> ⚠️ *Ensure the app is deployed and repo is public or access-enabled.*

---

## 🧰 Tech Stack

| Layer        | Technology                  |
|--------------|-----------------------------|
| Frontend     | ReactJS, Bootstrap 5, CSS   |
| Backend      | Flask (Python), REST APIs   |
| AI Assistant | Google PaLM 2 via Vertex AI |
| Testing      | `pytest`, `unittest`, Postman |
| Deployment   | Vercel (frontend), Render (backend) |
| Design Tools | Figma (UI/UX prototyping)   |

---

## 🏗️ System Architecture

<!-- You can embed the PNG or link to a PlantUML-rendered image here -->
![System Architecture](https://www.plantuml.com/plantuml/png/VLF1RjD04BtlLunwGCuXGkBO0sfQafAgXU3GNY12KtjmLbtlMhFZf152uX_uGxw4MSTDwWfnIRGxyzwRztPip5aKP6bh1pbvkOldxMwvYqArCMB54KpcuqNO4bFPTS0cWlR0p7hqXKK7at9ZOs3uy-itxA4muM9jXGffcOp1GhHy6ucDIRym7h-56GSlv4iuXQaNuWZV3umb2dxrhy2cWg8ZRAsieLYZt0Sn1sZYESVYOK-pr3zb2Lnt1B2n2Fbq-HacYpbahmjqHUjGQ6GIfiSVVKnzPJqfpqMecrOe0lTsxzLkBCWZsn3DIy1mY9pKitzkvfu97ygmzP1TBJz-69d_przJZ5WHID3aNtf82Gp6rvvlDw5itNvm7uNRb5V3Qa9IXh5ZLROxOg77H9ejyFe6tepC4QnKVOFMJ-5JIxphGk-PpA7uKZIdsAWkGTOuj7wigJWRrq2FUlOeDlY1qC3oB72DacRYdcPWhW_gc6jQneeyCGgLWBfu1HdJA2H5TdBeptB2GgwMenFuOG2-p7tJIgUsIiUB_IB1xRmxgeNMIOHSeSJ4A_Fp6UdJGDdCONn83_74ceTMw1IEcxKQtAf8Tp5b3WplqPVE-cf8VloA-ctA5ZjP1_yaSHDOgjHvqMi4xaVs0jEeobt2eEcIwofBmRg1Twtiu3fKjbZj_MyeIfr0bnosiXvEeVbFOhHHq4illEYU_RXIlUvb29MZV-nIHtYcERMrCty1)

---

## ⚙️ Installation & Setup

### 📦 Prerequisites

- Node.js ≥ 14.x  
- Python ≥ 3.8  
- Google Cloud API credentials for Vertex AI  
- Vercel / Render accounts (for deployment)

### 🖥️ Local Setup

#### 1. Clone the repository

## Set up the backend
- cd backend
- python main.py

## Set up the frontend:
- cd frontend
- npm install
- npm start

## 🧪 Usage Guide

1. Open the application in your browser (e.g., [http://localhost:3000](http://localhost:3000)).
2. Enter your:
   - Monthly rent
   - Property price and deposit
   - Mortgage rate, term, and related ownership costs
   - Expected investment return if renting
3. Click **"Calculate"** to generate a side-by-side, year-by-year financial comparison.
4. Use the **chat assistant** to receive clear, AI-generated explanations of the results and related financial concepts.
5. Adjust values to test new scenarios, such as different timeframes, property values, or financial strategies.

> 💡 Tip: Use the chatbot to explore *"what if I..."* questions like:
> - "What if rent grows faster than inflation?"
> - "How much would I save by investing instead of buying?"

---

## 🧭 Known Limitations

Despite delivering a functional and educational prototype, the current system has several limitations:

- 🔐 **No login or saved scenarios**: User data is not stored; session is temporary.
- 🧾 **Simplified tax logic**: Does not yet account for capital gains tax, remortgaging, or income from letting.
- 📉 **No live API integrations**: Property price, rent inflation, and mortgage data are entered manually.
- 📊 **Limited data visualizations**: Results are shown in text only; graphs and timelines are not yet implemented.
- 🤖 **AI model limitations**: In rare cases, AI responses may be overly generic or slightly repetitive.

---

## 🌱 Planned Features

To extend functionality and user value, the following improvements are planned:

- 🔗 **Real-time APIs** for Rightmove, Zoopla, and Bank of England mortgage rates
- 📈 **Graph-based visualizations** for:
  - Rent vs buy breakeven timelines
  - Net equity growth over time
  - Investment return vs homeownership
- 👤 **User authentication** with saved scenario history and dashboards
- 🌍 **International adaptation**, starting with US, EU, and Canadian tax/mortgage models
- 🧠 **Fine-tuned AI assistant** using anonymized user data (with opt-in)

---

## 👥 Contributors

- **Manasse Vita** – Full-stack Developer, Designer, and Author

> 🎯 For contributions, please open an issue or submit a pull request with clear documentation.

---

## 📄 License

This project is licensed under the **MIT License**.  
See [LICENSE](./LICENSE) for complete details.

---

## 🙌 Acknowledgements

- 🧠 [Google Vertex AI](https://cloud.google.com/vertex-ai) – conversational AI engine
- 🏡 [MoneyHelper](https://www.moneyhelper.org.uk/) – rent vs buy guidance inspiration
- 🧰 [ReactJS](https://reactjs.org/) and [Flask](https://flask.palletsprojects.com/) – development frameworks
- 📊 [UK Gov Data](https://www.gov.uk/) – housing tax, inflation, and council tax references

---

## 📌 Academic Note

🧪 This application was developed as part of a university dissertation titled:

**"Bridging the Gap Between Financial Literacy and Housing Decisions through Explainable AI"**

The GitHub repository contains:

- ✅ Project Proposal  
- ✅ Methodology, system architecture, and implementation  
- ✅ Evaluation results and user testing feedback  
- ✅ Sprint evidence and GitHub Project board  
- ✅ Source code and interactive frontend/backend

📂 Access the complete project archive:  
👉 [https://github.com/MVita11/rent-vs-buy-analysis](https://github.com/MVita11/rent-vs-buy-analysis)

> 📎 *To assist assessors, screenshots, appendices, and documents are located in `/docs`, `/project-management`, and `/screenshots`.*

---
