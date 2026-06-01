# 📢 Email-Marketing-Suite — Professional email marketing desktop application with GUI — campaign management, subscriber lists, analytics, and multi-SMTP support

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/zougar99/Email-Marketing-Suite/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/zougar99/Email-Marketing-Suite?style=social)](https://github.com/zougar99/Email-Marketing-Suite)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue)](https://github.com/zougar99/Email-Marketing-Suite)

> Professional email marketing desktop application with GUI — campaign management, subscriber lists, analytics, and multi-SMTP support.

---

## 📖 Table of Contents
- [Features](#-features)
- [How It Works](#-how-it-works)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Usage Guide](#-usage-guide)
- [Screenshots](#-screenshots)
- [Roadmap](#-roadmap)
- [FAQ](#-faq)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features
- ✔ **Campaign Builder** — WYSIWYG email editor with templates
- ✔ **Subscriber Management** — Import, segment, and manage mailing lists
- ✔ **Multi-SMTP** — Rotate between multiple SMTP servers for deliverability
- ✔ **Analytics** — Open rates, click rates, bounce tracking
- ✔ **Scheduling** — Schedule campaigns for specific dates/times
- ✔ **Template Library** — Pre-built responsive email templates
- ✔ **Unsubscribe** — Built-in unsubscribe link management

---

## 🔮 How It Works

```
  Input ──► Processing Pipeline ──► Output
  ┌────────┐   ┌────────┐   ┌────────┐
  │ Data   │──►│ Engine │──►│ Result │
  │ Source │   │ Logic  │   │        │
  └────────┘   └────────┘   └────────┘
```

1. **Input** — Load data from file, API, or user input
2. **Process** — Core engine applies logic/analysis/transformation
3. **Output** — Results displayed in UI, saved to file, or sent via API

---

## 💻 Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python 3.10+ |
| UI | CustomTkinter |
| Email | smtplib + Jinja2 templates |
| Database | SQLite |
| Reports | Matplotlib charts |

---

## 🚀 Installation

```bash
git clone https://github.com/zougar99/Email-Marketing-Suite.git
cd Email-Marketing-Suite
pip install -r requirements.txt
```

---

## 📄 Configuration

Create a `config.yaml` or `.env` file in the project root:

```yaml
# Application settings
debug: false
port: 8080
theme: dark
language: en
```

---

## 🧰 Usage Guide

1. Launch: `python main.py`
2. Add SMTP servers in Settings
3. Import or create subscriber lists
4. Design email using the template editor
5. Schedule and send your campaign
6. Monitor analytics in the Reports tab

---

## 🖼 Screenshots

> *(Screenshots coming soon. PRs welcome!)*

---

## 🔄 Roadmap

- 🟢 Web dashboard
- 🟡 Mobile companion app
- ⚫ API access
- ⚫ Plugin system
- ⚫ Multi-language support

---

## ❓ FAQ

### Can I send to unlimited subscribers?
Limited only by your SMTP server limits. The app rotates SMTPs to maximize throughput.

### Does it track opens?
Yes — via embedded tracking pixel.

---

## 🚧 Troubleshooting

| Problem | Solution |
|---------|----------|
| **App won't start** | Check Python version (3.10+); run `pip install -r requirements.txt` |
| **No output** | Check logs in `logs/` folder; enable debug mode in config |
| **Performance issues** | Close other applications; reduce batch size in config |
| **Dependency errors** | Create fresh venv: `python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt` |

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📐 License
Distributed under the **MIT License**. See [`LICENSE`](https://github.com/zougar99/Email-Marketing-Suite/blob/main/LICENSE) for more information.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/zougar99">zougar99</a>
</p>
