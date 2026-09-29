### Hey, I'm Arghya

I work on observability at **ION Trading**: Java and Spring services that collect metrics and logs across the platform, plus the Prometheus, Grafana and OpenSearch setup engineers use during an incident.

Outside work I mostly build desktop tools for Windows that fix my own annoyances. They're usually Go with a Svelte UI, and they go all the way to a proper installer and a release page.

[Portfolio](https://arghya2801.vercel.app) · [LinkedIn](https://www.linkedin.com/in/arghya333/) · [Resume](https://drive.google.com/file/d/1DmDorIE9CL8iTCmt8ilQg0Dyz7jVpCMf/view) · [arghya2801@gmail.com](mailto:arghya2801@gmail.com)

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

**Day job:** Java · Spring Boot · Prometheus · Grafana · OpenSearch · Fluent Bit · Linux<br>
**Side projects:** Go · TypeScript · Svelte · Next.js · Convex · C++<br>
**Cloud:** AWS (Solutions Architect Associate) · OCI (DevOps Professional) · Docker · Kubernetes

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arghya2801&layout=compact&hide_border=true&bg_color=00000000&title_color=ff9830&text_color=9198a1&langs_count=8&hide=html,css" height="150" alt="Top languages">
