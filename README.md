# Contoso Health · Azure L400 workshop

**Open the interactive guide: https://ibranibeny.github.io/contoso-health-l400-workshop/**

An expert-level (L400) workshop for infrastructure and DevOps engineers. Contoso Health, a fictional health insurer in Indonesia, moves its member portal (React frontend, Node.js API, Azure Managed Redis, Azure Database for PostgreSQL) onto a Well-Architected Azure landing zone in Indonesia Central, behind the Web Application Firewall on Application Gateway. You build it with Bicep or Terraform, containerize it and run it on AKS, then run the whole lifecycle through GitHub: repository governance, GitHub Copilot agents, GitHub Actions and Codespaces.

## What is in this repository

| File | What it is |
|---|---|
| [`index.html`](https://ibranibeny.github.io/contoso-health-l400-workshop/) | The interactive guide: one self-contained page with 10 modules, 93 hands-on steps and 20 animated, clickable architecture diagrams. Switch Bicep or Terraform once for the whole page, turn on facilitator notes, track your progress. |
| [`contoso-health-workshop-kit.zip`](contoso-health-workshop-kit.zip) | The workshop kit: the application with its tests, Dockerfiles, Kubernetes manifests, Bicep and Terraform for the landing zone, PaaS workload and AKS (including the WAF policy), GitHub Actions workflows, Copilot instructions and custom agents, a dev container, and the smoke, WAF and browser deployment tests. |

## Modules

| # | Module | Duration |
|---|---|---|
| 1 | Meet Contoso Health: the app and its PaaS architecture | 50 min |
| 2 | Design the landing zone the Well-Architected way | 60 min |
| 3 | Deploy the platform with Bicep or Terraform | 75 min |
| 4 | Protect the front door with the Web Application Firewall | 45 min |
| 5 | Containerize the existing application | 45 min |
| 6 | Run it on AKS, built with IaC | 75 min |
| 7 | Create and govern the repository with GitHub | 40 min |
| 8 | Agentic SDLC with GitHub Copilot | 60 min |
| 9 | GitHub Actions and agentic workflows from Codespaces | 60 min |
| 10 | Wrap-up: scorecard, clean-up and next steps | 15 min |
| | **Total** | **8 h 45 min** |

Appendices: A Coming from GitLab CI, Harbor and Rancher; B Facilitator guide; C Deploy and test runbook; D Verification status; E Workshop kit map; F Sources; G Icon legend.

## Get started

1. Open the guide at https://ibranibeny.github.io/contoso-health-l400-workshop/ (or download `index.html` and open it in any modern browser; it works offline).
2. Download and unzip the kit, then open it in a GitHub codespace or the dev container.
3. Follow the modules in order, or use Appendix C, the deploy and test runbook, to deploy everything and prove it works.

## Status

- Product facts were checked against Microsoft Learn, GitHub Docs and official release pages on 26 and 27 November 2026; every claim in the guide links to its source.
- The application tests pass locally, including the deployment tests against a local stack.
- The Bicep, Terraform, workflow and Kubernetes files were reviewed against the official references but have not been compiled or deployed yet. The kit's IaC validate workflow compiles them on the first push. Treat your first lab deployment as the acceptance test.
- Contoso Health is a fictional company. This is workshop material, not a production reference implementation.
