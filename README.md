<div align="center">

<svg width="100%" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Dark background gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#050d1a;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0a1628;stop-opacity:1" />
    </linearGradient>
    <!-- Blue glow left -->
    <radialGradient id="glow-left" cx="20%" cy="70%" r="45%">
      <stop offset="0%" style="stop-color:#1565c0;stop-opacity:0.7" />
      <stop offset="100%" style="stop-color:#050d1a;stop-opacity:0" />
    </radialGradient>
    <!-- Blue glow right -->
    <radialGradient id="glow-right" cx="85%" cy="40%" r="40%">
      <stop offset="0%" style="stop-color:#0d47a1;stop-opacity:0.55" />
      <stop offset="100%" style="stop-color:#050d1a;stop-opacity:0" />
    </radialGradient>
    <!-- Accent gradient for shapes -->
    <linearGradient id="shape-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1976d2;stop-opacity:0.9" />
      <stop offset="100%" style="stop-color:#42a5f5;stop-opacity:0.4" />
    </linearGradient>
    <!-- Text shine -->
    <linearGradient id="text-shine" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:1" />
      <stop offset="60%" style="stop-color:#e3f2fd;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#90caf9;stop-opacity:0.9" />
    </linearGradient>
    <filter id="blur-glow">
      <feGaussianBlur stdDeviation="18" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="text-glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="banner-clip">
      <rect width="900" height="280" rx="14"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <g clip-path="url(#banner-clip)">
    <rect width="900" height="280" fill="url(#bg)"/>
    <rect width="900" height="280" fill="url(#glow-left)"/>
    <rect width="900" height="280" fill="url(#glow-right)"/>

    <!-- Geometric shapes top-left (dark blue angled panels) -->
    <polygon points="0,0 320,0 180,280 0,280" fill="#0d1f3c" opacity="0.7"/>
    <polygon points="0,0 220,0 100,280 0,280" fill="#0a1a35" opacity="0.8"/>

    <!-- Geometric shapes right (bright blue accent panels) -->
    <polygon points="680,0 900,0 900,280 820,280" fill="url(#shape-grad)" opacity="0.75"/>
    <polygon points="730,0 900,0 900,180" fill="#1565c0" opacity="0.5"/>
    <polygon points="900,100 900,280 820,280" fill="#42a5f5" opacity="0.25"/>

    <!-- Thin diagonal accent lines -->
    <line x1="160" y1="0" x2="0" y2="220" stroke="#1976d2" stroke-width="1.2" opacity="0.4"/>
    <line x1="260" y1="0" x2="80" y2="280" stroke="#1565c0" stroke-width="0.7" opacity="0.3"/>
    <line x1="750" y1="0" x2="900" y2="200" stroke="#42a5f5" stroke-width="1" opacity="0.35"/>

    <!-- Dot grid (subtle texture) -->
    <pattern id="dots" x="0" y="0" width="28" height="28" patternUnits="userSpaceOnUse">
      <circle cx="1" cy="1" r="1" fill="#1976d2" opacity="0.18"/>
    </pattern>
    <rect width="900" height="280" fill="url(#dots)"/>

    <!-- Main heading -->
    <text
      font-family="'Segoe UI', 'Arial Black', Arial, sans-serif"
      font-size="54"
      font-weight="800"
      letter-spacing="1"
      x="450" y="138"
      text-anchor="middle"
      fill="url(#text-shine)"
      filter="url(#text-glow)"
    >Hardiyanto Jaya Pranata</text>

    <!-- Subtitle -->
    <text
      font-family="'Segoe UI', Arial, sans-serif"
      font-size="19"
      font-weight="400"
      letter-spacing="3"
      x="450" y="185"
      text-anchor="middle"
      fill="#90caf9"
      opacity="0.92"
    >Senior Full-Stack Engineer  ·  DevOps Architect</text>

    <!-- Bottom accent line -->
    <rect x="300" y="210" width="300" height="2" rx="1" fill="url(#shape-grad)" opacity="0.7"/>

    <!-- Small tagline -->
    <text
      font-family="'Segoe UI', Arial, sans-serif"
      font-size="13"
      font-weight="300"
      letter-spacing="2"
      x="450" y="240"
      text-anchor="middle"
      fill="#64b5f6"
      opacity="0.7"
    >Building systems that scale, survive, and sleep well in production.</text>

  </g>
