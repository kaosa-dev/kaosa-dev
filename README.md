<h1 align="center">İlteriş Günay</h1>

<p align="center">
  <b>Head Developer @ KEK Studio</b><br>
  Real-time multiplayer backends · browser MMOs · Unity developer tooling
</p>

<p align="center">
  <a href="https://x.com/ilterisgunay"><img src="https://img.shields.io/badge/X-@ilterisgunay-0d1117?style=flat-square&logo=x&logoColor=white&labelColor=0d1117" alt="X"></a>
  <a href="mailto:kaosacontact@gmail.com"><img src="https://img.shields.io/badge/Contact-kaosacontact-0d1117?style=flat-square&logo=maildotru&logoColor=white&labelColor=0d1117" alt="Email"></a>
  <img src="https://img.shields.io/badge/İstanbul-Türkiye-0d1117?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0d1117" alt="İstanbul, Türkiye">
</p>

---

I build the layer games run on: authoritative game servers, real-time networking, and the
editor tooling that keeps production moving. Shipped browser MMOs with live economies and
anti-cheat, and a commercial Unity extension used for localization QA.

- **Server-authoritative multiplayer** — tick loops, snapshot/delta fan-out, reconnect, anti-cheat
- **Backend systems** — auth, lobbies, inventory & economy, rate limiting, deployment
- **Unity tooling** — editor extensions that catch problems before they reach a build

---

## Selected work

### [realtime-game-server](https://github.com/kaosa-dev/realtime-game-server) · open source

Server-authoritative multiplayer backend — auth, lobbies, 20 TPS sessions, inventory/economy,
Redis presence & rate limits. The networking and progression layer competitive games sit on.

Measured on the live Docker stack with **200 concurrent WebSocket clients**:

| Clients | Tick rate | Input acks | Ack latency | Reconnects | Errors |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 200 / 200 | ~21.7 TPS | 118,600 / 118,600 | p50 14 ms · p95 35 ms · p99 56 ms | 40 / 40 | 0 |

`TypeScript` `Fastify` `ws` `PostgreSQL / Prisma` `Redis` `JWT` `Zod` `Vitest` `Docker` `GitHub Actions`

<br>

### LocUI — Text & Localization QA for Unity · commercial

A Unity editor extension that catches UI text which breaks before and after translation.
No crash server, no account, no background uploader — reports exist only when you send them.

→ [Bug reports & feedback](https://github.com/kaosa-dev/locui-feedback) · source stays private

`C#` `Unity Editor`

<br>

<details>
<summary><b>Haylord</b> — browser-based multiplayer farming MMO · live</summary>

<br>

Multiplayer backend, real-time networking, anti-cheat, economy & gameplay systems.

`Node.js` `Pixi.js` `WebSockets` `PostgreSQL`

> Source private — commercial ownership.

</details>

<details>
<summary><b>King's Tomb</b> — season-based browser MMORPG · completed</summary>

<br>

Server architecture, real-time multiplayer systems, anti-cheat, game economy, deployment & infrastructure.

`Node.js` `Three.js` `WebSockets` `PostgreSQL`

> Source private — commercial ownership. Project has concluded.

</details>

---

## Stack

**Languages**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Backend & real-time**<br>
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Client & engine**<br>
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![PixiJS](https://img.shields.io/badge/PixiJS-E22162?style=flat-square&logo=pixiv&logoColor=white)

**Infra**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
