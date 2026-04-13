# jeremy-trinity.github.io

> Professional repository of **Jeremy Trinity (da Trindade)**, Systems, Networks and Cybersecurity Engineer in Formation.
> Live at **[jeremytrinity.com](https://jeremytrinity.com)**

---

## Primary Objective

This repository tracks the structured acquisition of the **RNCP Level 6 qualification** (Bachelor equivalent, Niveau 6 / Bac+3) in Systems, Networks and Cybersecurity Administration, delivered via OpenClassrooms on an alternance pathway. The RNCP40356 title is the formal academic foundation required to enter the French technology labour market at a professional engineering level, meeting the hiring standards of international firms established in the Paris region.

The tracker hosted at this repository serves as a live, auditable record of every certification completed toward that objective.

---

## Strategic Target: 53 US Enterprises in the Paris Region

The employment strategy concentrates on **53 US-headquartered technology and consulting companies** accessible within a 120-minute public transport radius of central Paris. These firms represent the intersection of three criteria: Azure-first infrastructure (38 of 53 companies), active alternance hiring, and a documented demand for DevSecOps and Cloud Infrastructure engineers with formal French qualifications.

Priority is given to companies that have established French legal entities and are therefore eligible to host alternance contracts under OPCO financing mechanisms. RQTH status (disability recognition) further strengthens eligibility for AGEFIPH-supported placements and removes the standard over-33 age barrier on alternance contracts.

---

## Proof of Work: The /certs/ Directory

The `/certs/` directory in this repository functions as a verified gallery of completed certifications for recruiters and hiring managers. Each certificate is stored as a PDF named by its tracker ID (e.g., `p0-01.pdf`, `p3-01.pdf`).

When a certificate is marked `completed: true` in `progress.json`, the tracker automatically redirects its link from the external course page to the local `/certs/[ID].pdf` file. This creates a zero-friction path from the recruiter's browser to verifiable proof of completion.

To submit a new certificate: upload the PDF to `/certs/`, set the corresponding entry in `progress.json` to `completed: true` with the completion date, and commit.

---

## Professional Background

Jeremy functioned in practice as an Operations Manager across a period of sustained operational responsibility, despite carrying the official title of Team Leader. His duties encompassed team rotation management, coordination with regional leadership, performance indicator tracking, and continuous onboarding of new staff. This experience establishes a proven capacity to bridge strategic direction and ground-level execution, a combination directly applicable to the cross-functional demands of DevSecOps environments.

The career pivot from operations management to cloud infrastructure engineering is deliberate and structured: it is grounded in the Five Pillars development methodology, refined through the Cinq-Piliers framework, and now formalised through the RNCP40356 pathway. Each certification in this tracker represents a step in a sequence designed for zero bad practices from the foundation upward.

---

## Certification Roadmap Summary

| Phase | Focus | Certifications | Investment |
|---|---|---|---|
| Phase 0 | Quick Wins: This Week | 8 | EUR 0 |
| Phase 1 | Quick Wins: Weeks 2-4 | 8 | EUR 0 |
| Phase 2 | Technical Foundations | 7 | Mostly EUR 0 |
| Phase 3 | Security and Linux | 4 | EUR 0 |
| Phase 4 | Azure Fundamentals | 3 | ~EUR 165 per exam |
| Phase 5 | Advanced DevOps and Security | 5 | Partially paid |

Total: 35 certifications across 4 RNCP competency blocs, complemented by 7 administrative milestones and 5 daily habit trackers.

The four RNCP40356 competency blocs covered are: OS and virtualisation administration (Bloc 1), network and cloud infrastructure (Bloc 2), cybersecurity and data protection (Bloc 3), and secure infrastructure project management (Bloc 4).

---

## Language Philosophy: English through Use

English is not a separate subject in this programme. It is the primary working language for technical documentation, certification study materials, professional correspondence, and repository content. This approach, treating English as an active professional tool rather than a subject of study, is a deliberate application of immersion-based acquisition derived from the "Pilier 4" language methodology developed across this project.

All certification content, technical reading, and professional communication defaults to English. French is used for administrative and legal documents, OpenClassrooms coursework, and interactions with French public institutions.

---

## Repository Structure

```
jeremy-trinity.github.io/
|
|-- index.html          # Bilingual FR/EN dark-mode certification tracker
|-- progress.json       # Source of truth for completion state (sync across devices)
|-- README.md           # This file
|-- certs/              # Verified certificate gallery (PDF, named by tracker ID)
|   |-- p0-01.pdf       # Example: Claude 101 (Anthropic)
|   |-- p3-01.pdf       # Example: ISC2 Certified in Cybersecurity
|   `-- ...
```

---

## Infrastructure and Deployment

```
Domain Registrar: site.pt (jeremytrinity.com)
     |
Nameservers: Cloudflare (lucy.ns / marty.ns)
     |
DNS Records:
  A     @    -> 185.199.108.153  (GitHub Pages)
  A     @    -> 185.199.109.153  (GitHub Pages)
  A     @    -> 185.199.110.153  (GitHub Pages)
  A     @    -> 185.199.111.153  (GitHub Pages)
  CNAME www  -> jeremy-trinity.github.io
     |
CDN and SSL: Cloudflare (Free plan)
     |
Hosting: GitHub Pages (jeremy-trinity.github.io)
     |
Live URL: https://jeremytrinity.com
```

Cloudflare operates in DNS-only mode on A records to allow GitHub Pages to manage SSL verification correctly. HTTPS enforcement is active in GitHub Pages settings.

---

## How to Sync Progress

1. Open `index.html` in a browser and mark certifications as completed using the checkboxes.
2. Click **Export progress.json** to generate the updated state.
3. Paste the JSON into `progress.json` in this repository and commit.
4. On a new device, load the page and click **Import from GitHub**, paste the JSON, and click Load.

Alternatively, edit `progress.json` directly on GitHub: set `"completed": true` and add a `"date": "YYYY-MM-DD"` value for the relevant certification ID.

---

## Contact

| | |
|---|---|
| **Email** | [jeremytrinity.me@gmail.com](mailto:jeremytrinity.me@gmail.com) |
| **LinkedIn** | [linkedin.com/in/jeremy-trinity](https://www.linkedin.com/in/jeremy-trinity) |
| **GitHub** | [github.com/jeremy-trinity](https://github.com/jeremy-trinity) |
| **Website** | [jeremytrinity.com](https://jeremytrinity.com) |
| **Location** | Paris, France (from 26 August 2026) |

---

*Last updated: April 2026. Pivoted to RNCP40356 following strategic alignment with Deloitte consulting standards and the formal requirements of the 53-company target portfolio.*