</svg>

</div>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hardiyanto_Jaya_Pranata-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/hardiyantonumber1)
[![Email](https://img.shields.io/badge/Email-hardiyanto%40email.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hardiyanto@email.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-hardiyantonumber1.dev-1565C0?style=flat-square&logo=vercel&logoColor=white)](https://hardiyantonumber1.dev)
[![GitHub](https://img.shields.io/badge/GitHub-hardiyantonumber1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hardiyantonumber1)

</div>

---

## 👤 About Me

I am a senior software engineer with deep expertise spanning the full product lifecycle — from pixel-precise frontend interfaces to distributed backend systems and production-grade cloud infrastructure.

With years of experience leading engineering initiatives across startups and enterprise environments, I bring both technical depth and architectural clarity to every project. I care about code quality, system reliability, and developer experience equally.

```text
🏡 Based in      Indonesia (UTC+7 / WIB)
💼 Speciality    Full-Stack Engineering + DevOps Architecture
🔭 Currently     Building scalable distributed systems
🌱 Exploring     Rust async runtimes & eBPF observability
💬 Ask me about  System design, CI/CD, performance engineering
```

---

## 🚀 GitHub Statistics

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=hardiyantonumber1&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e" />
&nbsp;&nbsp;
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hardiyantonumber1&layout=compact&theme=github_dark&hide_border=true&langs_count=7&bg_color=0d1117&title_color=58a6ff&text_color=8b949e" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=hardiyantonumber1&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />

</div>

---

## ⚡ Activity Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=hardiyantonumber1&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&area_color=1f6feb)](https://github.com/hardiyantonumber1)

</div>

---

## 🛠️ Tech Stack

### ▸ Languages

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### ▸ Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)

### ▸ Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)

### ▸ DevOps & Cloud

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### ▸ Databases & Messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### ▸ Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)
![Elastic](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)

---

## 📌 Featured Projects

| Project                    | Stack                           | Description                                              |
| -------------------------- | ------------------------------- | -------------------------------------------------------- |
| 🦀 **zero-latency-api**    | Rust · Tokio · gRPC             | High-performance async microservice — sub-ms P99 latency |
| ☸️ **k8s-gitops-platform** | Kubernetes · ArgoCD · Terraform | Production GitOps platform with zero-downtime delivery   |
| ⚡ **realtime-dashboard**  | Next.js · WebSocket · Redis     | Live analytics handling 100k+ concurrent connections     |
| 🔐 **auth-fortress**       | Go · JWT · OAuth2 · PostgreSQL  | Distributed auth service with rate-limiting & audit logs |
| 🛠 **devpipeline**         | GitHub Actions · Docker · Bash  | Opinionated CI/CD framework powering 20+ projects        |

---

## 📊 Weekly Coding Breakdown

```text
Rust           ████████████░░░░░░░░░   44%
Go             ████████░░░░░░░░░░░░░   30%
TypeScript     █████░░░░░░░░░░░░░░░░   19%
YAML / HCL     ██░░░░░░░░░░░░░░░░░░░    7%
```

---

## 🧠 Engineering Manifesto

```rust
fn hardiyanto_principles() -> Vec<&'static str> {
    vec![
        "Code is communication  → write for the 3am on-call engineer",
        "Infra is product       → your CI/CD pipeline is a first-class feature",
        "Frontend is not decor  → a 200ms render is a real business decision",
        "Backend is not magic   → every abstraction leaks. know the metal",
        "DevOps is culture      → ship fast, break nothing, sleep well",
        "Complexity is the enemy→ if you can't explain it, you don't own it",
    ]
}
```

---

## 🏆 GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=hardiyantonumber1&theme=algolia&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/hardiyantonumber1)

</div>

---

<div align="center">

📍 Indonesia &nbsp;·&nbsp; ⏱ UTC+7 (WIB) &nbsp;·&nbsp; 💬 Open to collabs & consulting

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/hardiyantonumber1)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hardiyanto@email.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-1565C0?style=flat-square&logo=vercel&logoColor=white)](https://hardiyantonumber1.dev)

![Profile Views](https://komarev.com/ghpvc/?username=hardiyantonumber1&color=1565c0&style=flat-square&label=Profile+Views)

---

_"The best infrastructure is the one nobody talks about — because it just works."_

</div>
