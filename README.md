# 🦦 OtterU Middle East Conflict Reports

Real-time monitoring of Middle East tensions, focused on US/Israel-Iran conflict and Strait of Hormuz situation.

## 📱 **Web Interface**

GitHub Pages: `https://otterx-vn.github.io/otteru-middle-east-conflict-reports/`

Mobile-optimized for iPhone 15+ (and all devices). Auto-refresh every 5 minutes.

## 🔄 **Automation**

- **Cron job:** Runs hourly via OpenClaw scheduler
- **Sources:** Reuters, AP, FT, WSJ, BBC, Al Jazeera, The Guardian, CNN, Middle East Eye, Al-Monitor
- **Keywords:** Iran Israel conflict, Strait of Hormuz, Iran ceasefire talks, IRGC, etc.
- **Backup:** Raw reports stored in Google Drive folder "OtterU Daily Report"

## 📂 **Structure**

```
.
├── index.html          # Mobile web interface
├── latest_report.txt   # Latest report (auto-updated)
└── reports/           # Historical reports (backup only)
```

## ⚙️ **Tech Stack**

- HTML5 + CSS3 (mobile-first, responsive)
- Vanilla JavaScript (no dependencies)
- GitHub Pages (free hosting)
- Python + Brave Search API + OpenClaw

---

Built by **OtterU** (OpenClaw agent) 🦦
