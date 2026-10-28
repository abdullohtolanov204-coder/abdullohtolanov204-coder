from pathlib import Path

readme = r'''<div align="center">

<!-- DARK PREMIUM HEADER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,45:062b1b,100:00ff88&height=200&section=header&text=ABDULLOH%20TOLANOV&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Python%20Developer%20%7C%20Web%20%26%20Bot%20Builder&descAlignY=59&descSize=16" />

<a href="https://github.com/YOUR_USERNAME">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=00FF88&center=true&vCenter=true&width=700&lines=Hello%2C+I'm+Abdulloh+%F0%9F%91%8B;Python+%7C+Django+Developer;Building+Websites+%26+Telegram+Bots;Always+Learning+Something+New" alt="Typing SVG" />
</a>

<p>
  <img src="https://img.shields.io/badge/FOCUS-Web%20Development-00ff88?style=for-the-badge&labelColor=090909" alt="Focus: Web Development" />
  <img src="https://img.shields.io/badge/BASED%20IN-Uzbekistan-00ff88?style=for-the-badge&labelColor=090909" alt="Based in Uzbekistan" />
</p>

</div>

---

## `whoami` — About Me

```python
class Developer:
    name = "Abdulloh Tolanov"
    role = "Python Developer"
    location = "Uzbekistan"
    interests = ["Web Development", "Telegram Bots", "Automation"]
    currently_learning = ["Python", "Django", "JavaScript"]

    def goal(self):
        return "Build useful products and keep improving every day."
```

- 🔭 I build websites and Telegram bots.
- 🌱 I’m learning Python, Django, and JavaScript.
- 🧩 I enjoy turning ideas into useful digital projects.
- 🎯 My goal is to become a skilled full-stack developer.
- 📫 Contact: add your preferred contact link here.

---

## `tech_stack` — Technologies & Tools

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=python,html,css,js&theme=dark" alt="Python, HTML, CSS, JavaScript" />

### Frameworks & Tools
<img src="https://skillicons.dev/icons?i=django,git,github,vscode&theme=dark" alt="Django, Git, GitHub, VS Code" />

</div>

---

## `github_stats` — GitHub Analytics

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&hide_border=true&bg_color=080d0a&title_color=00ff88&icon_color=00ff88&text_color=e6fff2&ring_color=00ff88" alt="GitHub statistics" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&hide_border=true&bg_color=080d0a&title_color=00ff88&text_color=e6fff2" alt="Most used languages" />
</div>

<div align="center">
  <img width="95%" src="https://streak-stats.demolab.com?user=YOUR_USERNAME&hide_border=true&background=080d0a&ring=00ff88&fire=00ff88&currStreakLabel=00ff88&sideLabels=e6fff2&currStreakNum=e6fff2&sideNums=e6fff2&dates=8aa899" alt="GitHub contribution streak" />
</div>

---

## `activity` — Contribution Graph

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=080d0a&color=e6fff2&line=00ff88&point=ffffff&area=true&hide_border=true" alt="GitHub contribution activity graph" />
</div>

---

## `featured_projects` — Featured Projects

> Replace these example cards with your real repositories when you’re ready.

<div align="center">

<a href="https://github.com/YOUR_USERNAME">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=YOUR_USERNAME&repo=YOUR_PROJECT_1&hide_border=true&bg_color=080d0a&title_color=00ff88&text_color=e6fff2&icon_color=00ff88" alt="Featured project one" />
</a>
<a href="https://github.com/YOUR_USERNAME">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=YOUR_USERNAME&repo=YOUR_PROJECT_2&hide_border=true&bg_color=080d0a&title_color=00ff88&text_color=e6fff2&icon_color=00ff88" alt="Featured project two" />
</a>

</div>

**Project ideas to showcase**
- 🤖 **Telegram Bot** — a useful bot built with Python.
- 🌐 **Django Website** — a responsive website with a backend.
- ⚙️ **Automation Tool** — a small tool that saves time.

---

## `connect` — Find Me Online

<div align="center">

<a href="https://github.com/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/GitHub-Follow-00ff88?style=for-the-badge&logo=github&logoColor=00ff88&labelColor=090909" alt="GitHub" />
</a>
<a href="https://t.me/botyaratish_admin">
  <img src="https://img.shields.io/badge/Telegram-Contact-00ff88?style=for-the-badge&logo=telegram&logoColor=00ff88&labelColor=090909" alt="Telegram" />
</a>
<a href="https://instagram.com/tulanovv_a">
  <img src="https://img.shields.io/badge/Instagram-Connect-00ff88?style=for-the-badge&logo=instagram&logoColor=00ff88&labelColor=090909" alt="Instagram" />
</a>

</div>

---

<div align="center">

### `while (learning) { keep_building(); }`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff88,55:062b1b,100:050505&height=100&section=footer" alt="Green footer" />

<sub>Designed with 💚 by Abdulloh Tolanov</sub>

</div>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created: {path} ({path.stat().st_size} bytes)")
