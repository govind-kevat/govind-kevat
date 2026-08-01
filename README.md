<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:000000,100:1a1a2e&text=Govind%20Kevat&fontSize=50&fontColor=00FF00&animation=twinkling&fontAlignY=40&desc=%3E%20Java%20Developer%20%7C%20Building%20Projects%20%7C%20Learning%20DSA&descAlignY=65&descSize=18" />
</p>

<h1 align="center">
  Hi 👋, I'm Govind Kevat
</h1>

<h3 align="center">
  MCA Student | Java Developer | Aspiring Software Engineer
</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&center=true&vCenter=true&width=700&lines=Java+Developer;Learning+Data+Structures+%26+Algorithms;Building+Real+World+Projects;Always+Learning+New+Things" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=govind-kevat&label=Profile+Views&style=for-the-badge&color=0e75b6"/>
</p>

---

## 👨‍💻 About Me

* 🎓 MCA Student at **LNCT, Bhopal**
* ☕ Currently learning **Java & Data Structures and Algorithms**
* 💻 Building Java projects and improving problem-solving skills
* 🌱 Exploring **Git, GitHub, SQL, and Full Stack Development**
* 🚀 Interested in Backend Development and Software Engineering
* 🎯 Goal: Become a skilled Software Developer

---

## 💻 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,html,css,javascript,mysql,git,github,vscode,idea&perline=5" />
</p>

---

## 🚀 Featured Project

### 🌱 Eco-Score

A Java-based application that promotes eco-friendly habits by calculating an environmental score based on user activities.

### ✨ Features

* 🌍 Calculates environmental impact
* 📊 Provides eco-friendly scoring system
* 💡 Encourages sustainable lifestyle choices

🔗 Repository:
https://github.com/govind-kevat/Eco-Score

---

## 🏆 LeetCode Profile

<p align="center">
  <img src="https://leetcard.jacoblin.cool/Govind-kevat?theme=dark&font=Karma&ext=contest" />
</p>

---

## 🌐 Connect With Me

<p align="center">

<a href="https://github.com/govind-kevat">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/govind-kevat-96616233a">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://leetcode.com/u/Govind-kevat/">
<img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>

</p>

---

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    permissions:
      contents: write

    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: mukesh-patidar62
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          

## 💻 Currently Learning

<p align="center">
  <img width="450" src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif">
</p>

<p align="center">
  <b>☕ Java • 📚 DSA • 🌐 Full Stack Development • 🚀 Open Source</b>
</p>
