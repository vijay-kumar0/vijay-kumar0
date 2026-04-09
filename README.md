<!-- PROFILE BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=180&section=header&text=Vijay%20Kumar&fontSize=35&fontColor=ffffff" />
</p>

<h2 align="center">Hi 👋 I'm Vijay Kumar</h2>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=vijay-kumr0&color=blue" />
</p>

<p align="center">
  <b>Aspiring Software Developer | Building Clean & Functional Projects</b>
</p>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&center=true&vCenter=true&lines=Full+Stack+Developer;Problem+Solving;Building+Projects" />
</p>

---

## ⚡ About Me

- 🎓 BCA Student  
- 💻 Focused on Web Development  
- 🚀 Learning by building real projects  
- 🧠 Improving logic & problem-solving  

---

## 🛠️ Skill & Tech

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,java,github,vscode" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vijay-kumar0&show_icons=true&theme=tokyonight&hide_border=true" height="150"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vijay-kumar0&theme=tokyonight&hide_border=true" height="150"/>
</p>

---

## 🚀 Projects

- 🧮 Calculator Web App  
  → Real-time calculations, keyboard input, custom logic (no eval)  
  🔗 https://vijay-kumar.github.io/Calculator/

- 🌐 Portfolio Website  
  → Responsive design showcasing projects and skills  
  🔗 https://vijay-kumar.github.io/My-Portfolio/
---

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v2

      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: vijay-kumar0
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            dist/github-contribution-grid-snake-neon.svg?color_snake=00f7ff&color_dots=#161b22,#0e4429,#006d32,#26a641,#39d353

      - name: Push
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## 🔗 Connect With Me

<p align="center">

<a href="https://github.com/vijay-kumar0">
  <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://linkedin.com/in/thevijaykumar">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:imvksdr@gmail.com@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://vijay-kumar.github.io/My-Portfolio/">
  <img src="https://img.shields.io/badge/Portfolio-1e40af?style=for-the-badge&logo=google-chrome&logoColor=white"/>
</a>

</p>

---

<p align="center">
  ⚡ "Consistency beats intensity."
</p>
