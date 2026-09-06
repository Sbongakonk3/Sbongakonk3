<div align="center">

# Sibongakonke (Owethu) Ntsele

### Academic Officer at Wits University | BSc Computer Science & Applied Mathematics (2nd Year), University of the Witwatersrand

<img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD&height=120&section=header" width="100%"/>

</div>

---

## About Me

I am a second-year Computer Science and Applied Mathematics student at the University of the Witwatersrand, currently serving as the Academic Officer of Barnato Hall, where I coordinate academic support and tutor Applied Mathematics for fellow residents. I also contribute to the Wits Community Outreach Program, tutoring high school students on weekends.

My technical focus is on machine learning and cybersecurity, supported by a broader interest in computer vision, networking, Linux, and system administration. I am self-taught in machine learning and have built a range of models to deepen my practical understanding of the field. I am currently developing a Student Hub application aimed at making campus and residence life more efficient for students.

I am seeking opportunities and collaborations in software development, machine learning, and cybersecurity, and I am always open to connecting with like-minded developers and researchers.

---

## Tech Stack

**Languages**

<p> <img src="https://img.shields.io/badge/Python-6A0DAD?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Java-6A0DAD?style=for-the-badge&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-6A0DAD?style=for-the-badge&logo=javascript&logoColor=white" /> <img src="https://img.shields.io/badge/C++-6A0DAD?style=for-the-badge&logo=cplusplus&logoColor=white" /> </p>

**Domains**

<p> <img src="https://img.shields.io/badge/Machine%20Learning-800080?style=for-the-badge&logo=tensorflow&logoColor=white" /> <img src="https://img.shields.io/badge/Cybersecurity-800080?style=for-the-badge&logo=hackthebox&logoColor=white" /> <img src="https://img.shields.io/badge/Computer%20Vision-800080?style=for-the-badge&logo=opencv&logoColor=white" /> <img src="https://img.shields.io/badge/Networking-800080?style=for-the-badge&logo=cisco&logoColor=white" /> </p>

**Tools & Platforms**

<p> <img src="https://img.shields.io/badge/Linux-4B0082?style=for-the-badge&logo=linux&logoColor=white" /> <img src="https://img.shields.io/badge/System%20Administration-4B0082?style=for-the-badge&logo=gnu-bash&logoColor=white" /> <img src="https://img.shields.io/badge/Git-4B0082?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-4B0082?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/VS%20Code-4B0082?style=for-the-badge&logo=visualstudiocode&logoColor=white" /> </p>

---

## GitHub Analytics

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Sbongakonk3&show_icons=true&theme=radical&hide_border=true&bg_color=0D0221&title_color=B084CC&icon_color=B084CC&text_color=E0D7F5" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sbongakonk3&layout=compact&theme=radical&hide_border=true&bg_color=0D0221&title_color=B084CC&text_color=E0D7F5" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sbongakonk3&theme=radical&hide_border=true&background=0D0221&stroke=B084CC&ring=800080&fire=B084CC&currStreakLabel=B084CC" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Sbongakonk3&theme=redical&hide_border=true&bg_color=0D0221&color=B084CC&line=800080&point=E0D7F5" />
</p>

---

## Achievements & Contribution Graph

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Sbongakonk3&theme=algolia&no-frame=true&column=4&margin-w=15&margin-h=15" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Sbongakonk3/Sbongakonk3/output/github-contribution-grid-snake.svg" alt="Contribution Snake" />
</p>

> Note: The contribution snake animation above requires a one-time GitHub Actions workflow set up in this repository. Instructions are provided at the end of this file.

---

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/sibongakonke-ntsele">
    <img src="https://img.shields.io/badge/LinkedIn-4B0082?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Sbongakonk3">
    <img src="https://img.shields.io/badge/GitHub-4B0082?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:ntselesbongakonkeowethu@gmail.com">
    <img src="https://img.shields.io/badge/Email-4B0082?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=6A0DAD&height=100&section=footer" width="100%"/>
</div>

---

<details>
<summary><b>How to enable the contribution snake animation</b></summary>

1. In your profile repository (`Sbongakonk3/Sbongakonk3`), create a file at `.github/workflows/snake.yml` with the following content:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Platane/snk@v3
        id: snake
        with:
          github_user_name: Sbongakonk3
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

2. Push this file to your `main` branch.
3. GitHub Actions will run automatically and generate the snake SVG on an `output` branch, which this README references.
4. Enable Actions if prompted, and allow the workflow read/write permissions under Settings → Actions → General.

</details>
