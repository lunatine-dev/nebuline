# 🌌 nebuline

> ✨ Secure socket relay & API gateway to control your VRChat bots remotely

![Node.js](https://img.shields.io/badge/Node.js-20.x-green?logo=node.js)
![Socket.io](https://img.shields.io/badge/Socket.io-%E2%8C%A8%EF%B8%8F-lightgrey?logo=socket.io)
![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Issues](https://img.shields.io/github/issues/lunatine-dev/nebuline)
![Stars](https://img.shields.io/github/stars/lunatine-dev/nebuline?style=social)

## 🚀 Purpose

`nebuline` acts as a middleman between the internet and your VRChat bots.  
It forwards authenticated commands to your bots over a secure socket connection.

---

## ⚙️ Technical stack

-   **Backend**: Node.js + Socket.io
-   **Security**: API keys & token-based auth
-   **Database**: MongoDB (bot registrations & users)

---

## 📦 Installation & Deployment

```bash
git clone https://github.com/lunatine-dev/nebuline.git
cd nebuline
pnpm install
# Configure your .env (API keys, Mongo URI, etc.)
pnpm run start
```

## 📦 Related projects

-   **[nebuline-frontend](https://github.com/lunatine-dev/nebuline-frontend)** – SvelteKit dashboard to manage bots
-   **[nebuline-host](https://github.com/lunatine-dev/nebuline-host)** – Local client to connect your VRChat bots

## ⚠️ Disclaimer

> ✨ `nebuline` is a socket relay & API gateway built purely for **personal use, entertainment, and educational purposes**.
> ❌ It must _not_ be used to spam, harass, or harm others on VRChat or elsewhere.
> 🛡️ By using this software, you agree to follow VRChat’s Terms of Service and use it responsibly.
> The author(s) are not responsible for any misuse.
