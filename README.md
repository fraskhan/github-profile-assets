<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00C2CB&center=true&vCenter=true&width=500&lines=Hey%2C+I'm+Alfraskhan+A.+Jose+%F0%9F%91%8B;Full+Stack+Developer+%40+ALTSOLUTIONS;Web+%E2%80%A2+App+%E2%80%A2+Data+Analytics" alt="Typing SVG" />
<br/>
![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Profile Views](https://komarev.com/ghpvc/?username=fraskhan&style=for-the-badge&color=00c2cb&label=PROFILE+VIEWS)
</div>
---
About Me
🎓 IT Graduate — Pilar College, Class of 2025
💼 Full Stack Developer at ALTSOLUTIONS
🔭 Currently building full-stack web & mobile apps
📊 Expanding into Data Analytics
⚡ Always shipping, always learning
---
Tech Stack
Languages & Frameworks
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>
Frameworks & Libraries
<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
</p>
Databases
<p>
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
</p>
---
GitHub Stats
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=fraskhan&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=fraskhan&theme=tokyonight&hide_border=true" height="165"/>
<br/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fraskhan&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>
</div>
---
Contribution Graph — Snake
> The snake eats contributions from lowest to highest 🐍
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fraskhan/fraskhan/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fraskhan/fraskhan/output/github-contribution-grid-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/fraskhan/fraskhan/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>
> **To activate the snake:** create `.github/workflows/snake.yml` in your profile repo (see below ↓)
---
<details>
<summary>⚙️ Snake Setup — GitHub Actions Workflow</summary>
Create the file `.github/workflows/snake.yml` in your `fraskhan/fraskhan` repository:
```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # runs daily at midnight UTC
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
</details>
---
<div align="center">
  <i>"Code is like humor. When you have to explain it, it's bad." — Cory House</i>
</div>
