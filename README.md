<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=98C379&height=100&section=header" width="100%"/>

# Hey 👋 I'm Yash Potdar

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=98C379&center=true&vCenter=true&width=600&lines=homelab+tinkerer+%E2%80%A2+infra+%26+security;documents+everything+(probably+too+much);breaks+things+intentionally+%F0%9F%94%A5;builds+tools+%2C+not+unicorns+%F0%9F%A6%84)

<img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="400">

</div>

---

I build small, useful infrastructure tools and homelab prototypes, intentionally break them to learn how they fail, and document the entire process so you don't have to.

If it involves Linux, SSH, Raspberry Pi, or saying "let's see what happens if I..." — I'm probably interested.

---

## 🛠️ What I Actually Do

- **Build security tools** that I'd want to use (like [sentinel-ssh](https://github.com/yashpotdar-py/sentinel-ssh) — a lightweight SSH intrusion detector with personality)
- **Run homelabs** on Raspberry Pi hardware, Debian systems, and whatever else survives the power bill
- **Document everything** — postmortems, setup guides, failure logs, and lessons learned
- **Break things intentionally** to understand how they work (and write about it)
- **Write Python** when shell scripts get embarrassing

I prefer single-player technical exploration over Zoom meetings. My projects are small, focused, and designed to teach me (and you) something specific.

---

## 🧪 Current Experiments

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [sentinel-ssh](https://github.com/yashpotdar-py/sentinel-ssh)

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)
![Version](https://img.shields.io/badge/version-1.1.0-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

Lightweight SSH intrusion detector + auto-responder. Built because I wanted transparency over "magic" in security tooling.

**Features:**
- Real-time `journald` log parsing
- Brute-force detection with sliding time windows
- Temporary UFW blocks (so you don't accidentally ruin your life)
- Prometheus metrics for observability nerds

**Tech:** Python, systemd, journald, UFW, Prometheus  
**Status:** Production-ready (on my Pi, anyway)

</td>
<td width="50%" valign="top">

### 🏠 Homelab Infrastructure

![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Status](https://img.shields.io/badge/status-tinkering-orange?style=flat-square)

An ongoing experiment in running useful services on hardware that costs less than a sandwich.

**Current Setup:**
- Pi-hole for DNS filtering
- SSH hardening and monitoring
- Network topology that probably violates some RFC
- Various services that may or may not be up

**Documentation:** In progress. Postmortems upcoming.

</td>
</tr>
</table>

---

## 💡 Philosophy

> **"Build minimal solutions, intentionally break them, iterate until the lessons are clear."**

I write code to learn, not to scale to a billion users. My projects are:

- **Transparent** — you should know *why* a decision was made
- **Documented** — future-me deserves context
- **Practical** — solves a real (if small) problem
- **Auditable** — no black boxes, no "just trust me"

If a tool doesn't make sense at 3 AM when something's broken, I don't want to use it.

---

## 🧰 Tools & Tech I Actually Use

<div align="center">

### Systems & Infrastructure
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-3E94D3?style=for-the-badge)
![SSH](https://img.shields.io/badge/SSH-231F20?style=for-the-badge)

### Languages & Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### Networking & Security
![UFW](https://img.shields.io/badge/UFW-DD4814?style=for-the-badge)
![Pi-hole](https://img.shields.io/badge/Pi--hole-96060C?style=for-the-badge&logo=pi-hole&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

</div>

> *I don't do "full-stack" anymore. I do "full-depth" — one layer at a time, documented thoroughly.*

---

## 📝 What I Write About

- **Postmortems** — what broke, why it broke, and how I fixed it (or gave up)
- **Setup guides** — reproducible steps so you don't waste a weekend like I did
- **Threat models** — thinking through failure modes before they happen
- **System design docs** — because reading your own code 6 months later is humbling
- **Lessons learned** — usually titled "don't do what I did"

Check the repos for READMEs longer than the code. That's intentional.

---

## 🎯 Current Focus

- Expanding homelab monitoring and alerting
- Building more security tooling with Prometheus metrics
- Writing detailed setup guides for Raspberry Pi projects
- Learning Rust (because Python is too slow and I hate myself)

---

## 📬 Get In Touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-Coming_Soon-fabd2f?style=for-the-badge)](https://github.com/yashpotdar-py)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yashpotdar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yashpotdar.py@gmail.com)

</div>

> *I respond fastest to technical questions, project ideas, or suggestions for obscure sysadmin tooling.*

---

## 🚨 Fair Warning

My projects are:
- Built for learning, not production (unless noted otherwise)
- Over-documented on purpose
- Sometimes intentionally broken to prove a point
- Designed to run on a $35 computer

If you're looking for blazing-fast, enterprise-grade, venture-backed SaaS — you're in the wrong place.  
If you want to learn by building small, practical tools — stick around.

---

## 📊 Stats (if you care)

<div align="center">

![Yash's GitHub Stats](https://github-readme-stats.vercel.app/api?username=yashpotdar-py&show_icons=true&theme=gruvbox&hide_border=true&bg_color=1d2021&title_color=fabd2f&icon_color=fb4934&text_color=ebdbb2)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yashpotdar-py&layout=compact&theme=gruvbox&hide_border=true&bg_color=1d2021&title_color=fabd2f&text_color=ebdbb2)

![Visitor Count](https://komarev.com/ghpvc/?username=yashpotdar-py&color=fabd2f&style=flat-square&label=Visitors+%28who+got+lost%29)

</div>

---

<div align="center">

### *Built with ☕, paranoia, and too much free time.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=98C379&height=100&section=footer" width="100%"/>

</div>
