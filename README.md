
![Github Snake](https://raw.githubusercontent.com/behruzbek12329112010-code/behruzbek12329112010-code/output/github-contribution-grid-snake-dark.svg)
name: Generate Snake

on:
  schedule:
    # Har 12 soatda avtomatik yangilanadi
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
    - main
    - master

jobs:
  generate:
    permissions: 
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
          
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GH_TOKEN }}
###  Dynamic Activity Wave
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=behruzbek12329112010-code&theme=github-dark&color=79ffdf&line=79ffdf&point=ffffff&area=true&hide_border=true" width="100%" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />
</p>

###  Professional Metrics & Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=behruzbek12329112010-code&show_icons=true&theme=dark&icon_color=79ffdf&title_color=79ffdf&text_color=9f9f9f&bg_color=0d1117&count_private=true" height="150px" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=behruzbek12329112010-code&theme=dark&background=0d1117&fire=79ffdf&ring=79ffdf&sideLabels=9f9f9f" height="150px" />
</p>



###  Core Tech Stack & Skills
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,react,git,figma,vscode,netlify" />
  </a>
</p>

---
###  Let's Connect & Collaborate
<p align="center">
  <a href="https://t.me/WWwomadlila" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-2EA44F?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>

</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />
</p>
<p align="center">
   <b>Email:</b> <a href="mailto:behruzbek12329112010@gmail.com">behruzbek12329112010@gmail.com</a> |  <b>Portfolio:</b> <a href="https://bexaaone.netlify.app/" target="_blank">bexaaone.netlify.app</a>
</p>



