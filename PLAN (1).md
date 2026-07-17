# PLAN.md — TTPR Cybersecurity Research Project

> Status: 🟡 TBD — Research direction not yet decided. This is a generic template; fill in the blanks once the team picks a direction.

## 1. Background

A research project in collaboration with the Cybersecurity Reach Foundation (501c3) and TTPR @baruch. The team will analyze real cybersecurity data and publish a research report.

- Datasets:
  - `events` — Honeypot attack logs, 35M+ records, capturing attack source, targeted service, attempted usernames/passwords, exploits used, etc.
  - `ransomlook_posts` — Ransomware gangs' public "shame site" data: victim organization, gang name, date discovered
- Tools: Metabase (already set up, no configuration needed) / SQL / Python / Excel / Tableau — team's choice
- References:
  - [Data Guide — field explanations](https://ttpr.cybersecurityreach.org/guide.html)
  - [Project Ideas — 10 candidate directions](https://ttpr.cybersecurityreach.org/ideas.html)
  - Contact: Leonard (leonard.melnik@cybersecurityreach.org)

## 2. Research Question

> ⬜ **TBD** — One sentence, specific and answerable with the data (avoid something too broad)

**Candidate directions (team picks one after discussion, or defines a custom one):**

| # | Direction | Summary |
|---|-----------|---------|
| A | Honeypot attack behavior analysis | Geo × time patterns / password strategy / post-"login" attacker behavior / scanner fingerprinting / spike & anomaly investigation |
| B | Ransomware gang profiling | Gang rise-and-fall lifecycle, victim industry/geography distribution, or a deep profile of a single gang (e.g., LockBit, Akira) |
| C | Combined dataset analysis | Whether honeypot attack volume correlates over time with ransomware victim counts — the most ambitious but most original direction |
| D | Other / custom | ______________________ |

## 3. Team Roles

| Name | Responsibility | Notes |
|------|-----------------|-------|
| | Data exploration / querying | |
| | Visualization | |
| | Report writing | |
| | Project coordination / liaison with Leonard | |

## 4. Timeline (~6 weeks, aligned with the program's pace)

- [ ] **Week 1–2** Explore the data, form the team, define a research question
- [ ] **Week 3–4** Deep-dive analysis, build visualizations that support the findings
- [ ] **Week 5** Draft the written report (tell the story behind the data)
- [ ] **Week 6** Revise, finalize, and publish under the Foundation's name

## 5. Deliverables

- [ ] A clearly defined research question
- [ ] Analysis results (SQL/Python/Excel/Tableau, any of these)
- [ ] Visualizations that back up the conclusions
- [ ] A complete written report (explaining what was found and why it matters)

## 6. Suggested Repo Structure

```
joint-project-/
├── README.md          # Project overview
├── PLAN.md             # This file
├── data/               # Exported data / query results (avoid committing very large files)
├── queries/             # SQL queries
├── notebooks/           # Analysis code (Python/Jupyter etc.)
├── viz/                 # Charts, visualization outputs
└── report/              # Draft and final report
```

## 7. Next Steps

- [ ] Team discussion — pick a direction from A/B/C/D above, update Section 2
- [ ] Ask Leonard for Metabase login access
- [ ] Read through the Data Guide to get familiar with the fields
- [ ] First team meeting — assign roles from Section 3
