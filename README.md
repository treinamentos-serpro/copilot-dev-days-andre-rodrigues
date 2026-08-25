🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎯 Soc Ops

### Social Bingo — break the ice, make connections, win the room.

*Find people who match the prompts. Get 5 in a row. Repeat.*

<br/>

[![Play the Game](https://img.shields.io/badge/▶%20Play%20the%20Game-blue?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![View Lab Guide](https://img.shields.io/badge/📚%20Lab%20Guide-gray?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)

</div>

---

## ✨ What is Soc Ops?

Soc Ops turns the awkward silence of a conference room or team offsite into something genuinely fun. Each player gets a randomized 5×5 bingo board packed with icebreaker prompts — *"Has given a talk at a meetup"*, *"Speaks more than two languages"*, *"Has deployed on a Friday"* — and the challenge is to find real people in the room who match them.

It's a **Blazor WebAssembly** app that runs entirely in the browser, no server required.

---

## 🚀 Quick Start

> **Requires:** [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher

```bash
# Clone your copy, then:
cd SocOps
dotnet run
```

Open the URL shown in the terminal and start playing instantly.

### ☁️ Zero-install: Open in GitHub Codespaces

1. Click **Code → Codespaces → Create codespace on main**
2. Wait for the devcontainer to finish setting up (~1 min)
3. Run `dotnet run --project SocOps/SocOps.csproj` in the terminal
4. Click **Open in Browser** when prompted

---

## 🛠️ Build

```bash
cd SocOps
dotnet build
```

Every push to `main` deploys automatically to **GitHub Pages**.

---

## 🧪 Lab Guide — Learn While You Build

This repo is also a **hands-on workshop** for GitHub Copilot agent development. Work through the steps below to build, extend, and improve Soc Ops using AI-powered tooling:

| Step | Topic |
|:----:|-------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | 🗺️ Overview & Checklist |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | ⚙️ Setup & Context Engineering |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | 🎨 Design-First Frontend |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | 🤖 Custom Quiz Master Agent |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | 🔗 Multi-Agent Development |

> 📁 Prefer offline? All guides are in the [`workshop/`](workshop/) folder.

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Blazor WebAssembly (.NET 10) |
| Language | C# |
| Hosting | GitHub Pages |
| Dev environment | GitHub Codespaces + devcontainer |

---

## 🤝 Contributing

We'd love your contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

---

<div align="center">

Made with ☕ and a healthy fear of awkward silences.

</div>
