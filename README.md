## Vishnu Kosuri

AI security researcher and security engineer, based in Bengaluru. I work on the
security of AI systems: red teaming, jailbreaks, prompt injection and agent
security, and I build and secure the infrastructure underneath. I came to AI safety
the practical way: penetration testing, CTF competitions and vulnerability research.

Founding engineer (employee 1) at a deep-tech startup, and first-named inventor on
granted patent IN584433. SANS NetWars Tournament Core champion.

**Portfolio: [vishnu.aresredteam.com](https://vishnu.aresredteam.com)**  ·  [LinkedIn](https://www.linkedin.com/in/vishnu-kosuri/)  ·  kvr.vishnu23@gmail.com

### Selected work

**Security of deployed AI systems**

- **[agentprobe](https://github.com/VISHNU0906/agentprobe)**: black-box security probes for deployed LLM agents and MCP servers. Point it at an OpenAI-style chat endpoint or a stdio MCP server; it runs evidence-based probes (system-prompt leakage, indirect injection through fetched content, tool-description injection, path traversal, internal-metadata fetches, markdown exfiltration, unconfirmed sensitive actions) mapped to the OWASP Top 10 for LLM Applications, with vulnerable and hardened mock targets and one documented run against a real open-source MCP server.
- **[safeguard-probe](https://github.com/VISHNU0906/safeguard-probe)**: automated testing of misuse safeguards across multi-turn and multi-session interactions. Six strategy families, three detector levels, a labelled multi-interaction benchmark and an Inspect task adapter. Benign by construction and offline against a deterministic mock model.
- **[agentlog-monitor](https://github.com/VISHNU0906/agentlog-monitor)**: monitors for multi-agent transcripts (instruction propagation between agents, acrostic and invisible-Unicode covert channels, role drift, agreed-token signals), a synthetic corpus with ground truth, and a red-versus-blue mutation mode that shows which monitors break.
- **[mirage](https://github.com/VISHNU0906/mirage)**: a deliberately vulnerable LLM application and an attack framework across the OWASP LLM and API Top 10, paired with a hardened build.

**Earlier AI-safety scaffolds (June 2026, offline mock targets; each README says what is real)**

- **[taint](https://github.com/VISHNU0906/taint)**: detects when an agent followed indirect prompt injection hidden in a page, file or tool output, and gates the high-risk responses.
- **[autoforge](https://github.com/VISHNU0906/autoforge)**: a loop that searches for jailbreak strategies without hand-written payloads and clusters them into a taxonomy.
- **[refusal-climb](https://github.com/VISHNU0906/refusal-climb)**: uses a refusal direction and strength as a search signal to map the refusal boundary.

**Cloud and application security**

- **[gatekeeper](https://github.com/VISHNU0906/gatekeeper)**: a CI/CD security gate that consolidates SAST, dependency, secret, IaC and container scanners into one report, with baseline diffing and false-positive triage.
- **[cloudrange](https://github.com/VISHNU0906/cloudrange)**: a vulnerable AWS environment, an IAM privilege-escalation attack chain, and a read-only auditor that maps each path back to a fix.

**Security observability**

- **[bastion](https://github.com/VISHNU0906/bastion)**: turns security signals (certificate expiry, CVEs, authentication failures) into metrics, service-level objectives, dashboards and incident routing.
- **[triage](https://github.com/VISHNU0906/triage)**: correlates alert storms into root-cause incidents to cut on-call noise.

### Background

Patent IN584433 (Government of India, 2026), first-named inventor, built with my team.
SANS NetWars Tournament Core, 1st place; OWASP AppSec Bangalore BeSec CTF, 1st place.
GIAC GFACT, GSEC and GCIH; CEH; eJPT; ISC2 CC; OSCP in progress.
B.Tech in Computer Science and Engineering (Cyber Security), Jain University, expected 2027.

Open to AI-safety research and security-engineering roles.
