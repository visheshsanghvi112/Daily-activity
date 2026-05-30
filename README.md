<div align="center">

# 📊 Daily Activity

### *Keeping the GitHub contribution graph green, one commit at a time.*

[![Twice Daily Commit](https://github.com/visheshsanghvi112/Daily-activity/actions/workflows/daily.yml/badge.svg)](https://github.com/visheshsanghvi112/Daily-activity/actions/workflows/daily.yml)
[![GitHub last commit](https://img.shields.io/github/last-commit/visheshsanghvi112/Daily-activity?color=green)](https://github.com/visheshsanghvi112/Daily-activity/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

---

## 📈 Live Stats

<div align="center">

| Metric | Value |
|:------:|:-----:|
| 🔥 Current Streak | **96 day(s)** |
| 🏆 Longest Streak | **96 day(s)** |
| 📝 Total Auto-Commits | **193** |
| 🕐 Last Update | `2026-05-30 08:20 PM IST` |
| 📅 Tracking Since | `2026-02-24` |


</div>

> 💬 *"Code is like humor. When you have to explain it, it's bad. – Cory House"*

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🕐 **Twice Daily Commits** | Automated commits at 9:00 AM & 6:50 PM IST |
| ⏳ **Randomized Timing** | 0–5 min random delay so commits look natural |
| 📜 **Motivational Quotes** | 50+ curated quotes — a new one every commit |
| 🤖 **AI-Powered Thoughts** | Gemini API generates a unique thought each time |
| 🔥 **Streak Tracking** | Tracks current streak, longest streak & total commits |
| 📊 **Live README** | This README auto-updates with fresh stats every run |
| 🎲 **Varied Commit Messages** | 15 different random commit messages |
| 📁 **Multi-File Updates** | Rotates updates across multiple files |

## 🤖 How It Works

```
┌─────────────────────────────────────────────────┐
│              GitHub Actions (Cron)              │
│          9:00 AM IST  &  6:50 PM IST           │
└──────────────────────┬──────────────────────────┘
             │
┌────────────▼────────────┐
│  ⏳ Random Delay 0-5m   │
└────────────┬────────────┘
             │
     ┌─────────────────▼─────────────────┐
     │  📜 Pick Random Quote (50+ pool)  │
     │  🤖 Fetch AI Thought (Gemini)     │
     └─────────────────┬─────────────────┘
             │
  ┌────────────────────▼────────────────────┐
  │  📝 Update activity.log                 │
  │  📊 Update streak.json                  │
  │  📋 Regenerate README.md with stats     │
  │  📁 Update today.json                   │
  └────────────────────┬────────────────────┘
             │
         ┌─────────────▼─────────────┐
         │  🎲 Random Commit Message  │
         │  🚀 Commit & Push          │
         └───────────────────────────┘
```

## 🛠️ Tech Stack

- **GitHub Actions** — CI/CD automation engine
- **Bash Scripting** — lightweight, zero dependencies
- **Google Gemini API** — AI-generated daily thoughts
- **jq** — JSON processing for streak tracking
- **Cron** — UTC-based scheduling

## 📂 Project Structure

```
Daily-activity/
├── .github/workflows/
│   └── daily.yml        # The magic ✨
├── data/
│   ├── quotes.txt       # 50+ curated motivational quotes
│   ├── streak.json      # Streak & stats tracker
│   └── today.json       # Today's rotating snapshot
├── activity.log         # Auto-updated timestamp + quote log
├── LICENSE              # MIT License
└── README.md            # This file (auto-updated with live stats!)
```

## 🚀 Run It Manually

1. Head to the [**Actions**](https://github.com/visheshsanghvi112/Daily-activity/actions) tab
2. Select **Twice Daily Commit**
3. Click **Run workflow** → **Run**

## 📜 License

Licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made with 💚 by <a href="https://visheshsanghvi.me"><b>Vishesh Sanghvi</b></a>
</p>
