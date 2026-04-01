<h1 align="center">
  Hi 👋, I'm Devashish Bajaj
</h1>

<h3 align="center">
  🚀 AI/ML Engineer | Cognitive Computing | Full Stack Developer
</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&center=true&vCenter=true&lines=AI+%7C+ML+%7C+NLP+Enthusiast;Full+Stack+Developer;Building+Real+World+AI+Solutions;Always+Learning+New+Things+🚀">
</p>

---

## 🧠 About Me
- 🎓 M.Tech CSE (Cognitive Computing) @ SRM IST (CGPA: 9.08)
- 🤖 AI/ML | NLP | Computer Vision Enthusiast
- 🌐 Full Stack Developer (Flask + Flutter)
- 📊 Data Analytics & Visualization Lover
- 🚀 Building impactful AI-driven applications

---

## ⚡ Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,c,js,dart,flask,flutter,tensorflow,firebase,opencv,git,github,html,css" />
</p>

---

## 🚀 Featured Projects

### 🌍 Air Quality Analysis Dashboard
✔️ Streamlit + Plotly + Prophet  
✔️ Real-time AQI visualization & forecasting  
✔️ Weather API integration  

---

### 🧴 Skin Disease Detection
✔️ EfficientNet-B0 Deep Learning Model  
✔️ Multi-class classification  
✔️ AI in Healthcare  

---

### ✈️ Flight Finder AI
✔️ Transformer-based NLP chatbot  
✔️ Natural language flight search  
✔️ API integration  

---

### 📚 Library Management System
✔️ Python + Tkinter + SQLite  
✔️ Full CRUD operations  
✔️ GUI-based system  

---

## 🏆 Certifications
- 🥇 Oracle Generative AI Professional  
- ☁️ AWS ML Foundations  
- 📱 Flutter & Dart  
- 🧠 NLP & Text Mining  
- 🌐 Networking Basics (Cisco)  

---

## 🏁 Achievements
🏆 Finalist – CAD 2.0 Hackathon  
🏆 Finalist – Blockchain Hackathon  

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&hide_border=true" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://github.com/YOUR_USERNAME/YOUR_USERNAME/blob/output/github-contribution-grid-snake.svg" />
</p>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/YOUR_LINK">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:db8681@srmist.edu.in">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/YOUR_USERNAME">
    <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
  </a>
</p>

---

## ⚡ Fun Fact
💡 I build AI systems that solve real-world problems 🚀

---

## 🔥 Snake Setup (IMPORTANT STEP)

To activate the snake animation:

1. Go to your repo  
2. Click **Actions** tab  
3. Click **New Workflow**  
4. Choose **"set up a workflow yourself"**  
5. Paste this:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
