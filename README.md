<!-- PROFILE HEADER -->

<h1 align="center">Hi 👋, I'm Sneha Gurav</h1>

<h3 align="center">💻 Computer Science Engineering Student | Aspiring Software Engineer | AI/ML Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Building+Ideas+Into+Software;Exploring+AI%2FML+%26+Full-Stack+Development;Learning+%E2%80%A2+Building+%E2%80%A2+Improving" alt="Typing introduction" />
</p>

<p align="center">
  <a href="https://github.com/SnehaGurav-create">
    <img src="https://img.shields.io/badge/GitHub-SnehaGurav--create-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Software%20Engineering-0A66C2?style=for-the-badge" alt="Software Engineering" />
  <img src="https://img.shields.io/badge/Interest-AI%20%7C%20ML-8A2BE2?style=for-the-badge" alt="AI and ML" />
</p>

---

## 👩‍💻 About Me

```json
{
  "🧑‍💻 name": "Sneha Sadanand Gurav",
  "📍 location": "Peth, Maharashtra, India",

  "🎓 education": {
    "current": "B.Tech CSE — MIT Academy of Engineering, Alandi, Pune",
    "focus": "Software Engineering | Artificial Intelligence | Machine Learning"
  },

  "⚡ technical_focus": [
    "💻 Software Developer → Building practical software solutions",
    "🌐 Full-Stack Developer → React, JavaScript, Node.js, Express.js",
    "🤖 AI/ML Enthusiast → Machine Learning, XGBoost, Explainable AI",
    "☁️ Cloud Computing Learner → AWS, EC2, VPC, IAM, AWS CLI",
    "🧩 Problem Solver → Data Structures, Algorithms, Java, C++"
  ],

  "🚀 featured_projects": [
    "🩺 GlycoSense → Explainable AI for diabetes severity classification",
    "🩸 Blood Donation Network System → Full-stack web application",
    "🤟 Smart Sign Language Translation → Computer Vision and gesture recognition",
    "☁️ AWS Networking → Cloud infrastructure using AWS CLI"
  ],

  "🏅 professional_development": [
    "🎓 Cisco Virtual Internship Program 2026",
    "💡 Hands-on project development and technical learning",
    "🤝 Interested in hackathons, collaboration, and open-source development"
  ],

  "🛠️ technology_stack": {
    "languages": ["C", "C++", "Java", "Python", "JavaScript"],
    "web": ["HTML", "CSS", "React", "Node.js", "Express.js"],
    "databases": ["MySQL", "SQLite"],
    "tools": ["Git", "GitHub", "VS Code", "AWS"],
    "ai_ml": ["Machine Learning", "Computer Vision", "XGBoost", "SHAP"]
  },

  "💬 philosophy": "Learn continuously. Build purposefully. Solve real-world problems through technology."
}
```


## 🛠️ Technical Arsenal

### Programming Languages

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,java,python,js" alt="C, C++, Java, Python and JavaScript" />
</p>

### Web Development

<p>
  <img src="https://skillicons.dev/icons?i=html,css,react,nodejs,express,vite" alt="Web development technologies" />
</p>

### Databases & Tools

<p>
  <img src="https://skillicons.dev/icons?i=mysql,sqlite,git,github,vscode,aws" alt="Databases and developer tools" />
</p>

### AI / ML & Development Areas

`Machine Learning` · `Computer Vision` · `Explainable AI` · `REST APIs` · `Cloud Computing`

---
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: SnehaGurav-create
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


---

## 🚀 Featured Projects

### 🩸 Blood Donation Network System

A full-stack application concept for connecting blood donors with people seeking blood donations.

**Tech Stack:** React · Vite · Node.js · Express.js · MySQL · JWT

**Focus Areas:** Authentication, donor management, REST APIs, and database integration.

### 🩺 GlycoSense — Explainable AI for Diabetes

An AI/ML project focused on diabetes severity classification, personalized dietary guidance, and explainable predictions.

**Tech Stack:** Python · XGBoost · SHAP · Machine Learning

**Focus Areas:** Classification, model evaluation, interpretability, and personalized recommendations.

### 🤟 Smart Sign Language Learning & Translation

A computer-vision project concept for recognizing sign language gestures and supporting real-time translation.

**Tech Stack:** Python · OpenCV · MediaPipe · Deep Learning

**Focus Areas:** Gesture recognition, landmark extraction, and real-time prediction.

### ☁️ AWS Networking & Infrastructure

Hands-on cloud learning through AWS CLI and infrastructure configuration.

**Tech Stack:** AWS · EC2 · VPC · IAM · EBS · AWS CLI

**Focus Areas:** Virtual networking, security groups, compute instances, and cloud resource management.

> 📌 Replace these project descriptions with links to your actual repositories as they become available. Clearly label projects that are still in development.

---
---

## 🏆 Achievements & Certifications

<p align="center">
  <img src="https://img.shields.io/badge/Cisco-Virtual%20Internship%20Program%202026-049FD9?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco Virtual Internship Program 2026" />
  <img src="https://img.shields.io/badge/Focus-Continuous%20Learning-8A2BE2?style=for-the-badge" alt="Continuous Learning" />
</p>

- 🎓 **Cisco Virtual Internship Program 2026** — Developing technical knowledge through internship learning and practical activities.
- 💻 **Project Development** — Exploring software engineering, full-stack development, AI/ML, and cloud computing through hands-on projects.
- 🧠 **Problem Solving** — Continuously strengthening programming fundamentals, Data Structures, and Algorithms.
- 🚀 **Technical Growth** — Learning emerging technologies and applying them to practical engineering challenges.

> 📌 Add your verified certifications, competition rankings, awards, and other measurable achievements here as you earn them.

---

## 💡 Hackathons & Technical Activities

I enjoy exploring innovative ideas, collaborating with developers, and building technology-driven solutions to real-world problems.

- 🚀 **Hackathon Participation** — Working toward developing practical solutions for real-world challenges.
- 🩺 **Healthcare Innovation** — Exploring AI/ML applications through GlycoSense.
- 🤟 **Assistive Technology** — Exploring computer vision for sign language recognition and translation.
- 🌐 **Software Development** — Building full-stack applications and learning modern development workflows.
- 🤝 **Collaboration** — Interested in team-based problem solving, technical events, and open-source contributions.

### 🎯 Areas I'm Interested In

`Artificial Intelligence` · `Machine Learning` · `Healthcare Technology` · `Full-Stack Development` · `Cloud Computing` · `Social Impact`

> 🏅 **Hackathon Log:** Add each event's name, year, problem statement, project, team role, and result. Include a certificate or demo link whenever available.



## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SnehaGurav-create&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub statistics" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SnehaGurav-create&layout=compact&theme=tokyonight&hide_border=true" alt="Most used programming languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=SnehaGurav-create&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</p>

---

## 🎯 Current Mission

- Strengthen my problem-solving and software development skills.
- Build and document meaningful projects.
- Explore practical AI/ML applications.
- Improve my cloud deployment and engineering workflow.
- Contribute to collaborative and open-source development.

---

## 🤝 Let's Connect

<p align="center">
  <a href="https://github.com/SnehaGurav-create">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  ⭐ Thanks for visiting my profile! Let's learn, collaborate, and build something meaningful.
</p>
