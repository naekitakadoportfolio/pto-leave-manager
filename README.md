<p align="center"><img src="assets/banner.svg" alt="PTO Leave Manager" width="100%"></p>

<p align="center">
<img src="https://img.shields.io/badge/stack-Apps_Script_·_Calendar_·_Slack_·_Gmail_·_HRIS-14384E?style=flat-square">
<img src="https://img.shields.io/badge/data-fictional-89CDE7?style=flat-square">
<a href="https://sider.ai/agents/web-creator/share/695ea81100a621619985fdfb"><img src="https://img.shields.io/badge/Portfolio-Nae_Kitakado-1D4C93?style=flat-square"></a>
</p>

<p align="center"><a href="https://naekitakadoportfolio.github.io/pto-leave-manager/"><img src="https://img.shields.io/badge/%E2%96%B6%20Try%20the%20live%20demo-14384E?style=for-the-badge" alt="Live demo"></a></p>

# PTO Leave Manager

A free leave-management system with role-based views. Submit a request, switch between Manager, HR and Teammate to approve it, and see how protected leave stays private while the calendar and chat update automatically.

> **Portfolio rebuild.** This is a from-scratch recreation of a production system I designed and run, rebuilt with **fictional data** and no client names, code or branding. The live demo runs entirely in the browser.

## The problem
Leave requests ran through eight separate team-specific no-code workflows with inconsistent rules, a date-format bug in most of them, and no privacy protection for sensitive leave types.

## Impact in production
Replaced the paid workflows with one free system: role-based access, dual approval, protected-leave privacy, automatic calendar, chat and HRIS updates, and a cleanup orchestrator that fixed historical timezone and duplicate-row issues.

## What it demonstrates
| Capability | How |
|---|---|
| Role-based access | Employee, Manager, HR and Teammate views |
| Dual-approval workflow | Manager → HR state machine |
| Privacy by design | Protected leave types are masked from teammates |
| Business rules | Working-day counts, balance checks, overlap warnings |
| Integrations | Calendar event, chat post, email and HRIS sync on approval |

## Production architecture
Apps Script web app · Sheets data model · CalendarApp · Gmail · Slack webhooks · project-tool API · HRIS sync · installable triggers

## Try it
Open the **[live demo](https://naekitakadoportfolio.github.io/pto-leave-manager/)** or run `index.html` locally. No install needed.

---
<p align="center"><sub>Built by <b>Nae Kitakado</b>, AI Automation Consultant · <a href="https://www.linkedin.com/in/nae-k-203194265">LinkedIn</a> · <a href="https://sider.ai/agents/web-creator/share/695ea81100a621619985fdfb">Portfolio</a> · open to retainer &amp; part-time consulting</sub></p>
