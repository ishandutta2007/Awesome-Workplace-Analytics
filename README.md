# Awesome-Workplace-Analytics

# Top Workplace Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Employee Productivity, Collaboration Insights & Workforce Intelligence*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Workplace Analytics**. These tools measure and improve how work happens across organizations — analyzing collaboration patterns, productivity trends, meeting culture, and employee engagement to help leaders make data-driven decisions about their workforce.

**Examples** include Microsoft Viva Insights, Humanyze, ActivTrak, Teramind, Culture Amp, Worklytics, Perceptyx, Time Doctor, Hubstaff, and Workvivo (the category leaders).

**Open-source emphasis**: The open-source ecosystem for workplace analytics is anchored by **Kimai** (web-based time tracking), **Ever Gauzy** (open business management platform), and emerging employee engagement tools like **Alignify**. While commercial platforms lead in advanced behavioral analytics and validated survey frameworks, open-source tools provide strong time tracking and employee feedback foundations with full data ownership.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Microsoft Viva Insights](https://www.microsoft.com/microsoft-viva/insights)**  
  Personal and organizational productivity analytics integrated with Microsoft 365. Personal insights included in E3/E5; organizational insights require $6/user/month add-on. Measures collaboration hours, email activity, meeting time, and Copilot adoption. **Key limitation**: does not report email reply time, does not support shared mailboxes, and cannot measure external customer wait times — making it a workload metric rather than a service metric .

- **[Humanyze](https://humanyze.com/)**  
  Behavioral analytics and Organizational Network Analysis (ONA) platform that produces an **Organizational Health Score** to quantify engagement, productivity, capacity, and attrition. Integrates with 20+ platforms including Microsoft 365, Slack, Jira, and GitHub. **Privacy by design**: analyzes only metadata (no content), uses pseudonymization and aggregation, and is SOC 2 Type 2 compliant .

- **[ActivTrak](https://www.activtrak.com/)**  
  Workforce analytics and productivity monitoring platform starting at $10/user/month. Tracks application usage, idle time, and productivity trends with dashboards for spotting inefficiencies. Integrates with Power BI, Tableau, and Google Data Studio for custom reporting .

- **[Teramind](https://www.teramind.com/)**  
  Insider threat management and employee monitoring platform covering activity tracking, data loss prevention, and behavioral analytics. Supports policy-based controls for regulatory compliance with real-time alerts and visual analytics. Available via cloud or on-premise deployment .

- **[Culture Amp](https://www.cultureamp.com/)**  
  Employee experience platform combining engagement surveys, performance management, and skills development. Offers extensive benchmarks by industry, company size, and region with AI-powered insights. Self-Starter tier covers 25-200 users; ISO 27001 certified and GDPR compliant .

- **[Worklytics](https://www.worklytics.co/)**  
  Privacy-first workplace analytics platform starting at $2,500/month (Business) for 100-1,000 employee organizations. Analyzes collaboration patterns, meeting effectiveness, manager effectiveness, and AI adoption across 50+ integrations including Slack, Microsoft Teams, Zoom, and GitHub. **Free tier**: up to 100 users with calendar data only .

- **[Perceptyx](https://www.perceptyx.com/)**  
  Employee survey and people analytics platform with customizable survey programs covering onboarding, lifecycle, and exit stages. Provides performance metrics, interactive dashboards, and built-in recommendations with consultant support for presenting results to leadership .

- **[Time Doctor](https://www.timedoctor.com/)**  
  Time tracking and productivity platform with four plans: Basic ($6.67/user/month annual), Standard ($11.67), Premium ($16.70), and Enterprise. Premium adds Benchmarks AI, Unusual Activity AI, mouse jiggler detection, video screen recording, and meeting insights. 14-day free trial .

- **[Hubstaff](https://hubstaff.com/)**  
  Time tracking and workforce management platform starting at $4.99/seat/month (Starter). Grow tier ($7.50) adds tasks, idle timeout, and one integration. Enterprise ($25) includes HIPAA compliance, SOC-2 Type II, SCIM provisioning, and silent app tracking. Optional Insights add-on ($2.50/seat) provides suspicious activity detection .

- **[Workvivo](https://workvivo.com/)**  
  Employee engagement and communication platform (acquired by Zoom) with video, podcast, and social networking features for team collaboration. Starting at $20,000 one-time. Integrates with Zoom, Slack, and Microsoft Teams .

## Open-Source GitHub Projects

- **[Kimai](https://github.com/kimai/kimai)**  
  The leading open-source web-based multi-user time-tracking application with 4,000+ GitHub stars and MIT license. Works for freelancers, companies, and organizations of any size — track times, generate reports, create invoices, and manage teams. SaaS version available at kimai.cloud. **The de facto open-source alternative to Toggl and Harvest** for organizations wanting full data ownership .

- **[Ever Gauzy](https://github.com/ever-co/ever-gauzy)**  
  Open Business Management Platform (ERP/CRM/HRM/ATS/PM) that includes time tracking and workforce analytics capabilities. 2,500+ GitHub stars, MIT licensed. Comprehensive alternative for organizations wanting an integrated platform covering HR, project management, and time tracking in one self-hosted solution .

- **[Alignify](https://github.com/iam-tsr/alignify)**  
  AI-powered employee engagement platform built for closing the communication gap between employees and employers through anonymous surveys. Uses **Qwen model** for automated question generation and **DistilBERT** for employee feedback classification. Features survey panel, analytics dashboard with AI-generated improvement suggestions, and weekly automated survey distribution. Beta stage, open source to serve employee interests .

- **[Employee Performance Analytics](https://github.com/Equaliserspasticparalysis650/Employee-Performance-Analytics)**  
  SQL and Python-based tool for analyzing employee performance and departmental productivity. Features KPI dashboards, efficiency trend tracking, workload balancing insights, and data visualization for HR decision-making. Open-source with contributions welcome .

- **[tietracker](https://github.com/peterpeterparker/tietracker)**  
  Simple, open-source, free time tracking app available on multiple platforms. Lightweight alternative for individuals and small teams needing basic time tracking without enterprise features .

- **[dominikbraun/timetrace](https://github.com/dominikbraun/timetrace)**  
  Simple CLI for tracking working time, written in Go. Ideal for developers who prefer terminal-based workflows with minimal overhead .

- **[urlaubsverwaltung/zeiterfassung](https://github.com/urlaubsverwaltung/zeiterfassung)**  
  Digital working time recording for German companies, designed for compliance with German labor law requirements. Open-source with Docker deployment .

- **[TeamTrack](https://github.com/goodmagma/teamtrack)**  
  Web-based, self-hosted time tracking app built with Laravel & Livewire. Designed for team time tracking with reporting capabilities .

- **[timesheet (rfrost-xyz)](https://github.com/rfrost-xyz/timesheet)**  
  Python-based timesheet management app tracking time entries for projects, stages, and tasks using SQLite. Terminal menu interface for adding entries and viewing timesheets .

### Additional Strong Open-Source Options

- **TimeAudit** — Python desktop application prompting user activity every 25 minutes, with logs analyzable via custom GPT model for time management insights .
- **Jikan TimeTracking Tool** — C# WPF customizable time-tracking tool with SQLite or SQL Server, project-based logging, and graphical reports .
- **WorkingTimeMeasurementSystem** — Simple Go + SQLite work time tracking system example .
- **DevClock** — Time tracking web application with multiple functionalities .
- **eager** — Tool for maintaining and synchronizing one worklog across different services .

**Frameworks for building custom workplace analytics solutions**: Combine **Kimai** for comprehensive time tracking with reporting and invoicing . Use **Ever Gauzy** for an integrated ERP/HRM/PM platform with workforce analytics . Deploy **Alignify** for AI-powered employee engagement surveys with automated question generation and feedback classification . Integrate **Employee Performance Analytics** for SQL-based KPI dashboards and productivity analysis . Note that true workplace analytics with Organizational Network Analysis, meeting effectiveness scoring, and validated engagement benchmarks (like Humanyze's Organizational Health Score or Culture Amp's benchmarks) remain primarily commercial territory; open-source stacks provide strong time tracking and employee feedback foundations that require integration for complete workforce intelligence.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Workplace analytics tools collect sensitive employee data and must comply with data privacy regulations (GDPR, CCPA) and employment law. Self-hosted solutions require proper security hardening and access controls.
- Behavioral analytics and monitoring tools raise significant privacy and ethical concerns. Ensure transparency with employees, obtain proper consent where required, and use data to improve working conditions rather than for punitive surveillance .
- The open-source ecosystem provides strong time tracking and employee feedback foundations, but Organizational Network Analysis, validated engagement benchmarks, and advanced behavioral analytics remain primarily commercial offerings.

---

**Made for HR leaders, people analytics teams, operations managers, and workforce intelligence professionals.**  
Let's make workplace analytics more open, transparent, and employee-centric.
