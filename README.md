<div align="center">

```
   ████████╗██╗   ██╗██████╗ ████████╗
   ╚══██╔══╝██║   ██║██╔══██╗╚══██╔══╝
   ██║   ██║   ██║██████╔╝   ██║
   ██║   ██║   ██║██╔══██╗   ██║
   ██║   ╚██████╔╝██║  ██║   ██║
   ╚═╝    ╚═════╝ ╚═╝  ╚═╝   ╚═╝
```

### `@panithan` · `tull` · `turt`

**QA Tester & Vibe Coder** — based in 🇹🇭 Thailand  
Ramkhamhaeng University · Mass Comm × Tech

[![YouTube](https://img.shields.io/badge/YouTube-Genblem-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/@Genblem)
[![TikTok](https://img.shields.io/badge/TikTok-@genblem-000000?style=flat-square&logo=tiktok)](https://www.tiktok.com/@genblem)
[![Email](https://img.shields.io/badge/Email-genblem.forwork-EA4335?style=flat-square&logo=gmail)](mailto:genblem.forwork@gmail.com)

</div>

---

## `> whoami`

Hey 👋 I'm **Panithan** — call me **tull** or **turt**, doesn't matter.  
QA by day, vibe coder by night, streamer somewhere in between.

I'm 5 years into a Mass Comm degree at Ramkhamhaeng, spending most of my free time learning QA, writing tests, building stuff on the web, and occasionally going unhinged in Valorant ranked.

The goal? Merge my media background with real engineering skills. Still cooking. 🍳

---

## `> stack --list`

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)

**Currently Learning**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SDLC](https://img.shields.io/badge/SDLC-FF6B35?style=flat-square&logo=read-the-docs&logoColor=white)

**Tools I Actually Use**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0079BF?style=flat-square&logo=trello&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![OBS Studio](https://img.shields.io/badge/OBS_Studio-302E31?style=flat-square&logo=obs-studio&logoColor=white)
![Premiere Pro](https://img.shields.io/badge/Premiere_Pro-9999FF?style=flat-square&logo=adobe-premiere-pro&logoColor=white)
![After Effects](https://img.shields.io/badge/After_Effects-9999FF?style=flat-square&logo=adobe-after-effects&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobe-photoshop&logoColor=white)

**AI I Vibe With**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=google-gemini&logoColor=white)

---

## `> currently`

```yaml
learning:
  - Next.js + Express.js architecture
  - Node.js backend fundamentals
  - Playwright for E2E testing
  - SQL & database design
  - SDLC methodologies (Agile / Waterfall)
building:   things that may or may not work
playing:    Valorant (climbing), Dota 2 (suffering), CS2 (casually)
streaming:  TikTok content @ genblem
goal:       Mass Comm brain × Dev hands
```

---

## `> ci/cd --pipeline`

Automating tests & deploys with **GitHub Actions** — runs on every push, deploys only when `main` passes ✅

```yaml
# .github/workflows/ci.yml
name: CI/CD Pipeline

on:
  push:
    branches: [main, develop]
  pull_request:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Setup Node.js
        uses: actions/setup-node@v4
        with:
          node-version: '20'
          cache: 'npm'

      - name: Install dependencies
        run: npm ci

      - name: Run Cypress tests
        run: npm run test:cy

      - name: Run Playwright tests
        run: npx playwright test

  deploy:
    needs: test
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'
    steps:
      - uses: actions/checkout@v4

      - name: Deploy
        run: echo "🚀 plug in Vercel / your host here"
```

---

## `> certs --show`

[![Microsoft - Intro to Generative AI](https://img.shields.io/badge/Microsoft-Intro_to_Gen_AI-0078D4?style=flat-square&logo=microsoft)](https://learn.microsoft.com/api/achievements/share/en-us/PanithanAkepanithanpong-1982/4G33B3QK?sharingId=E581883C0E6610E1)

---

## `> interests`

- 🖥️ PC Hardware nerd
- 🎯 FPS Games — Valorant, CS2
- 🧙 Dota 2 (it never ends)
- 🎬 Video editing & content creation
- 📡 Streaming & live content

---

<div align="center">

*"still learning, still building, still ranking up."*

</div>
