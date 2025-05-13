# 🏠 AI-Powered Rent vs Buy Financial Advisor (UK Edition)

> A full-stack web application that helps users in the UK make informed housing decisions by comparing renting vs buying through personalized, explainable AI-powered financial analysis.

---

## 📌 Table of Contents

- [Overview](#overview)  
- [Key Features](#key-features)  
- [Live Demo](#live-demo)  
- [Tech Stack](#tech-stack)  
- [System Architecture](#system-architecture)  
- [Installation & Setup](#installation--setup)  
- [Usage Guide](#usage-guide)  
- [Testing](#testing)  
- [Known Limitations](#known-limitations)  
- [Planned Features](#planned-features)  
- [Contributors](#contributors)  
- [License](#license)

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

🌐 [Live Application URL](https://your-deployed-url.com)  
🔗 [GitHub Repository](https://github.com/your-username/rent-vs-buy-advisor)

> ⚠️ *Ensure the app is deployed and repo is public or access-enabled.*

---

## 🧰 Tech Stack

| Layer        | Technology                 |
|--------------|----------------------------|
| Frontend     | ReactJS, Bootstrap 5, CSS  |
| Backend      | Flask (Python), REST APIs  |
| AI Assistant | Google PaLM 2 via Vertex AI|
| Testing      | `pytest`, `unittest`, Postman |
| Deployment   | Vercel (frontend), Render (backend) |
| Design Tools | Figma (UI/UX prototyping)  |

---

## 🏗️ System Architecture

---

## 🧪 Usage Guide

1. Open the application in your browser (e.g., [http://localhost:3000](http://localhost:3000)).
2. Enter your:
   - Monthly rent
   - House price and deposit
   - Mortgage rate, term, and related costs
   - Estimated investment return (if renting)
3. Click **"Calculate"** to generate a side-by-side financial comparison.
4. Use the **chat assistant** to receive plain-English explanations of your results.
5. Adjust values to simulate new housing scenarios or test financial trade-offs.

---

## ✅ Testing

The system includes both unit and integration tests for functionality validation:

### ✅ Backend Testing


Covered functions:

- Mortgage amortization

- Rent escalation

- Stamp duty calculations

- Net equity and opportunity cost

## ✅ API Testing
- Test endpoints with Postman or curl:
   -`/calculate`: Validates full financial model outputs
   - `/chat`: Tests interaction with the AI assistant
   - Includes handling for missing fields, invalid numbers, and timeout scenarios

## ✅ Frontend Testing
- Manual testing across:
   - Chrome, Firefox, Safari
   - Desktop, tablet, and mobile breakpoints

- Key UI behaviors tested:
   - Form validation
   - Result rendering
   - Chatbot visibility and UX
   - API response handling (loading spinners, fallback messages)

## 🧭 Known Limitations
- 🔒 No login or persistent user account support (yet)
- 📉 No integration with live APIs for mortgage or property data
- 📊 Visualizations are minimal; current version is text-heavy
- ⚠️ AI can produce vague responses in rare or unusual scenarios
- 🧾 Tax modelling excludes advanced cases like capital gains, remortgaging, or letting income

## 🌱 Planned Features
- 📡 Real-time API integration with Rightmove, Zoopla, and the Bank of England
- 📈 Graphs for breakeven points, investment trajectories, and cost summaries
- 👤 Authenticated user profiles with dashboard and scenario history
- 🌐 Region selection for international market expansion
- 🧠 Fine-tuned AI responses using anonymized user data (ethical opt-in)

## 👥 Contributors
- Manasse Vita – Developer, Designer, and Author


## 🙌 Acknowledgements
- Google Vertex AI for providing the conversational AI backend
- MoneyHelper for rent vs buy educational frameworks
- ReactJS and Flask for enabling rapid development
- UK Government data portals for tax, mortgage, and inflation reference models

## 📌 Academic Note
🧪 This application was developed as part of a university dissertation titled:

"Bridging the Gap Between Financial Literacy and Housing Decisions through Explainable AI"

The full paper, including literature review, methodology, and evaluation, is available upon request or as a supplemental file in this repository.
