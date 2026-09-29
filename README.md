### Hey, I'm Arghya

I work on observability at **ION Trading**: Java and Spring services that collect metrics and logs across the platform, plus the Prometheus, Grafana and OpenSearch setup engineers use during an incident.

Outside work I mostly build desktop tools for Windows that fix my own annoyances. They're usually Go with a Svelte UI, and they go all the way to a proper installer and a release page.

<p>
<a href="https://arghya2801.vercel.app"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/arghya333/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MyAyLjA2MyAwIDEgMSAwLTQuMTI2IDIuMDYzIDIuMDYzIDAgMCAxIDAgNC4xMjZ6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMHoiLz48L3N2Zz4=&logoColor=white" alt="LinkedIn"></a>
<a href="https://drive.google.com/file/d/1DmDorIE9CL8iTCmt8ilQg0Dyz7jVpCMf/view"><img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"></a>
<a href="mailto:arghya2801@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### What I've been building

<table>
<tr>
<td width="50%"><a href="https://github.com/arghya2801/agent-terminal-control"><img src="cards/atc.svg" alt="Agent Terminal Control: a Windows terminal with a sidebar of Claude Code and Codex sessions"></a></td>
<td width="50%"><a href="https://github.com/arghya2801/directory-size-exporter"><img src="cards/directory-size-exporter.svg" alt="directory-size-exporter: Prometheus exporter for per-directory disk usage"></a></td>
</tr>
<tr>
<td><a href="https://github.com/arghya2801/email_newsletter_reader"><img src="cards/newsletters.svg" alt="Newsletters: desktop reader for Gmail newsletter labels"></a></td>
<td><a href="https://github.com/arghya2801/taiga"><img src="cards/taiga.svg" alt="Taiga fork: MyAnimeList anime and manga client for Windows"></a></td>
</tr>
<tr>
<td><a href="https://github.com/arghya2801/portfolio"><img src="cards/portfolio.svg" alt="Portfolio site styled as a Grafana dashboard"></a></td>
<td><a href="https://github.com/arghya2801/visual-product-matcher-backend"><img src="cards/visual-product-matcher.svg" alt="Visual Product Matcher: image similarity search with embeddings"></a></td>
</tr>
</table>

- **[Agent Terminal Control](https://github.com/arghya2801/agent-terminal-control):** I got tired of `claude --resume` and trying to remember which folder a session lived in. ATC reads `~/.claude/projects` and Codex's history and puts every session under its project, one click to resume. It runs a real ConPTY terminal with tabs, split panes, tasks linked to branches, and a usage page that shows what the tokens would have cost at API prices. Started on Tauri/Rust, now on Go/Wails.
- **[directory-size-exporter](https://github.com/arghya2801/directory-size-exporter):** node_exporter tells you a volume is 90% full. This tells you which directory filled it. Scans run in the background with timeouts and concurrency caps, and a failed scan never publishes partial numbers, so it can't fake a capacity drop and set off alerts.
- **[Newsletters](https://github.com/arghya2801/email_newsletter_reader):** a reader for the Gmail labels my filters already sort newsletters into. It's not a mail client. The only change it makes to the mailbox is marking an issue read.
- **[Taiga fork](https://github.com/arghya2801/taiga):** my fork of erengy's Taiga rewrite, turned into a fast MyAnimeList client with manga support, sortable columns, cached posters and a flat theme.

<details>
<summary>Older stuff</summary>

- [code_review_ai_agent](https://github.com/arghya2801/code_review_ai_agent_backend) ([frontend](https://github.com/arghya2801/code_review_ai_agent_frontend)): an AI code reviewer attached to a LeetCode-style coding platform
- [Intelligent Order Parameter Prefill](https://github.com/arghya2801/Intelligent-Order-Parameter-Prefill-Frontend): hackathon project
- [e-commerce-spring-backend](https://github.com/arghya2801/e-commerce-spring-backend) and [e-commerce](https://github.com/arghya2801/e-commerce): the same store built twice, once in Spring Boot and once in Express + MongoDB
- [accountability-tracker](https://github.com/arghya2801/accountability-tracker): public goals, so your friends can call you out
- [convert2pdf](https://github.com/arghya2801/convert2pdf): PowerShell CLI to batch-convert Word, Excel and PowerPoint files to PDF
- [aws_disaster_recovery](https://github.com/arghya2801/aws_disaster_recovery): kill EC2 in one region, bring it back in another, with Lambda handling the AMIs

</details>

---

### Stack

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=java,spring,prometheus,grafana,linux,docker,kubernetes,aws&perline=8" alt="Java, Spring, Prometheus, Grafana, Linux, Docker, Kubernetes, AWS"></a><br>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=go,ts,svelte,nextjs,react,tailwind,cpp,python&perline=8" alt="Go, TypeScript, Svelte, Next.js, React, Tailwind, C++, Python"></a>

<sub>Also: OpenSearch · Fluent Bit · Convex · Wails. AWS Solutions Architect Associate, OCI DevOps Professional.</sub>
