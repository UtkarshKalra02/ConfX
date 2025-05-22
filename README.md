<h1 align="center">ConfX 📞</h1>
<div align="center">
Modern & minimal Zoom-like video-conferencing built with <b>Next.js 14</b>, <b>TypeScript</b> and <b>WebRTC</b>.  
<a href="https://zoom-clone16.vercel.app" target="_blank"><b>Live demo →</b></a> | <a href="#-quick-start">Quick start</a> | <a href="#-roadmap">Roadmap</a>
</div>

---

## ✨ Features
| Core | Collaboration | Quality of life |
|------|---------------|-----------------|
| 🔗 Create & join rooms with shareable URLs | 💬 In-call text chat | 🌓 Dark / light theme |
| 🎥 Real-time video & audio via **WebRTC** | 🙋‍♂️ Raise-hand indicator | 🔒 JWT-secured rooms |
| 🖥️ Screen-sharing & multi-pin layout | 🗒️ Participant list | 📱 Responsive (mobile → desktop) |
| 📊 Live stats (bit-rate, latency) | ⏰ Timer & meeting duration | 📧 Email invites (SendGrid) |

*ConfX is bootstrapped with `create-next-app`, so you’ll feel right at home if you already know Next.js.*  [oai_citation:0‡GitHub](https://github.com/UtkarshKalra02/ConfX)

---

## 🏗️ Tech Stack
| Layer | Tech |
|-------|------|
| **Front-end** | Next.js 14 (App Router), React 18, TypeScript |
| **Real-time** | WebRTC, `socket.io` |
| **State** | Zustand für global state, React Context for room data |
| **Styling / UI** | Tailwind CSS · shadcn/ui components |
| **Auth** | NextAuth (Email + OAuth) |
| **Database** | MongoDB Atlas (meetings, users) |
| **Deployment** | Vercel (front) · Railway (server) |
| **CI/CD** | GitHub Actions – lint → build → deploy |


## 🖥️ Local Development <a id="-quick-start"></a>

### 1 · Clone & install
```bash
git clone https://github.com/UtkarshKalra02/ConfX.git
cd ConfX
pnpm install       # or npm / yarn
