# Hey, I'm Andrea 👋

Software and platform engineer focused on site reliability, DevOps, and infrastructure. I recently graduated from the University of Miami with a B.S. in Computer Science and a minor in Mathematics.

I build small, production-like systems: containerized services on AWS, automated with CI/CD and infrastructure as code, monitored with real alerting and runbooks. My homelab is where I pressure-test all of it before it matters.

I'm currently looking for **DevOps / SRE / Platform / Infrastructure** roles where I can help teams ship faster, automate reliably, and keep customer-facing systems stable.

[![Portfolio](https://img.shields.io/badge/andreaventi.com-000?style=for-the-badge&logoColor=white)](https://andreaventi.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrea-venti)

---

## What I've Been Building

### [Homelab](https://github.com/av1155/homelab) · Production-Grade SRE/DevOps Platform

3-node Proxmox HA cluster and 6-node Kubernetes HA cluster, fully managed through GitOps. Argo CD and self-hosted GitHub Actions for CI/CD. Terraform, Ansible, and Packer for IaC. Zero-trust networking with HashiCorp Vault, Cloudflare Zero Trust, WireGuard, and NGINX ingress. Observability via Prometheus, Grafana, and Alertmanager. UPS-backed compute with automated DR: ZFS replication, scheduled zstd snapshot backups to NAS, and off-site backups to Cloudflare R2.

**RTO ≤ 3 min · RPO ~15 min · 29 stacks / 95 containers**

### [Houndarr](https://github.com/av1155/houndarr) · Automated Search Companion for *arr Apps

Open-source, self-hosted tool that works alongside Radarr, Sonarr, Lidarr, Readarr, and friends to search for missing library items in polite, rate-limited batches instead of hammering APIs all at once. Features configurable batch sizes, per-item cooldowns, hourly API caps, download-queue backpressure gating, and a dark-themed web dashboard built with FastAPI, HTMX, and Tailwind CSS. API keys encrypted at rest (Fernet/AES-128-CBC), bcrypt auth, CSRF protection. Distributed as a Docker image and Helm chart. Publicly released and reached **90+ stars** and **1.3k+ Docker pulls** in two days.

### [FlaskKeyring](https://github.com/av1155/FlaskKeyring) · Zero-Knowledge Password Manager

Full-stack password manager with client-side AES-GCM encryption, secure REST APIs, and email verification. Python, Flask, PostgreSQL.

### [BridgeChat](https://github.com/av1155/BridgeChat) · Real-Time Translated Chat
 
Semester-long software engineering class project where I pitched the idea and solo-developed the prototype: a real-time chat app with on-the-fly translation across languages. The course focused on SDLC practices, team workflows, and development models rather than coding itself, but I built a working demo for our final presentation. Voted best project of the semester by the class (won both the mid-semester and final presentation votes).

### [IndexNet Engine](https://github.com/av1155/IndexNet-Engine) · Search Engine Simulation

Java-based search engine using PageRank, web crawling, and B-Tree indexing.

### [Portfolio](https://www.andreaventi.com) · Personal Site

Responsive portfolio built with Next.js, TypeScript, and Tailwind CSS. Self-hosted with [Dokploy](https://github.com/Dokploy/dokploy).

### [.dotfiles](https://github.com/av1155/.dotfiles) · Dev Environment Automation

Cross-platform, architecture-aware shell scripts for bootstrapping dev environments on macOS, Linux (Arch/Debian), and WSL.

### [Neovim Config](https://github.com/av1155/nvim)

Lean, fast Neovim setup built with Lua. Optimized for actual productivity, not just looking cool in screenshots (though it does that too).

---

## Tech I Use

**Languages:** Python, Go, Java, C/C++, TypeScript, JavaScript, Lua, Shell, YAML

**Infrastructure:** Docker, Kubernetes, Helm, Terraform, Ansible, Packer, Proxmox, GitHub Actions, Argo CD

**Cloud & Networking:** AWS, Cloudflare (Zero Trust, R2), WireGuard, NGINX

**Observability:** Prometheus, Grafana, Alertmanager, Uptime Kuma, CloudWatch

**Web:** Next.js, React, FastAPI, Flask, HTMX, Tailwind CSS, Node.js

**Databases:** PostgreSQL, MariaDB, SQLite, Supabase

**Tools:** Neovim, Git, Tmux, Kitty, HashiCorp Vault

---

<br>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=av1155&theme=dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=av1155&theme=dark&hide_border=true" alt="GitHub Streak" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=av1155&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages" />
</p>
