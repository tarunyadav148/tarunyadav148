<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:7c6af7&height=220&section=header&text=Tarun%20Singh%20Yadav&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineer%20%7C%20Distributed%20Systems%20%7C%2070M%2B%20records%20per%20scan&descSize=16&descAlignY=55&descColor=a0a0ff" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=7C6AF7&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=70&lines=%E2%9A%A1+Building+systems+that+handle+millions;%F0%9F%94%A5+Kafka+%C2%B7+Redis+%C2%B7+Spring+Boot+%C2%B7+AWS+%C2%B7+K8s" alt="Typing SVG" />

<p>
  <a href="https://linkedin.com/in/tarunyadav148"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:tarunyadav148@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/tarunyadav148"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

</div>

<br/>

## `$ whoami`

```js
{
  name:        "Tarun Singh Yadav",
  role:        "Software Engineer @ ArmorCode Inc.",
  education:   "NIT Kurukshetra '24 · CGPA 9.07",
  focus:       "High-throughput backends · Distributed infrastructure",
  
  highlights: [
    "Pipelines processing 70M+ records per scan",
    "Eliminated production OOM failures",
    "Two-tier caching → sub-second reads at scale",
    "7-day sprint cycles, shipped every single one"
  ]
}
```

<br/>

## `$ tech --stack`

<div align="center">

**Backend & Infra**

<img src="https://skillicons.dev/icons?i=java,spring,kafka,redis,aws,docker,kubernetes,postgres,mongodb&theme=dark" />

**Frontend & Languages**

<img src="https://skillicons.dev/icons?i=react,angular,nodejs,ts,python,cpp&theme=dark" />

</div>

<br/>

---

<br/>

## `$ ls ~/projects`

<br/>

<div align="center">

> ### 🏗️ Featured: Systems & Backend

</div>

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">⚡ <a href="https://github.com/tarunyadav148/jeduler">Jeduler</a></h3>
<p align="center"><strong>Distributed Job Scheduler</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
</p>

```
┌─────────────────────────────────┐
│  Scheduling Engine (Spring Boot)│
│  ┌───────┐ ┌───────┐ ┌───────┐ │
│  │ Redis │ │ Kafka │ │Postgre│ │
│  │counter│ │topics │ │  SQL  │ │
│  └───┬───┘ └───┬───┘ └───┬───┘ │
│      └─────────┴─────────┘     │
│      Concurrency Maximizer      │
└─────────────────────────────────┘
```

- **Distributed scheduler** — event-driven engine
- **Kafka** per-type topics → worker scaling & ordering
- **Redis** atomic counters — sub-ms concurrency checks
- **Redis TTL** heartbeat — auto-detect dead workers
- Greedy fill algorithm — max slot utilization
- Multi-dim limits: tenant × type × global
- `docker-compose up` → full stack, zero config

</td>
<td width="50%" valign="top">

<h3 align="center">💬 <a href="https://github.com/tarunyadav148/ChitChat">ChitChat</a></h3>
<p align="center"><strong>Real-time Chat Platform</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

```
┌──────────────────────────────┐
│  React UI (Discord-style)    │
│         ↕ Socket.IO          │
│  Node.js ←→ MongoDB          │
│  • Rooms  • DMs  • Presence  │
└──────────────────────────────┘
```

- Public rooms + private 1-on-1 DMs
- Live online/offline presence indicators
- Fully containerized with Docker Compose
- Dark glassmorphism UI

</td>
</tr>
</table>

<br/>

<div align="center">

> ### 🛠️ Apps & Tools

</div>

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">✅ <a href="https://github.com/tarunyadav148/taskflow-tarunyadav">TaskFlow</a></h3>
<p align="center"><strong>Production-grade Task API</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

- RESTful backend with full CRUD
- Containerized — `docker compose up`
- Clean layered architecture

</td>
<td width="50%" valign="top">

<h3 align="center">🌤️ <a href="https://github.com/tarunyadav148/weather">Weather App</a></h3>
<p align="center"><strong>Live Weather + City Autocomplete</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/OpenWeatherMap-E96E50?style=flat-square&logo=icloud&logoColor=white"/>
</p>

- Geolocation auto-detect
- Animated SVG rings for humidity & UVI
- Zero dependencies, zero build step

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center">✅ <a href="https://github.com/tarunyadav148/Task-Tracker">Task Tracker</a></h3>
<p align="center"><strong>Firebase Task Manager + Social Login</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
</p>

- Google / Facebook / GitHub OAuth
- Real-time sync via Firebase
- [🔗 Live Demo](https://tarunyadav148.github.io/Task-Tracker/)

</td>
<td width="50%" valign="top">

<h3 align="center">❌⭕ <a href="https://github.com/tarunyadav148/Tic-Tac-Toe">Tic-Tac-Toe</a></h3>
<p align="center"><strong>C++ LLD Design Showcase</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/C++14-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
<img src="https://img.shields.io/badge/OOP-purple?style=flat-square"/>
<img src="https://img.shields.io/badge/Makefile-064F8C?style=flat-square&logo=gnu&logoColor=white"/>
</p>

- MVC + Facade pattern
- **O(1) win detection** via counters
- 7 LLD patterns documented

</td>
</tr>
</table>

<br/>

<div align="center">

> ### 🤖 Fun Bots

</div>

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">🎩 <a href="https://github.com/tarunyadav148/SortingHatBot">SortingHatBot</a></h3>
<p align="center"><strong>Hogwarts Sorting Discord Bot</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/discord.py-5865F2?style=flat-square&logo=discord&logoColor=white"/>
</p>

- Sorts users into Hogwarts houses
- Persistent memory per user
- Rich embeds with house crests

</td>
<td width="50%" valign="top">

<h3 align="center">📊 <a href="https://github.com/tarunyadav148?tab=repositories">More on GitHub →</a></h3>
<p align="center"><strong>Always shipping something new.</strong></p>

<br/>
<p align="center">
<img src="https://img.shields.io/github/followers/tarunyadav148?style=flat-square&color=7c6af7&label=Followers"/>
<img src="https://img.shields.io/github/stars/tarunyadav148?style=flat-square&color=7c6af7&affiliations=OWNER&label=Stars"/>
</p>

</td>
</tr>
</table>

<br/>

---

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=tarunyadav148&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph" width="95%"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=tarunyadav148&color=7c6af7&style=for-the-badge&label=PROFILE+VIEWS"/>

<br/><br/>

```
"Build things that scale. Fix things that break. Ship things that matter."
```

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:7c6af7&height=120&section=footer" width="100%"/>
