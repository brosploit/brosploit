<!--
  PROFILE README — replace every YOUR_USERNAME with your GitHub username.
  Create a public repo named exactly YOUR_USERNAME/YOUR_USERNAME, drop this in as README.md.
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=D4A017&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Dhruv+%F0%9F%91%8B;Developer+from+India+%F0%9F%87%AE%F0%9F%87%B3;Building+DegreePilot+%F0%9F%8E%93;Tinkering+with+Arduino+%26+hardware+%F0%9F%94%A7" alt="Typing SVG" />

<br/>

![Profile views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile+views&color=0B1F3A&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/YOUR_USERNAME?style=for-the-badge&logo=github&color=0B1F3A)
![Stars](https://img.shields.io/github/stars/YOUR_USERNAME?style=for-the-badge&logo=github&color=D4A017)

</div>

---

## 🧭 About me

- 🎓 Building **DegreePilot**, a platform that helps Indian students navigate academic pathways from secondary school to undergraduate degrees
- 🔧 Hardware tinkerer: Arduino, fingerprint sensors, GSM modules
- 🧱 I like modular, dependency-light architectures that are easy to extend
- 📍 Based in India

> 💡 **Tip:** click the ▶ arrows below to expand sections.

---

## 🚀 Projects

<details open>
<summary><b>🎓 DegreePilot</b> — education portal for Indian students</summary>
<br/>

A modular, extensible foundation for guiding students through academic pathways. Future modules (admissions, scholarships, college predictors) plug in without touching the core.

| | |
|---|---|
| **Stack (current)** | PHP 8.x, MySQL, framework-independent, built for shared hosting |
| **Stack (earlier phase)** | Flask 3, PostgreSQL, SQLAlchemy 2, Alembic |
| **Auth** | Passwordless, provider-agnostic OTP |
| **Architecture** | Service layer + repository pattern, role-based access control |
| **Design** | Navy and gold academic theme |
| **Status** | 🟡 In active development |

<details>
<summary>🧩 Architecture highlights</summary>

- PSR-4-style autoloader and a minimal HTTP kernel (Request / Response / Router / Middleware)
- Hardened sessions with CSRF protection
- Category-based logger with sensitive-data redaction
- Hostname-based admin subdomain routing
- Single generic `EducationProfile` model with a JSON escape hatch

</details>

[![Repo](https://img.shields.io/badge/View_repo-0B1F3A?style=for-the-badge&logo=github)](https://github.com/YOUR_USERNAME/degreepilot)

</details>

<details>
<summary><b>🖐️ Fingerprint Attendance System</b> — Arduino UNO</summary>
<br/>

A modular attendance system that logs fingerprint scans with timestamps and sends SMS alerts.

| Component | Role |
|---|---|
| Arduino UNO | Controller |
| R307 | Fingerprint sensor |
| I2C LCD | Display |
| DS1307 RTC | Timekeeping |
| SIM800L | GSM / SMS |
| Buzzer | Audio feedback |

[![Repo](https://img.shields.io/badge/View_repo-0B1F3A?style=for-the-badge&logo=github)](https://github.com/YOUR_USERNAME/fingerprint-attendance)

</details>

---

## 🛠️ Tech stack

<details open>
<summary><b>Click to toggle</b></summary>
<br/>

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</details>

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" alt="Stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true" alt="Streak" />

</div>

<details>
<summary>📈 Contribution activity graph</summary>
<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&hide_border=true" alt="Activity graph" width="100%" />

</details>

<details>
<summary>🐍 Contribution snake (needs a one-time setup)</summary>
<br/>

Add this workflow at `.github/workflows/snake.yml` in your profile repo, run it once, then uncomment the image below.

```yaml
name: Generate snake
on:
  schedule: [{ cron: "0 0 * * *" }]
  workflow_dispatch:
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/github-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

<!-- <img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake.svg" alt="Snake" /> -->

</details>

---

## 📌 Currently

| | |
|---|---|
| 🔭 Working on | DegreePilot: database schema, docs, deployment |
| 🌱 Learning | Scaling modular architectures on shared hosting |
| 💬 Ask me about | PHP architecture, Flask, Arduino projects |

---

## 🤝 Let's connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/YOUR_HANDLE)

<br/>

<sub>⭐ If something here helped you, drop a star on the repo.</sub>

</div>
