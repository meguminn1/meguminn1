𓂃 ✦ meguminn1 ✦ 𓂃

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=34&duration=3000&pause=1000&color=FFB7C5&center=true&vCenter=true&width=900&lines=Hi+👋,+I'm+Megumin;Backend+Engineer+%7C+System+Designer;Building+Scalable+%26+Reliable+Systems;Quiet+but+Impactful" />
</h1><p align="center">
  <img src="https://i.postimg.cc/HkTD2wWn/meguminn1.jpg" alt="banner" width="100%" style="border-radius:16px;" />
</p><p align="center">
  <img src="https://img.shields.io/github/followers/meguminn1?style=for-the-badge&color=FFB7C5&labelColor=1f1f1f" />
  <img src="https://komarev.com/ghpvc/?username=meguminn1&style=for-the-badge&color=FFB7C5&labelColor=1f1f1f" />
  <img src="https://img.shields.io/badge/Focus-System%20Design-FFB7C5?style=for-the-badge&labelColor=1f1f1f" />
</p>---

🌸 Philosophy

«“Build simple systems. Scale only when needed.
But design it right from the start.”»

- 🧠 Think in flows, not functions
- ⚙️ Prefer stateless & scalable systems
- ⚡ Optimize for latency & UX
- 🧩 Every component must have clear responsibility

---

🏗️ System Design — QrtzMusic (Real Architecture)

flowchart LR

%% CLIENT
subgraph CLIENT
U[User]
end

%% EDGE
subgraph EDGE
CDN[CDN / Edge Cache]
WAF[WAF / Protection]
LB[Load Balancer]
end

%% APP
subgraph APP
FE[Next.js Frontend]
GW[API Gateway / BFF]
end

%% SERVICES
subgraph SERVICES
STREAM[Streaming Service]
SEARCH[Search Aggregator]
AI[Kobeni AI Service]
end

%% DATA-LIKE
subgraph DATA
CACHE[(In-memory Cache)]
QUEUE[(Queue)]
end

%% ASYNC
subgraph ASYNC
WORKER[Worker / Processor]
end

%% EXTERNAL
subgraph EXT
YT[YouTube API]
YTM[YTMusic]
INN[Innertube]
INV[Invidious]
LLM[Gemini API]
end

%% FLOW
U --> CDN --> WAF --> LB
LB --> FE
LB --> GW

GW --> STREAM
GW --> SEARCH
GW --> AI

STREAM --> CACHE
STREAM --> QUEUE

SEARCH --> YT
SEARCH --> YTM
SEARCH --> INN
SEARCH --> INV

AI --> LLM

QUEUE --> WORKER
WORKER --> YT

---

📊 System Metrics

<p align="center">
  <img src="https://img.shields.io/badge/Uptime-99%25-FFB7C5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Avg%20Latency-120~180ms-6CE7F5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cold%20Start-~400ms-a78bfa?style=for-the-badge" />
</p><p align="center">
  <img src="https://img.shields.io/badge/Architecture-Serverless-ff8fb1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Storage-Client--Side%20(localStorage)-6366f1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scaling-Auto%20(Vercel)-22c55e?style=for-the-badge" />
</p>---

📈 Performance & Load Behavior

xychart-beta
    title "Latency Distribution (ms)"
    x-axis ["P50","P75","P90","P99"]
    y-axis 0 --> 300
    line [110,140,180,260]

xychart-beta
    title "Traffic Pattern (Relative)"
    x-axis ["Mon","Tue","Wed","Thu","Fri","Sat","Sun"]
    y-axis 0 --> 100
    bar [40,50,55,60,75,95,85]

---

🚀 Deployment (Production Thinking)

flowchart LR
User --> Edge[Vercel Edge Network]
Edge --> FE[Next.js App]

FE --> API[/api routes]

API --> YT[YouTube]
API --> YTM[YTMusic]
API --> INN[Innertube]
API --> INV[Invidious]

FE --> LS[localStorage]

⚙️ Infra Stack

- Platform: Vercel (Edge + Serverless Functions)
- Runtime: Next.js App Router
- Storage: localStorage (client-first architecture)
- Streaming: proxy API ("/api/stream")
- AI: Gemini API
- Caching: browser + edge layer

---

🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,ts,react,nextjs,tailwind,vercel,docker" />
</p>---

🚀 Featured Work

🎧 QrtzMusic

Music platform tanpa login, tanpa DB, fully client-driven
🔗 https://qrtzmusic.web.id/

🌸 Qrtznime

UI/UX-focused anime web experience

---

🧩 What I Actually Do

- System design & architecture
- Backend engineering
- Performance optimization
- Turning ideas → scalable systems

---

🏆 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=meguminn1&show_icons=true&theme=transparent&hide_border=true&title_color=FFB7C5" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=meguminn1&layout=compact&theme=transparent&hide_border=true&title_color=FFB7C5" height="170"/>
</p>---

🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/meguminn1/meguminn1/output/github-contribution-grid-snake-dark.svg" />
</p>---

🌐 Connect

<p align="center">
  <a href="https://t.me/rynaaqrtz">
    <img src="https://img.shields.io/badge/Telegram-Contact-2CA5E0?style=for-the-badge&logo=telegram" />
  </a>
  <a href="https://github.com/meguminn1">
    <img src="https://img.shields.io/badge/GitHub-Profile-121011?style=for-the-badge&logo=github" />
  </a>
</p>---

<p align="center">
  <img src="https://media.tenor.com/r_z_2zN0K_wAAAAC/kobeni-double-peace.gif" width="260" style="border-radius:12px;" />
</p><p align="center">
  <strong>Build simple. Scale smart. Stay reliable.</strong><br/>
  <sub>𓂃 ✦ meguminn1 ✦ 𓂃</sub>
</p>
---