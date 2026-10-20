<div align="center">

<img src="assets/logo.png" width="96" alt="Sanad logo">

# Sanad Business

**The smart workplace system for Saudi companies: mail, approvals, people and numbers in one place, with an assistant that speaks your dialect.**

نظام شركتك الذكي: البريد والموافقات والفريق والأرقام في مكان واحد، وسند يساعدك فيها بلهجتك، بالكتابة أو بالصوت.

[**Try the live demo**](https://calm-field-7452sanad-business.re4679607.workers.dev) · [Features](#what-it-does) · [How it works](#how-its-built) · [Security](#security)

</div>

<p align="center"><img src="assets/hero.png" alt="Sanad Business: manager dashboard and employee phone view"></p>

---

## Why I built it

Most companies here run on a patchwork: email in Outlook, leave requests on paper or WhatsApp, attendance in one tool, sales in a spreadsheet. The manager ends up chasing people for updates and nobody knows where a request is stuck.

Sanad Business plugs into the company as **one system**, not another separate app. Every page has an owner, every request has a clear path, and Sanad (the assistant) keeps an eye on the work and tells the manager what needs attention, in Saudi Arabic.

## Try it

> **Live demo:** [https://calm-field-7452sanad-business.re4679607.workers.dev](https://calm-field-7452sanad-business.re4679607.workers.dev)
>
> No sign-up. Pick a role (company manager, employee, or café owner) and you get a private sandbox company with realistic data. It deletes itself after 24 hours.

## What it does

### For the manager
- **One home screen** with today's revenue, attendance, pending approvals, unread mail and meetings.
- **"Sanad notices"**: a live list of what needs you: late tasks, low stock, stuck requests, pages whose owner hasn't updated them.
- **Auto mode vs "I'm here"**: let Sanad follow up with staff on your behalf, or switch it off and handle things yourself.

<p align="center"><img src="assets/screens/kpi.png" width="49%" alt="KPIs"> <img src="assets/screens/responsibilities.png" width="49%" alt="Page owners"></p>

### Mail that works with what you already have
- Connect **Outlook (Microsoft 365)** or **Gmail**, or use a company address hosted by Sanad.
- Shared company inbox for the manager and whoever owns the mail page.
- Sanad can summarise a thread, suggest a reply, or polish your wording, **only when you ask**. People still write and send their own mail.

<p align="center"><img src="assets/screens/mail.png" alt="Mail"></p>

### Requests and approvals
- Leave, salary letters, advances, expenses, IT requests, each with its own approval chain: department head → HR or IT → finance for money.
- Before each decision Sanad shows the facts: leave balance, who else is off and team coverage, meetings the person would miss, and working days (Sunday to Thursday).
- Employment letters generated automatically once approved.

<p align="center"><img src="assets/screens/approval.png" alt="Approval chain"></p>

### People and structure
- Departments with heads, job titles, personal sign-in codes or company SSO (Microsoft / Google).
- Attendance with a grace period, announcements with read receipts, a shared calendar, and a documents & policies library.
- **Every page has an owner.** Sanad tracks whether each owner keeps their page up to date and reports to the manager.

<p align="center"><img src="assets/screens/attendance.png" width="49%" alt="Attendance"> <img src="assets/screens/calendar.png" width="49%" alt="Calendar"></p>

### Performance and customers
- Per-employee KPIs: sales target progress, revenue collected, profit margin.
- Customer ratings through a simple public link, plus repeat-customer tracking.

### For employees
Each employee sees **only their own work**: their attendance, requests, mail, tasks and KPIs. One tap to ask for leave, and a side panel to reach the manager or ask Sanad for help.

<p align="center">
<img src="assets/screens/phone-staff.png" width="24%" alt="Employee home">
<img src="assets/screens/phone-leave.png" width="24%" alt="Leave request">
<img src="assets/screens/phone-sanad.png" width="24%" alt="Talking to Sanad">
<img src="assets/screens/phone-login.png" width="24%" alt="Sign in">
</p>

### Arabic first, English too
The whole interface is right-to-left Arabic by default, and switches to English with one tap.

<p align="center"><img src="assets/screens/home-en.png" width="49%" alt="English home"> <img src="assets/screens/requests-en.png" width="49%" alt="English requests"></p>

## Payroll and HR operations

- **Monthly payroll** with GOSI worked out per employee (Saudi and non-Saudi rates), advance instalments, unpaid leave deductions and absences flagged for review. Draft → approved → paid, and each employee gets their payslip.
- **Mudad (WPS) and bank transfer files** ready to download once the run is approved.
- **Resignations and offboarding:** Sanad checks the notice period, the end-of-service award, the leave balance owed, and any company custody that hasn't come back.
- **Location check-in:** set the office location and radius; attendance shows who checked in on site and who didn't.
- **Reports** for staff, attendance, leave, requests, documents and custody, exportable to Excel.
- **Integrations page** showing what's connected: Microsoft 365, Google Workspace, Mudad, banks, GOSI, Excel and the Saudi voice.

<p align="center"><img src="assets/screens/payroll.png" alt="Monthly payroll run"></p>
<p align="center"><img src="assets/screens/resignation.png" width="49%" alt="Sanad's check on a resignation"> <img src="assets/screens/attendance-location.png" width="49%" alt="Attendance with office location"></p>
<p align="center"><img src="assets/screens/phone-payslip.png" width="24%" alt="Employee payslip"> <img src="assets/screens/integrations.png" width="73%" alt="Integrations"></p>

## Security and compliance

Built for what Saudi companies ask before they sign. Everything below is live in the demo.

- **Saudi labour law:** all statutory leave types, sick pay tiers (30 days full, 60 at 75%, 30 unpaid), 21 days of annual leave rising to 30 after five years, official holidays left out of leave days, Hijri dates on screens and letters, and the end-of-service award under articles 84 and 85.
- **Employee files:** ID, iqama, passport, contract and insurance with expiry alerts 30 days ahead, plus company custody that has to come back before someone leaves.
- **Two-step sign-in** with any authenticator app, on top of personal codes and Microsoft or Google single sign-on.
- **Permissions by role:** manager, department head, HR, finance, IT, page owner and employee each see only what their role needs.
- **Audit log** of every sign-in, decision and sensitive change, exportable as CSV.
- **Your data, your call:** see where it's stored and who processes it, export everything in one file, delete the company account with a 7-day grace period, and switch the AI off for the whole company.
- **Security testing:** a live security check in the app, and automated penetration tests (cross-company access, forged sessions, cross-site requests, brute force, two-step bypass and more) on every release.

<p align="center"><img src="assets/screens/security.png" alt="Security and privacy page"></p>
<p align="center"><img src="assets/screens/labour-check.png" width="49%" alt="Sanad's labour-law check on a sick leave"> <img src="assets/screens/employee-file.png" width="49%" alt="Employee file with documents and custody"></p>
<p align="center"><img src="assets/screens/two-step.png" width="49%" alt="Two-step sign-in setup"> <img src="assets/screens/audit-log.png" width="49%" alt="Audit log"></p>

## How it's built

| Layer | Choice |
|---|---|
| Runtime | Cloudflare Workers (single worker, edge-deployed) |
| Database | Cloudflare D1 (SQLite) with forward-only migrations |
| Front end | Hand-written HTML/CSS/JS, no framework, IBM Plex Sans Arabic |
| Assistant | Large language model with tool calling, scoped per role |
| Mail | Microsoft Graph, Gmail API, Resend (outbound), Cloudflare Email Routing (inbound) |
| Sign-in | Signed session cookies, per-employee codes, Microsoft / Google SSO |
| Tests | 77 automated tests covering approvals, payroll, labour law, mail, SSO, attendance, security and the demo |

## Security in the code

- No keys or passwords in the front end or in this repository; all secrets live in the platform's secret store.
- Employee codes and passwords are stored as HMAC hashes, never in plain text.
- Mail OAuth tokens are encrypted at rest (AES-GCM).
- Every API checks the role and the page owner before acting; employees can't see each other's data.
- Demo sandboxes are rate-limited, can't send real email, and are wiped after 24 hours.

## About

Designed and built by **Reema Ghazi**, software engineering student at Gulf Colleges.

This repository is a showcase. The source code is private.
