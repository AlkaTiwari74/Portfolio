# 🌐 Alka Tiwari — Personal Cloud Portfolio

<div align="center">

![Portfolio Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,35:203A43,70:2C5364,100:6A11CB&height=220&section=header&text=ALKA%20TIWARI&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Cloud%20Computing%20%7C%20AWS%20%7C%20Networking%20%7C%20Cloud%20Security&descAlignY=60&descSize=18)

[![Live Website](https://img.shields.io/badge/Live_Portfolio-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://YOUR_PORTFOLIO_URL)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alka-tiwari-724552423)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alka630@gmail.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<br/>

> **Modern, responsive, dark-themed cloud engineer portfolio featuring interactive architecture diagrams, live skill matrices, and AWS project documentation.**

</div>

---

## 📌 Overview

This repository contains the source code for the personal portfolio of **Alka Tiwari**, a BCA student at Amity University Online specializing in **AWS Cloud Computing, Computer Networking, and Cloud Security**.

The web application is built with modern web standards, featuring a clean cyberpunk/glassmorphism dark aesthetic, interactive terminal simulators, architecture visualization, and direct contact integration.

---

## ✨ Key Features

- ⚡ **Zero-Friction Landing:** Direct access without lock screens or redundant loading screens.
- 🎨 **Modern Cyber/Cloud Aesthetic:** Deep dark gradients, glowing glassmorphism, glowing borders, and responsive grid layouts.
- ⌨️ **Interactive Terminal Simulation:** Demonstrates AWS CLI querying directly in the hero section.
- 🧰 **Dynamic Tech Stack Filter:** Toggle between AWS & Cloud, Networking, Systems, and Tools with live badges.
- 📐 **Interactive Architecture Diagram:** Visual breakdown of the static website hosting topology on **Amazon S3** with bucket configuration details.
- 🗺️ **3-Stage Learning Roadmap:** Visual timeline tracking Foundations, Cloud Engineering, and Cloud Security milestones.
- 📬 **Interactive Connect Section:** Direct one-click email copy button and mailto generator.

---

## 🛠️ Tech Stack & Dependencies

| Layer | Technologies |
| :--- | :--- |
| **Frontend Core** | HTML5, Modern CSS3, JavaScript (ES6+) |
| **Styling & Icons** | [Tailwind CSS CDN](https://tailwindcss.com), [FontAwesome 6.4](https://fontawesome.com) |
| **Typography** | `Inter` (UI) & `Fira Code` (Monospace/CLI) via Google Fonts |
| **Deployment Options** | Amazon S3 Static Website Hosting, GitHub Pages, Vercel, or Netlify |

---

## 📁 Project Structure

```text
├── index.html        # Main single-page portfolio layout & JavaScript logic
├── README.md         # Documentation & project guide
└── assets/           # (Optional) Static images, diagrams, and downloadable resume
🚀 Quick Start & Local Setup
1. Clone the repository
Bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/portfolio.git](https://github.com/YOUR_GITHUB_USERNAME/portfolio.git)
cd portfolio
2. Run locally
You can open index.html directly in any browser:

Double click index.html, or

Use VS Code extension Live Server (Right-click index.html -> Open with Live Server), or

Use Python's built-in server:

Bash
python3 -m http.server 8000
Then navigate to http://localhost:8000.

☁️ Deployment Guide (Amazon S3)
To deploy this project to Amazon S3 Static Website Hosting (as highlighted in the portfolio's featured project):

Create an S3 Bucket:

Bucket name: alka-tiwari-portfolio (must be globally unique)

Uncheck "Block all public access" and acknowledge the warning.

Enable Static Website Hosting:

Go to Bucket Properties -> scroll to Static website hosting -> Click Edit.

Select Enable, specify index.html as the index document, and click Save changes.

Add Bucket Policy:

Go to the Permissions tab -> Bucket Policy -> Edit and paste:

JSON
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::alka-tiwari-portfolio/*"
    }
  ]
}
(Replace alka-tiwari-portfolio with your actual bucket name).

Upload Files:

Upload index.html (and any assets folder) directly to the bucket root.

Access Your Site:

Find your Bucket website endpoint at the bottom of the Properties tab!

👩‍💻 About the Author
Alka Tiwari

BCA Student (2026–2029) — Amity University Online

Focus Areas: Cloud Infrastructure, AWS, Computer Networking, Linux, Cloud Security.

LinkedIn: alka-tiwari

Email: alka630@gmail.com

📄 License
This project is open source and available under the MIT License.


### 💡 Quick Tips:
1. Replace `YOUR_GITHUB_USERNAME` and `YOUR_PORTFOLIO_URL` with your actual links before committing.
2. If you want this to serve as your **GitHub Profile README**, you can create a rep
