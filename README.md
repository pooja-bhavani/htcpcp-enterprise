# 🫖 HTCPCP/2.0 Enterprise

> Production-grade observability for your imaginary tea brewing infrastructure.

[![RFC 2324](https://img.shields.io/badge/RFC-2324-brown?style=flat-square)](https://www.rfc-editor.org/rfc/rfc2324)
[![HTTP 418](https://img.shields.io/badge/HTTP-418%20I'm%20a%20Teapot-red?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/418)
[![Coffee](https://img.shields.io/badge/Coffee-REJECTED-red?style=flat-square)]()
[![Tea](https://img.shields.io/badge/Tea-ACCEPTED-green?style=flat-square)]()
[![Uptime](https://img.shields.io/badge/Uptime-99.97%25-green?style=flat-square)]()
[![Larry Approved](https://img.shields.io/badge/Larry%20Masinter-Approved-C4934A?style=flat-square)]()

**[→ Live Demo]([https://your-deployed-link-here](https://pooja-bhavani.github.io/htcpcp-enterprise/))**

---

## What is this?

In 1998, **Larry Masinter** and a group of engineers published [RFC 2324](https://www.rfc-editor.org/rfc/rfc2324) — the *Hyper Text Coffee Pot Control Protocol* (HTCPCP). It defined a new internet protocol for controlling, monitoring, and diagnosing coffee pots over a network.

Inside it lived HTTP status code **418: I'm a Teapot** — returned whenever a teapot is asked to brew coffee, because a teapot is not a coffee machine and will not pretend to be one.

It was an April Fools' joke. Status 418 was a joke inside the joke.

Then the internet loved it so much it made it real. Node.js has it. Go has it. Python has it. curl has it. It has survived every attempt to remove it from the spec.

So naturally, the next step was to build a **full enterprise Kubernetes monitoring dashboard** for it.

---

## Features

### Core Dashboard
- 📊 **Real-time metrics** — brews, 418 errors, steep time, kettle saturation
- 🫖 **Animated teapot** with live brew progress bar cycling through stages
- 🟢 **Pod health indicators** — `earl-grey-0`, `english-brkfst-1`, `oolong-2`, `chamomile-3`
- 📋 **Live request log** — streaming HTCPCP/2.0 requests with timestamps
- 🌡️ **Temperature telemetry** — real-time kettle temperature chart
- ⚙️ **Cluster controls** — toggle Auto-Steep, Reject Coffee, Dark Mode Tea, AI Mode

### The Deploy Button
Clicking **Deploy to Production** will always return:

```
418 I'm a Teapot

Error: COFFEE_REQUESTED_FROM_TEAPOT
  at deploy.js:418:1 (I'm a teapot)
  Stack: [empty — tea spilled on it]
```

Always. No exceptions. As the RFC intended.

### AI-Powered Teapot (Real API Calls)
Every brew and every failed deployment triggers a **live AI response** — Claude responds in character as the teapot, citing RFC 2324, celebrating successful steeps, or furiously rejecting coffee requests. Every response is unique.

### Sound Effects
Built entirely with the **Web Audio API** — no external audio files:
- 🫧 Bubbling sounds while brewing
- 📯 Sad trombone on every 418 deploy failure
- 🎵 Victory chime when brew completes

### Easter Eggs
Two hidden easter eggs for the developers who look:

**Konami Code** — Type `↑ ↑ ↓ ↓ ← → ← → B A` to unlock **Ultra Premium Earl Grey Mode**

**Coffee Search** — Type `coffee` into the cluster search bar and face the consequences

---

## Tech Stack

| Thing | What it is |
|-------|-----------|
| HTML/CSS/JS | The entire app — zero dependencies, zero build step |
| Web Audio API | All sound effects, synthesised in the browser |
| Anthropic API | Live AI teapot responses on brew and deploy events |
| Space Mono | The font that makes everything look like a terminal |
| RFC 2324 | The only dependency that matters |

**Total dependencies:** 0 npm packages. 0 frameworks. 1 RFC.

---

## Running It

```bash
# Option 1: just open it
open index.html

# Option 2: serve it locally
npx serve .

# Option 3: deploy it
# Drag index.html to https://app.netlify.com/drop
# Done. Larry would want it this way.
```

---

## HTCPCP Request Reference

| Method | Endpoint | Response | Notes |
|--------|----------|----------|-------|
| `BREW` | `/pot/earl-grey` | `200 OK` | Steep: 4m18s |
| `BREW` | `/pot/oolong` | `200 OK` | Steep: 4m18s |
| `BREW` | `/pot/coffee` | `418 I'm a Teapot` | Working as intended |
| `POST` | `/espresso` | `418 I'm a Teapot` | Nice try |
| `GET` | `/healthz` | `200 OK` | Adequately steeped |
| `*` | `/coffee/*` | `418 I'm a Teapot` | Always |
| `*` | `/java/*` | `418 I'm a Teapot` | Especially Java |

---

## Cluster Architecture

```
tea-production namespace
├── earl-grey-0        [Running]   ████████████ 100% steeped
├── english-brkfst-1   [Running]   ████████████ 100% steeped
├── oolong-2           [Steeping]  ██████░░░░░░  58% steeped
└── chamomile-3        [Running]   ████████████ 100% steeped

Ingress: rejects all /coffee/* routes with 418
HPA: scales chamomile at bedtime (EU region)
Network policy: DENY espresso machines on port 5000
```

---

## FAQ

**Q: Does the Deploy button ever work?**
A: No. That's the point.

**Q: What if I need to deploy coffee?**
A: You don't. You need tea.

**Q: Is HTTP 418 a real status code?**
A: It's more real than most things. Node.js, Go, Python, curl, and half the internet have implemented it. Several attempts to remove it from the HTTP spec have been blocked by the internet's collective will.

**Q: Who is Larry Masinter?**
A: The hero who gave us RFC 2324 in 1998. This dashboard is dedicated to him.

**Q: Why does it use AI?**
A: Because an enterprise-grade teapot deserves enterprise-grade snark.

**Q: Can I fork this?**
A: Yes. But if your fork adds coffee support, you will return 418.

---

## License

MIT — but any use of this code to brew coffee will result in an automatic `418 I'm a Teapot` response from the universe.

---

*Built for the [DEV April Fools Challenge 2026](https://dev.to/challenges/aprilfools-2026)*

*RFC 2324 · HTCPCP/2.0 · HTTP 418 · Larry Masinter Memorial Cluster*

*No coffee was brewed during the making of this project. Several attempts were made. All returned 418.*
