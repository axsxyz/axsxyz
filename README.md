### axs

Software engineer. I take systems from a working prototype to something that runs unattended, and I measure them before
I make claims about them.

**Recent work**

- **[mistral-k8s](https://github.com/axsxyz/mistral-k8s):** Ministral 3 served on Kubernetes.
  - vLLM on GPU and llama.cpp on CPU, deployed with Helm and Terraform, observed with Prometheus and Grafana.
  - Load-tested to 1,024 concurrent requests and a 10,000-request burst.
  - `--max-num-seqs` tuned from the KV-cache size: 0 preemptions, p95 time per token halved.
- **[section23-jobs](https://github.com/axsxyz/section23-jobs):** async ingestion of French job offers from several
  sources, with deduplication, LLM scoring against a target profile, alerts and a multi-user web board.
- **[windows-usb-provisioning](https://github.com/axsxyz/windows-usb-provisioning):** a USB kit that provisions Windows
  11 Pro workstations end to end: apps, Microsoft 365, Entra ID / Intune join, user migration.
- **[polymarket-lp-bot](https://github.com/axsxyz/polymarket-lp-bot) and [ak-arc](https://github.com/axsxyz/ak-arc):**
  trading and on-chain systems where every bug has a price: layered guards, paper modes, append-only audit trails.

**How I work**

- Agent-first: coding agents under explicit rules, invariants and tests. I care about how to evaluate what they produce.
- Claims in my READMEs point to a measurement, a test or a commit.
- My main projects keep a "What broke and how I fixed it" section and their open items in plain sight.

**Stack:** Python · TypeScript · SQL · PowerShell · Docker · Kubernetes · Helm · Terraform · PostgreSQL ·
Prometheus/Grafana · vLLM

**Contact:** [axs@moonbow.gg](mailto:axs@moonbow.gg)
