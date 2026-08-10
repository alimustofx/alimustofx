<div align="center">

# Ali Mustofa

**Infrastructure Engineer · Laravel Developer · School IT Operator**

East Java, Indonesia

[![GitHub](https://img.shields.io/badge/-alimustofx-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alimustofx)
[![Email](https://img.shields.io/badge/-alimustofx%40gmail.com-305cac?style=flat-square&logo=gmail&logoColor=white)](mailto:alimustofx@gmail.com)
[![WhatsApp](https://img.shields.io/badge/-Chat-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/6282264928953)
[![Instagram](https://img.shields.io/badge/-alimustofx-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/alimustofx)

</div>

<br>

## About

I keep school technology running — student data systems, internal portals, networking, and the servers underneath all of it. That means I end up owning the whole stack: I write the Laravel applications teachers use every morning, and I run the Proxmox cluster and Linux boxes they sit on.

Self-taught, currently studying Communication Science alongside the engineering work — because the systems I build only matter if the people using them actually understand them.

<br>

## What I'm working on

| Project | Stack | Status |
|---|---|---|
| Student Data Verification System | Laravel, MySQL, Cloudflare | Live |
| School Information System | Laravel, PHP 8, Ubuntu Server | Active |
| Proxmox infrastructure upgrade | Proxmox VE, Docker, LXC | Ongoing |
| Network security hardening | Cloudflare, pfSense, Linux | Ongoing |

<br>

## Stack

**Backend** — Laravel · PHP 8 · MySQL · Blade

**Infrastructure** — Proxmox VE · Ubuntu Server · Docker · Nginx · Linux

**Networking / Security** — Cloudflare · pfSense · Zero Trust

**Tools** — Git · Composer · VS Code

<br>

## System layout

A rough sketch of how the school network is put together — Cloudflare in front, Proxmox underneath, everything else riding on top of it.

```
Internet
   │
   ▼
Cloudflare  (DNS · DDoS protection · Zero Trust tunnel)
   │
   ▼
Proxmox host
   ├── VM  — Ubuntu Server
   │         ├── Student Verification App
   │         ├── School Information System
   │         └── Internal tools
   ├── VM  — Database
   │         ├── MySQL (Galera)
   │         └── Redis
   └── LXC — Monitoring
             ├── Grafana
             └── Uptime Kuma
   │
   ▼
Teachers · Staff · Students · Admin
```

<br>

## Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=alimustofx&show_icons=true&theme=default&hide_border=true&title_color=305cac&icon_color=4f8ef7&text_color=434751&count_private=true&include_all_commits=true&rank_icon=github&border_radius=8&bg_color=00000000"/>
<img width="41%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alimustofx&layout=compact&theme=default&hide_border=true&title_color=305cac&text_color=434751&langs_count=8&border_radius=8&bg_color=00000000"/>

</div>

<br>

---

<sub>Based in East Java · usually reachable somewhere between a terminal and a coffee cup</sub>
