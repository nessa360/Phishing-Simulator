# PhishGuard — Phishing Awareness Simulator

A browser-based phishing awareness training tool that teaches users how to spot phishing emails through interactive simulation and instant feedback.

## Live Demo

🔗 [https://YOUR_USERNAME.github.io/Phishing-Simulator/](https://YOUR_USERNAME.github.io/Phishing-Simulator/)

---

## What It Does

PhishGuard presents users with 10 realistic fake emails — some phishing, some legitimate — and asks them to identify which is which. After each decision, the app explains the reasoning and highlights the specific red flags present in that email.

### The three sections

| Section | Description |
|---|---|
| 🎓 Training | Learn the 6 most common phishing red flags before you start |
| 📧 Simulator | Read 10 emails and decide: phishing or legitimate? |
| 📊 Results | See your score, accuracy, and a full review of every email |

---

## Features

- 10 hand-crafted email scenarios (PayPal, Microsoft, DHL, GitHub, Netflix, Spotify, HR scams, and more)
- Instant feedback with explanations after every answer
- Red flag tags that highlight exactly what to look for
- Animated score ring and accuracy stats on the results screen
- Full email review at the end showing correct answers and explanations
- No backend, no dependencies — single HTML file

---

## Getting Started

### Run locally

Just open the file in any browser:

```bash
open index.html
```

No server, no install, no build step needed.

### Deploy to GitHub Pages

```bash
git add index.html README.md
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/Phishing-Simulator.git
git push -u origin main
```

Then in your GitHub repo: **Settings → Pages → Source: main branch → Save**

Your app will be live at `https://YOUR_USERNAME.github.io/Phishing-Simulator/` within a minute or two.

---

## Red Flags Covered

1. **Suspicious URLs** — typosquatted domains and misleading subdomains
2. **Mismatched senders** — display name vs actual email address
3. **Urgency and fear tactics** — artificial deadlines and threats
4. **Too-good-to-be-true offers** — prize and reward lures
5. **Unexpected attachments** — malware delivered via .zip or .exe
6. **Poor grammar and formatting** — signs of mass-generated phishing

---

## Tech Stack

| | |
|---|---|
| **Languages** | HTML, CSS, JavaScript |
| **Dependencies** | None |
| **Hosting** | GitHub Pages |
| **Build tools** | None |

---

## Project Structure

```
Phishing-Simulator/
└── index.html      # Entire app — training, simulator, and results
└── README.md
```

---

## Assignment Context

Built as part of a cybersecurity awareness module. The goal was to create a functional, standalone web app that demonstrates both phishing simulation and security awareness training without requiring any backend infrastructure.

---

## License

This project is for educational purposes only. All email scenarios are fictional and created solely to illustrate phishing techniques.
