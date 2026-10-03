<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,15,31&height=220&section=header&text=Ritesh%20Kumar%20Kushwaha&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20Developer%20%7C%20Open%20Source%20Contributor%20%7C%20AI%20Enthusiast&descAlignY=60&descAlign=50" width="100%"/>

<!-- Typing Animation -->
<a href="https://github.com/itsriteshx">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=500&lines=Building+modern+web+%26+mobile+apps;Passionate+about+Open+Source;Exploring+AI+%26+Deep+Learning;Always+learning+and+shipping+code!" alt="Typing SVG" />
</a>

<br/>

<!-- Social Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/riteshkkushwaha)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:riteshroyal834047@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/itsriteshx?label=Followers&style=for-the-badge&color=238636&logo=github)](https://github.com/itsriteshx)

<br/>

---

</div>

### 👨‍💻 About Me

```yaml
name: Ritesh Kumar Kushwaha
location: India 🇮🇳
focus: Full-Stack Engineering, Open-Source & AI Systems
currently_learning: Advanced Distributed Systems & Deep Learning Architectures
fun_fact: "I turn coffee into scalable code and clean pull requests ☕⚡"

name: Generate Snake Animation

on:
  schedule:
    # Har 12 ghante me automatically update hoga
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: Generate GitHub Contribution Snake
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push Snake SVG to Output Branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<div align="center">

<!-- Futuristic Hero Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,24,31&height=240&section=header&text=RITESH%20KUMAR&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full%20Stack%20Engineer%20%E2%80%A2%20Open%20Source%20Contributor%20%E2%80%A2%20AI%20Enthusiast&descAlignY=58&descAlign=50" width="100%"/>

<!-- Dynamic Animated Typing Text -->
<a href="https://github.com/itsriteshx">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=Building+Scalable+Full-Stack+Systems+🚀;Open+Source+Contributor+%40+WeatherRoutingTool+🌐;Crafting+Desktop+Apps+with+Electron.js+💻;Exploring+Deep+Learning+%26+Optimization+Algorithms+🤖;Turning+Complex+Problems+into+Clean+Code+⚡" alt="Typing SVG" />
</a>

<br/><br/>

<!-- Modern Rounded Badges -->
<p align="center">
  <a href="https://linkedin.com/in/riteshkkushwaha">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:riteshroyal834047@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/itsriteshx?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-1E293B?style=for-the-badge&logo=github&logoColor=white" alt="Repos"/>
  </a>
  <a href="https://github.com/itsriteshx?tab=followers">
    <img src="https://img.shields.io/github/followers/itsriteshx?label=Followers&style=for-the-badge&color=0284C7&logo=github" alt="Followers"/>
  </a>
</p>

</div>

---

### 🐍 Contribution Activity Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itsriteshx/itsriteshx/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/itsriteshx/itsriteshx/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Grid Snake" src="https://raw.githubusercontent.com/itsriteshx/itsriteshx/output/github-contribution-grid-snake-dark.svg" width="100%" />
  </picture>
</div>

---

### ⚡ Terminal Summary

```zsh
ritesh@workspace ~ % neofetch --dev
-----------------------------------------
OS: macOS / Linux
Role: Full-Stack Developer & Open Source Contributor
Languages: Python, TypeScript, JavaScript, C++, Go, Kotlin
Core Stacks: React, Next.js, Node.js, Express, Fastify, Electron
Databases: PostgreSQL, MongoDB, Redis, MySQL, Prisma
Current Focus: Weather Routing Optimization & Real-Time Collaborative Platforms
Motto: "Write readable code, engineer scalable architecture."
-----------------------------------------

