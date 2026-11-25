<!-- view-source gang, welcome. yes, it is still 44. -->
<div align="center">

<img src="assets/header.svg" width="100%" alt="44 — DevOps / Platform Engineer"/>

<br/><br/>

<a href="https://t.me/bz444aj1"><img src="https://img.shields.io/badge/Telegram-@bz444aj1-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram @bz444aj1"/></a>

</div>

<br/>

### `$ whoami`

I'm **44**, a DevOps / platform engineer. I run production on **AWS + Kubernetes**: every resource
lives in **Terraform**, every deploy goes through **ArgoCD**, every critical service sits behind an
**SLO**. I like infrastructure that is boring, reproducible and cheap, and I write my own tools when
the existing ones are too slow, too magic, or both.

I came in through systems programming and automation (C, Python, Linux, networks). It still shows:
I read the logs before the docs.

<br/>

### `$ cat ~/prod.md`

<table>
<tr>
<td width="50%" valign="top"><b>Infrastructure as code</b><br/><sub>Multi-account AWS described end to end in Terraform: reusable modules, remote state in S3 with DynamoDB locking, click-ops resources imported instead of left to rot. Ansible for the fleet that is not in Kubernetes yet.</sub></td>
<td width="50%" valign="top"><b>Kubernetes platform</b><br/><sub>EKS clusters for dozens of services. Karpenter and HPA for capacity, honest requests and limits, PodDisruptionBudgets, probes that actually mean something, zero-drama node rotations.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><b>Delivery</b><br/><sub>GitLab CI and Jenkins shared libraries with cached layers and parallel jobs. GitOps with ArgoCD: git is the source of truth, a release is a merge, a rollback is one click.</sub></td>
<td width="50%" valign="top"><b>Observability and on-call</b><br/><sub>Prometheus, Grafana, Loki, Alertmanager. SLOs with burn-rate alerts, blameless postmortems, runbooks and DR drills, so whoever is on call fixes the usual stuff without escalating.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><b>Security</b><br/><sub>IRSA and least-privilege IAM, External Secrets on top of AWS Secrets Manager, Trivy in every pipeline, Kyverno policies at admission. Audit-ready, not audit-scared.</sub></td>
<td width="50%" valign="top"><b>Cost</b><br/><sub>Spot capacity through Karpenter, rightsizing from real utilisation, S3 lifecycle rules, non-prod asleep at night. The AWS bill is a metric with a dashboard and an owner.</sub></td>
</tr>
</table>

<br/>

### `$ ls ~/projects`

<table>
<tr>
<td width="50%" valign="top">
<b>Realtime voice copilot</b> <sub><code>private</code></sub><br/>
<sub>Listens to live audio, transcribes it on the fly (UA / RU / EN with language detection) and streams LLM answers to a desktop overlay. Speculative generation on speech pauses plus prompt caching: the first words show up in <b>~0.7 s</b> (median over 165 answers). Native Hyprland integration over IPC, LAN mirror to a phone over WebSocket, offline self-test suite.</sub><br/><br/>
<code>Python</code> <code>asyncio</code> <code>PyQt6</code> <code>streaming STT</code> <code>Claude API</code> <code>WebSocket</code> <code>Hyprland IPC</code>
</td>
<td width="50%" valign="top">
<b>Trading automation platform</b> <sub><code>private</code></sub><br/>
<sub>Async FastAPI backend on PostgreSQL and Redis with background workers and a state machine for every deal, a Telegram bot for ops control and a Next.js dashboard. Built safety-first: dry-run by default, staged profiles from observation to live, market health gates, preflight checks, loss limits and a read-only kill switch.</sub><br/><br/>
<code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Redis</code> <code>Next.js</code> <code>Docker Compose</code> <code>pytest</code>
</td>
</tr>
</table>

<sub>Also in the drawer: a PowerShell toolkit for Wi-Fi and network auditing, an async proxy checker, Telegram bots for remote PC control and channel automation, low-level C utilities and Arduino builds. Source on request.</sub>

<br/>

### `$ cat stack.yaml`

<table>
<tr>
<td><code>cloud · infra</code></td>
<td><img src="https://skillicons.dev/icons?i=aws,kubernetes,terraform,ansible,docker,nginx" height="40" alt="AWS, Kubernetes, Terraform, Ansible, Docker, Nginx"/></td>
</tr>
<tr>
<td><code>ci/cd · gitops</code></td>
<td><img src="https://skillicons.dev/icons?i=gitlab,jenkins,githubactions,git" height="40" alt="GitLab CI, Jenkins, GitHub Actions, Git"/><br/>
<code>ArgoCD</code> <code>Helm</code> <code>Karpenter</code></td>
</tr>
<tr>
<td><code>observability</code></td>
<td><img src="https://skillicons.dev/icons?i=prometheus,grafana" height="40" alt="Prometheus, Grafana"/><br/>
<code>Loki</code> <code>Alertmanager</code> <code>VictoriaMetrics</code> <code>ELK</code> <code>Zabbix</code></td>
</tr>
<tr>
<td><code>security</code></td>
<td><code>IRSA</code> <code>IAM</code> <code>External Secrets</code> <code>Secrets Manager</code> <code>Trivy</code> <code>Kyverno</code></td>
</tr>
<tr>
<td><code>code · systems</code></td>
<td><img src="https://skillicons.dev/icons?i=linux,bash,python,go,c" height="40" alt="Linux, Bash, Python, Go, C"/><br/>
<code>systemd</code> <code>TCP/IP</code> <code>DNS</code> <code>Wireshark</code></td>
</tr>
<tr>
<td><code>data</code></td>
<td><img src="https://skillicons.dev/icons?i=postgres,redis" height="40" alt="PostgreSQL, Redis"/><br/>
<code>RDS</code> <code>ElastiCache</code> <code>DynamoDB</code></td>
</tr>
</table>

<br/>

### `$ cat principles.txt`

```text
everything as code   →  if it is not in git, it does not exist
measure first        →  dashboards before opinions
automate the runbook →  the best runbook is a script nobody has to run
boring in prod       →  clever stuff lives in side projects
explicit over magic  →  know what runs, where, and why
```

<br/>

<img src="assets/footer.svg" width="100%" alt="44@platform:~$ uptime — up 44 days, load average: 0.44, 0.44, 0.44"/>

<details>
<summary><sub><code>44@platform:~$ sudo make me a sandwich</code></sub></summary>
<sub><code>okay.</code></sub>
</details>
