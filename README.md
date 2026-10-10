<div align="center">

# 🔑 Password Generator

**Generate strong, random passwords in one click — choose the length and character types, see a live strength indicator, and copy to clipboard.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Try_it_on_Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://password-generator-shariq2003s-projects.vercel.app/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub last commit](https://img.shields.io/github/last-commit/Shariq2003/Password_Generator-?style=flat-square)

[Features](#-features) · [How it works](#-how-it-works) · [Strength rules](#-strength-indicator) · [Getting Started](#-getting-started)

</div>

---

## ✨ Features

- 🎚️ **Length slider** — 1 to 20 characters
- ☑️ **Character options** — uppercase, lowercase, numbers, symbols
- ✅ **Guaranteed variety** — at least one character from every selected type
- 🔀 **Fisher–Yates shuffle** so the guaranteed characters aren't predictable
- 🚦 **Live strength indicator** — red, yellow or green glow
- 📋 **One-click copy** with a "copied" tooltip

## 🔄 How it works

```mermaid
flowchart LR
    A["Selected types<br/>e.g. A-Z, a-z, 0-9, !@#"] --> B["1 char from each<br/>selected type"]
    B --> C["Fill remaining length<br/>with random picks"]
    C --> D["Fisher–Yates shuffle"]
    D --> E["🔑 Password"]
    E --> F["Strength check 🚦"]
```

## 🚦 Strength indicator

| Colour | Rule |
|---|---|
| 🟢 **Strong** | Upper **and** lower case, plus a number or symbol, and length ≥ 8 |
| 🟡 **Medium** | Any letters, plus a number or symbol, and length ≥ 6 |
| 🔴 **Weak** | Anything else |

## 🚀 Getting Started

No dependencies, no build step:

```bash
git clone https://github.com/Shariq2003/Password_Generator-.git
cd Password_Generator-
# open index.html in your browser
```

> ℹ️ The clipboard API needs HTTPS or `localhost` — use the live demo or `npx serve .` if copy doesn't work from a local file.

<details>
<summary><b>📁 Project structure</b></summary>

```text
Password_Generator-/
├── index.html
├── index.css
└── index.js     # generation, shuffle, strength, clipboard
```

</details>

---

<div align="center">

Built by **[Shariq](https://github.com/Shariq2003)** · [LinkedIn](https://www.linkedin.com/in/shariq-sd)

⭐ If you like this project, consider giving it a star!

</div>
