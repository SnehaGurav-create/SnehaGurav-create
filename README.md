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

---

## 🚀 Featured Projects

<p align="center">
  <i>Building intelligent solutions through software engineering, AI/ML, healthcare innovation, and cloud technologies.</i>
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🩸 Blood Donation Network System

A full-stack platform designed to connect blood donors with people in need, helping simplify donor discovery and blood donation coordination.

**⚙️ Tech Stack**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**✨ Key Areas**
- Donor management and search
- Authentication and secure APIs
- Database integration

</td>
<td width="50%" valign="top">

### 🩺 GlycoSense

**Explainable AI for Diabetes**

An AI-powered project focused on diabetes severity classification, personalized dietary guidance, and interpretable model predictions.

**⚙️ Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square)
![ML](https://img.shields.io/badge/Machine_Learning-8A2BE2?style=flat-square)
![SHAP](https://img.shields.io/badge/Explainable_AI-00A896?style=flat-square)

**✨ Key Areas**
- Severity-aware classification
- SHAP-based explainability
- Personalized dietary recommendations

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ❤️ CardioScope

**AI-Powered Cardiovascular Health Insights**

A healthcare-focused project concept aimed at analyzing relevant health data to support cardiovascular risk assessment and provide understandable health insights.

**⚙️ Suggested Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ML](https://img.shields.io/badge/Machine_Learning-8A2BE2?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**✨ Key Areas**
- Health data analysis
- Risk classification using validated models
- Explainable predictions and educational insights

</td>
<td width="50%" valign="top">

### 🌱 AgroVision

**AI-Driven Smart Agriculture**

An agriculture-focused project concept exploring AI-powered crop insights to support informed agricultural decisions and sustainable farming practices.

**⚙️ Suggested Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ML](https://img.shields.io/badge/Machine_Learning-8A2BE2?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**✨ Key Areas**
- Crop and plant health analysis
- Image-based disease detection
- Data-driven agricultural insights

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤟 Smart Sign Language Translation

A computer-vision project exploring real-time sign language gesture recognition and translation to support accessible communication.

**⚙️ Tech Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)

**✨ Key Areas**
- Hand landmark detection
- Gesture recognition
- Real-time translation pipeline

</td>
<td width="50%" valign="top">

### ☁️ AWS Networking & Infrastructure

Hands-on cloud infrastructure learning using AWS CLI, covering virtual networking and compute resource configuration.

**⚙️ Tech Stack**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-527FFF?style=flat-square)

**✨ Key Areas**
- VPC and subnet configuration
- Security groups and EC2
- AWS CLI automation

</td>
</tr>
</table>

<p align="center">
  <b>💡 Explore • Experiment • Engineer • Evolve</b>
</p>

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




---

<h2 align="center">📊 GitHub Analytics Dashboard</h2>

<p align="center">
  <i>Tracking my coding journey, consistency, and development activity.</i>
</p>

<table>
<tr>
<td width="33%" align="center" valign="top">

### 💻 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=SnehaGurav-create&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" width="100%" alt="GitHub Statistics" />

</td>
<td width="33%" align="center" valign="top">

### 🚀 Most Used Languages

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SnehaGurav-create&layout=compact&theme=tokyonight&hide_border=true" width="100%" alt="Most Used Languages" />

</td>
<td width="33%" align="center" valign="top">

### 🔥 Contribution Streak

<img src="https://streak-stats.demolab.com?user=SnehaGurav-create&theme=tokyonight&hide_border=true" width="100%" alt="GitHub Contribution Streak" />

</td>
</tr>
</table>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SnehaGurav-create&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="GitHub Contribution Activity Graph" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Every+commit+is+progress.;Consistency+builds+great+software.;Keep+Learning.+Keep+Building." alt="Coding motivation" />
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
