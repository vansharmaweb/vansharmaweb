<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Vansh+Sharma+%F0%9F%91%8B;B.Tech+CSE+%40+PSIT+Kanpur;Building+real+things+that+ship+%F0%9F%9A%80)](https://git.io/typing-svg)

<p>
  <img src="https://komarev.com/ghpvc/?username=vansharmaweb&color=58a6ff&style=flat-square&label=profile+views" />
  <img src="https://img.shields.io/github/followers/vansharmaweb?&color=58a6ff&style=flat-square&label=followers" />
</p>

</div>

---

## $ whoami

```python
vansh = {
    "name"      : "Vansh Sharma",
    "college"   : "PSIT Kanpur · AKTU · B.Tech CSE",
    "year"      : "2nd Year",
    "cgpa"      : 8.86,
    "building"  : ["Portfolio tools", "Expense trackers", "DSA grind"],
    "learning"  : ["C++", "Python", "SQL", "Modern Web Dev"],
    "belief"    : "Consistency beats talent when talent doesn't show up.",
}
```

---

## 🚀 projects

| Project | What it does |
|---|---|
| 🌐 **[Portfolio Website Generator](https://portgen.gitignored.workers.dev/)** | Build & deploy stunning dev portfolios — one-click GitHub Pages deploy + Markdown export |
| 💸 **[Student Expense Tracker](https://exptracker.vanshonweb.workers.dev/)** | Fintech-inspired SPA for students — budget scoring, real-time health meter, dark mode |
| 🛠️ **[UtilityX](https://utilityx.vanshonweb.workers.dev/)** | Pinned app dashboard + admin-promoted utilities — your own mini app store |
| 💼 **[Portfolio](https://vansharmaweb.github.io)** | My personal corner of the internet |
| ⚡ **[CPP Questions](https://github.com/vansharmaweb/CPP_Questions)** | C++ grind — arrays, OOP, and beyond |
| 🐍 **[HackerRank Python](https://github.com/vansharmaweb/HACKERRANK_Ques_Python)** | Python problem-solving playground |

---

## 📊 github stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=vansharmaweb&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9"/>

<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vansharmaweb&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=vansharmaweb&theme=tokyonight-duo&hide_border=true&background=0d1117&ring=58a6ff&fire=ff7b54&currStreakLabel=58a6ff" alt="GitHub Streak"/>

</div>

<!--
NOTE ON THE ACTIVITY GRAPH:
The old <img src="github-readme-activity-graph.vercel.app/graph?..."> line is removed below
because that demo server intermittently fails with "Failed to retrieve contributions" —
it's a shared free instance that gets rate-limited by GitHub's API, not an issue with your
account or username. Two fixes, pick one:

OPTION A (quick, same reliability as before): just re-add this line, it usually recovers
on its own within a few hours:
<img src="https://github-readme-activity-graph.vercel.app/graph?username=vansharmaweb&theme=tokyo-night&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&hide_border=true" alt="Contribution Graph"/>

OPTION B (permanent fix, recommended): generate the graph yourself via a GitHub Action
that commits an SVG into your profile repo on a schedule. It never depends on a third-party
server being up. Workflow + embed snippet given below the tech stack section.
-->

---

## 🛠️ tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=cplusplus&logoColor=00599C)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-0d1117?style=for-the-badge&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-0d1117?style=for-the-badge&logo=css3&logoColor=1572B6)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=mysql&logoColor=4479A1)
![Flask](https://img.shields.io/badge/Flask-0d1117?style=for-the-badge&logo=flask&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-0d1117?style=for-the-badge&logo=cloudflare&logoColor=F38020)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-0d1117?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 🐍 contribution snake (self-hosted, never breaks)

<div align="center">

<img src="https://raw.githubusercontent.com/vansharmaweb/vansharmaweb/output/github-contribution-grid-snake.svg" alt="Snake animation eating your contributions" />

</div>

*(This image only appears once you add the workflow below to your `vansharmaweb/vansharmaweb` repo — it generates the SVG itself, so it doesn't depend on any external server.)*

<details>
<summary>Setup: <code>.github/workflows/snake.yml</code></summary>

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"   # every 6 hours
  workflow_dispatch: {}
  push:
    branches: [main]

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: vansharmaweb
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Push that file to your profile repo, let the Action run once, then the `<img>` tag above will render.
</details>

---

## 📫 reach me

<div align="center">

[![Gmail](https://img.shields.io/badge/vanshsharmaweb@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:vanshsharmaweb@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/vansharmaweb)
[![Portfolio](https://img.shields.io/badge/portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=white)](https://vansharmaweb.github.io)
[![Reddit](https://img.shields.io/badge/r%2Fgitignoreddevs-0d1117?style=for-the-badge&logo=reddit&logoColor=FF4500)](https://reddit.com/r/gitignoreddevs)

</div>

---

<div align="center">
  <em>⭐ If something here sparked interest, a star on a repo means a lot — it keeps the 2AM sessions worth it.</em>
</div>
