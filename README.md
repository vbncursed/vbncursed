<h1 align="center">vbncursed</h1>
<p align="center"><b>Go Backend Engineer</b> · gRPC · PostgreSQL · Redis · Kafka · React on the side</p>

<p align="center">
  <a href="https://vbncursed.fun"><img src="https://img.shields.io/badge/portfolio-vbncursed.fun-171717?style=for-the-badge" alt="Portfolio" /></a>
  <a href="mailto:enrbyltw@gmail.com"><img src="https://img.shields.io/badge/email-enrbyltw%40gmail.com-7B3F9A?style=for-the-badge" alt="Email" /></a>
  <a href="https://t.me/vbncursed"><img src="https://img.shields.io/badge/telegram-%40vbncursed-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
</p>

---

### 💫 About

Go-разработчик с фокусом на backend и микросервисы. Проектирую gRPC и REST API, держу PostgreSQL под нагрузкой, разбираюсь в runtime Go: GC, горутины, профилирование через pprof. Сейчас в **Газпромнефть НТЦ** закрываю и фронтенд на React/TypeScript – миграция legacy-десктопа потребовала fullstack-работы.

Ценю инженерную дисциплину: тесты, наблюдаемость, чистые контракты.

- 🛠 **Сейчас:** миграция .NET-стека (WCF + WPF) на **15 gRPC-сервисов** на Go и веб-фронт на React 19
- 🧪 **Стек дома:** Go, PostgreSQL, Kafka, Redis, Docker, Kubernetes
- 📚 **Интересуюсь:** распределенными системами, performance engineering
- 🌍 Тюмень / удаленно / релокация

---

### 💻 Tech stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)

![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=google&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=for-the-badge&logo=google&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-fc6d26?style=for-the-badge&logo=git&logoColor=white)

---

### 🚀 Highlight projects

| Project | Stack | What it does |
|---|---|---|
| **[Experra2](https://vbncursed.fun/projects/experra2)** | Go · gRPC · PostgreSQL · React 19 | Миграция .NET-стека (WCF + WPF) на 15 gRPC-сервисов (~225k LOC Go, 127 proto) под единым `grpc-gateway v2`. p95 ~3×, RAM на сервис ~70 МБ vs ~350 МБ на легаси. |
| **[MPC-2FA](https://vbncursed.fun/projects/mpc-2fa)** | Go · Shamir SSS · gRPC · Next.js 16 | Распределенное хранение TOTP-секретов: Shamir 2-of-3 в GF(256), AES-256-GCM, mTLS, JWT RS256. Shamir и TOTP (RFC 6238) написаны с нуля. |
| **[Rask.pro](https://vbncursed.fun/projects/rask)** | Go · Kafka · PostgreSQL · ClickHouse | Аналитика продавцов маркетплейсов. p95 ~8×, образы Docker ~25×, GC-паузы 120 → 15 мс. |
| **[Monopoly Tracker](https://vbncursed.fun/projects/monopoly-tracker)** | Swift 6.2 · SwiftUI · SwiftData | iOS-приложение для учета партии. Журнал транзакций как single source of truth, cold launch 305 мс, бандл 3.4 МБ. |

Полное портфолио: **[vbncursed.fun](https://vbncursed.fun)**

---

### 📊 GitHub stats

![](https://github-readme-stats.vercel.app/api?username=vbncursed&hide_border=true&include_all_commits=true&count_private=true&bg_color=171717&text_color=fafafa&icon_color=7B3F9A&title_color=ffffff)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=vbncursed&hide_border=true&layout=compact&langs_count=8&bg_color=171717&text_color=fafafa&title_color=ffffff)

![](https://streak-stats.demolab.com?user=vbncursed&hide_border=true&background=171717&stroke=2a2a2a&ring=7B3F9A&fire=7B3F9A&currStreakLabel=fafafa&sideLabels=fafafa&dates=a1a1a1&currStreakNum=fafafa&sideNums=fafafa)

---

<sub>Brand colours follow my portfolio: ink `#171717` · violet `#7B3F9A` · canvas `#fafafa`.</sub>
