# CS Visualized ⚡

> Hard concepts. Killer visuals. Finally explained right.

A collection of one-screen, fullscreen animations that make the hardest parts of Computer Science click in under 60 seconds. Built by **Shourya Pratik**.

---

## 🔴 Live Animations

| # | Title | Category | Status |
|---|-------|----------|--------|
| 01 | [What Happens When You Click Run](click_run_explainer.html) | OS / Systems | ✅ Live |
| 02 | [Race Condition](race_condition.html) | Concurrency | ✅ Live |
| 03 | Virtual Memory | OS / Systems | 🔜 Coming Soon |
| 04 | TCP Handshake | Networking | 🔜 Coming Soon |
| 05 | LRU Cache | Data Structures | 🔜 Coming Soon |
| 06 | Load Balancer | System Design | 🔜 Coming Soon |
| 07 | Deadlock | Concurrency | 🔜 Coming Soon |
| 08 | How the Internet Works | Networking | 🔜 Coming Soon |

---

## 📁 Project Structure

```
cs-visualized/
├── index.html               ← Dashboard (homepage)
├── click_run_explainer.html ← Animation 01
├── race_condition.html      ← Animation 02
└── README.md
```

---

## ➕ How to Add a New Animation

**Step 1** — Drop the new `.html` file into the project folder.

**Step 2** — Open `index.html` and find the `ANIMATIONS` array near the top of the `<script>` tag. Add one object:

```js
{
  id: 9,
  title: "Virtual Memory",
  desc: "How your OS tricks every process into thinking it owns all the RAM.",
  file: "virtual-memory.html",
  category: "os",       // os | conc | net | ds | sys
  tagLabel: "OS",
  color: "#ff7c3b",
  complexity: 3,        // 1 = easy, 2 = medium, 3 = hard
  live: true
}
```

**Step 3** — Done. The card renders itself on the dashboard.

---

## 🚀 Deploy (GitHub Pages)

```bash
# 1. Create a repo on GitHub named cs-visualized

# 2. Push all files
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/YOUR_USERNAME/cs-visualized.git
git push -u origin main

# 3. Go to repo Settings → Pages → Source: main branch → Save
# Your site will be live at:
# https://YOUR_USERNAME.github.io/cs-visualized/
```

---

## 🛠️ Tech Stack

- Pure HTML / CSS / Vanilla JavaScript
- Zero frameworks, zero dependencies
- CSS keyframe animations
- Single-file per animation (fully self-contained)

---

## 📌 Category Tags

| Tag | Value | Color |
|-----|-------|-------|
| OS / Systems | `os` | Orange |
| Concurrency | `conc` | Red |
| Networking | `net` | Blue |
| Data Structures | `ds` | Purple |
| System Design | `sys` | Teal |

---

Built with 🔥 by [Shourya Pratik](https://github.com/YOUR_USERNAME)