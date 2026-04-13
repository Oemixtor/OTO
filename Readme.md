# 🔍 OTO – Website Watcher (Chrome-Based)

OTO is a lightweight website monitoring tool that uses a real Chrome browser session to watch for specific text appearing on a page.

It behaves exactly like a human user would — no API access, no scraping shortcuts — just Chrome running normally and checking what’s visible on screen.

---

## 🚀 What It Does

* Opens Chrome like a real user
* Navigates to a target website
* Continuously watches for specific text on screen
* Triggers notifications instantly when the text appears

---

## 🧠 How It Works

OTO uses a **real browser session** instead of backend requests.

This means:

* It sees exactly what you see
* Works on dynamic sites (React, Next.js, etc.)
* Handles login/session-based pages
* Avoids most bot detection systems

---

## 🔔 Notification Methods

When the target text is detected, OTO can notify you through:

* 📞 Google Voice (call/alert)
* 📧 Email
* 💬 Discord (webhook/message)

---

## ⚙️ Core Concept

Instead of polling APIs or scraping HTML, OTO:

1. Launches Chrome
2. Loads the page
3. Observes the rendered content
4. Scans for target text
5. Fires alerts when matched

---

## 🧩 Use Cases

* Monitoring restocks
* Watching for access opportunities
* Tracking status changes on web apps
* Detecting time-sensitive updates

---

## ⚡ Why OTO

* No reverse engineering required
* Works on almost any site
* Extremely simple logic
* Reliable for real-world scenarios

---

## 🛠️ Philosophy

> If you can see it, OTO can detect it.

---

## 📌 Notes

* Designed for single-target monitoring (focused + efficient)
* Runs locally using your environment
* Chrome must be installed

---

## 🔒 Disclaimer

Use responsibly and in accordance with the website’s terms of service.

---

## 🧪 Future Ideas

* Multi-target support
* Smart delay/randomization
* Screenshot-based detection fallback
* UI dashboard
* Mobile push notifications

---

## 👤 Author

Built for practical, real-world monitoring where speed matters.
