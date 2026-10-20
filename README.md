# Hey, I'm Dotan 👋
### Full-Stack Developer | Python & Node.js 

I like building things from scratch — whether it's a web app, a mobile app,
a game, or something that scrapes the internet at 2am for no good reason.

My stack spans the full product: frontend to backend, databases to
deployment. I've also built mobile applications (that are currently published on Google Play), and lately I've been
going deep on Python — LLMs, AI, web scraping, computer vision, and
whatever interesting problem shows up next.

🥋 Before code, there was judo — I'm a former **Israeli National Judo Team** athlete
(Israeli Champion, competed in Europe). I learned to code between training sessions,
and the same discipline carried over: show up every day, get a little better.

<!-- I care about clean code and solid architecture. Not because someone
told me to, but because I've read enough messy code to know the difference. -->

> Most of my projects are private for now — they'll go public when
> they're ready. I'm not in a rush, I'm in a process. 🚧

---

## ⭐ Featured Projects

### [AllyCat](https://www.npmjs.com/package/allycat) — Accessibility CLI Analyzer
> Source-first accessibility analyzer for the web — built for developers, not auditors.

[![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/allycat)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AllyCatHQ/allycat-core)
[![npm version](https://img.shields.io/npm/v/allycat?style=flat-square&color=CB3837&label=version)](https://www.npmjs.com/package/allycat)
[![npm downloads](https://img.shields.io/npm/dt/allycat?style=flat-square&label=downloads)](https://www.npmjs.com/package/allycat)

<p align="center">
  <img src="https://raw.githubusercontent.com/AllyCatHQ/allycat-core/main/assets/demo-optimize.gif" width="720" alt="AllyCat scanning a project in the terminal and reporting accessibility issues with exact file and line numbers">
</p>

- **2,500+ npm downloads** — 1,000+ of them in the first 1.5 weeks after launch
- Scans JSX/TSX, Vue, Angular & HTML **without a running server** — exact line numbers, zero build tools required
- `allycat fix` hands the found issues straight to **Claude Code** in a new terminal to fix them
- Watch mode, `--baseline` flag, CI gates, WCAG 2.1 / 2.2 AA via axe-core
- CI on Ubuntu / macOS / Windows with GitHub Actions, published with npm Trusted Publishing
- Built with Node.js, Playwright, JSDOM, Babel, Chokidar, ESM
- Open source under the **[AllyCatHQ](https://github.com/AllyCatHQ)** GitHub org

### [Dotmarket](https://github.com/dotcomico/dotmarket) — Full-Stack Supermarket + AI Assistant
> A full online supermarket: a customer storefront and a complete admin back office.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dotcomico/dotmarket)

<table>
<tr>
<td width="50%"><img src="https://raw.githubusercontent.com/dotcomico/dotmarket/main/media/screenshots/cart-checkout.gif" width="100%" alt="Adding products to the cart and going through checkout in the Dotmarket storefront"></td>
<td width="50%"><img src="https://raw.githubusercontent.com/dotcomico/dotmarket/main/media/screenshots/admin-product-crud.gif" width="100%" alt="Creating and editing a product in the Dotmarket admin back office"></td>
</tr>
<tr>
<td align="center"><sub><b>Storefront</b> — cart & checkout</sub></td>
<td align="center"><sub><b>Admin</b> — product management</sub></td>
</tr>
</table>

- **React 19 + TypeScript** frontend (Vite, Zustand, React Router 7)
- **Flask REST API** — layered routes → services → models, JWT auth + role-based access
- **AI chat assistant** — a FastAPI service runs an LLM (local Ollama) that calls an **MCP server** to answer with real product data
- Runs as a 6-service **Docker Compose** stack behind an nginx reverse proxy
- Repos: [workspace](https://github.com/dotcomico/dotmarket) · [client](https://github.com/dotcomico/dotmarket-client) · [server](https://github.com/dotcomico/dotmarket-server)

---

## 📱 Live on Google Play

<table>
<tr>
<td width="50%" valign="top">
<h3><img src="assets/quicksend-icon.png" width="28" align="center" alt=""> <a href="https://play.google.com/store/apps/details?id=com.dotcom.quicksendwhatsapp">Quick Send – Direct Chat</a></h3>
<a href="https://play.google.com/store/apps/details?id=com.dotcom.quicksendwhatsapp"><img src="https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=googleplay&logoColor=white" alt="Get it on Google Play"></a>
<img src="https://img.shields.io/badge/source-private-lightgrey?style=flat-square&logo=github" alt="Source code is private">
<br><br>
Send a WhatsApp message to a number without saving it as a contact.
<br><br>
<img src="assets/quicksend-send.png" width="48%" alt="Quick Send home screen: type a number and send a WhatsApp message without saving the contact">
<img src="assets/quicksend-widget.png" width="48%" alt="Quick Send floating widget shown over the phone home screen">
<br>
<sub>Floating widget (Foreground Service) · WhatsApp Business support · message history & templates · EN/HE · dark mode</sub>
<br>
<sub><b>Java · Android · Material Design 3</b> · 100+ downloads</sub>
</td>
<td width="50%" valign="top">
<h3><img src="assets/kashnik-icon.png" width="28" align="center" alt=""> <a href="https://play.google.com/store/apps/details?id=com.myappname.kashniks">Kashnik</a></h3>
<a href="https://play.google.com/store/apps/details?id=com.myappname.kashniks"><img src="https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=googleplay&logoColor=white" alt="Get it on Google Play"></a>
<img src="https://img.shields.io/badge/source-private-lightgrey?style=flat-square&logo=github" alt="Source code is private">
<br><br>
An indoor guide for Kiryat Sharet High School (Holon), used by real students.
<br><br>
<img src="assets/kashnik-nav.png" width="48%" alt="Kashnik directions screen with photo-based navigation between classrooms">
<img src="assets/kashnik-home.png" width="48%" alt="Kashnik screen for saving an encrypted locker code">
<br>
<sub>~44 rooms mapped by hand with annotated photo directions · weekly class schedule · encrypted locker codes · Hebrew UI</sub>
<br>
<sub><b>Java · Android · Material Design 3</b> · 50+ downloads</sub>
</td>
</tr>
</table>

---

## 🧪 More Public Projects

### [Crypto Tracker](https://github.com/dotcomico/crypto)
[![Live Demo](https://img.shields.io/badge/Live_Demo-2ea44f?style=flat-square&logo=githubpages&logoColor=white)](https://dotcomico.github.io/crypto/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dotcomico/crypto)

Live prices for the top 100 coins in USD / EUR / ILS, search, and a personal 5-coin watchlist. Vanilla JavaScript (ES modules), jQuery and Bootstrap 5 on the CoinGecko API, with client-side caching to keep API calls low.

<img src="https://raw.githubusercontent.com/dotcomico/crypto/main/docs/screenshots/home.png" width="600" alt="Crypto Tracker home screen with a list of coin cards">

### [Sticky Notes Todo](https://github.com/dotcomico/sticky-notes-todo)
[![Live Demo](https://img.shields.io/badge/Live_Demo-2ea44f?style=flat-square&logo=githubpages&logoColor=white)](https://dotcomico.github.io/sticky-notes-todo/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dotcomico/sticky-notes-todo)

A task board that looks like a corkboard covered in sticky notes. Plain HTML, CSS and JavaScript — no frameworks, no build step.

<img src="https://raw.githubusercontent.com/dotcomico/sticky-notes-todo/main/docs/screenshots/desktop.jpg" width="600" alt="Sticky Notes Todo board with colorful notes pinned on a corkboard">

---

## 🛠️ My Tech Stack

### Frontend & UI
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

### AI & LLMs
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Ollama](https://img.shields.io/badge/ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

### Python Ecosystem
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![PyQt6](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/playwright-%232EAD33.svg?style=for-the-badge&logo=playwright&logoColor=white)

*Also worked with: OpenCV, Pandas, Selenium, MediaPipe, BeautifulSoup, Scrapy, LangChain, OpenAI API, WebSockets, WhatsApp Bots*

### Databases
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

### Mobile & Game Dev
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white)
![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)

### Tools & DevOps
![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

---
<!-- 
## 🧠 Development Philosophy

I don't just write features — I stress-test them. My default mindset is
**"what could go wrong here?"**, which means separate test suites for edge
cases, not just the happy path.

- **Modular by default** — components and modules that don't fight each other
- **Edge case first** — null values, overflows, unexpected inputs are features, not surprises
- **Clean > clever** — if it needs a comment to explain what it does, it needs a rewrite

---
 -->
## 📊 GitHub Stats
*(Most of my work lives in private repos — these numbers are just the tip)*

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Dotcomico&show_icons=true&theme=tokyonight&count_private=true&cache_seconds=1800" alt="GitHub Stats" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dotcomico&layout=compact&theme=tokyonight&hide=html,css" alt="Top Languages" height="180" />
</p>

---
## 📫 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dotan-siman-tov)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dotan.simantov.dev@gmail.com)
[![npm](https://img.shields.io/badge/npm-allycat-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/allycat)
