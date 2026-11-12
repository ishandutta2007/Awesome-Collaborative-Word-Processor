# Awesome-Collaborative-Word-Processor

# Top Collaborative Word Processor Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Co-Editing, Document Collaboration & Cloud-Native Writing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Word Processors**. These tools enable teams to write, edit, and review documents together in real time—covering rich text editing, suggestion mode, comment threads, version history, and AI-assisted drafting that eliminates the friction of emailing documents back and forth.

**Examples** include Google Docs, Microsoft Word Online, Zoho Writer, Notion, Quip, Dropbox Paper, OnlyOffice Document Editor, Coda, Slite, and Apple Pages iCloud (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted collaborative editors, open-source document suites, and community-driven writing platforms—ideal for organizations seeking data sovereignty, offline capability, and vendor neutrality over per-seat cloud subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Google Docs](https://docs.google.com/)** | Browser-based word processor within Google Workspace. Real-time collaboration, suggestion mode, version history, and Gemini AI integration. Free for personal Google accounts with 15 GB shared storage . | Business Starter: $7/user/month (annual); Business Standard: $14 | **Free (personal Google account)**: full Docs editor, 15 GB shared Google Drive storage, collaboration features. **14-day trial** for Workspace Business plans |
| **[Microsoft Word Online](https://www.microsoft.com/en-us/microsoft-365/word)** | Web version of Word with core editing, real-time co-authoring, and 5 GB OneDrive storage on the free tier . | Microsoft 365 Business Basic: $7/user/month (rising July 2026) | **Free**: Word web version, 5 GB OneDrive storage, basic templates, real-time collaboration. No time-limited trial for free tier |
| **[Zoho Writer](https://www.zoho.com/writer/)** | Cloud word processor within Zoho Office Suite. Real-time collaboration, track changes, comments, and integration with Zoho ecosystem. Free for individuals . | Paid plans available via Zoho Workplace (Standard/Professional) | **Free for individuals**: full document editing, real-time collaboration, integration with Zoho apps |
| **[Notion](https://www.notion.so/)** | All-in-one workspace with document editing embedded in pages and databases. Supports collaborative editing, comments, and AI writing assistance. Free plan includes unlimited pages for individuals and up to 10 guests . | Plus: ~$10/user/month; Business: ~$18/user/month (annual) | **Free**: unlimited pages for individuals, 10 guests, 5 MB file uploads, 7-day page history |
| **[Quip](https://quip.com/)** | Salesforce-owned collaborative document and spreadsheet platform with embedded chat. Real-time editing with comments and @mentions. Starter plan includes unlimited documents . | Starter: $10/user/month (annual); Plus: $25; Advanced: $100 | **No free tier**; paid plans only. Special offer: $30 for first five users (Starter, annual) |
| **[Dropbox Paper](https://www.dropbox.com/paper)** | Collaborative document tool integrated with Dropbox. Real-time editing, comments, and task assignment. Free for all Dropbox users . | Free with any Dropbox account; paid Dropbox plans for additional storage | **Free forever**: unlimited Paper documents with a Dropbox account |
| **[OnlyOffice Document Editor](https://www.onlyoffice.com/)** | Docs, Sheets, Slides, and DocSpace collaboration platform. Cloud Startup plan is free for small teams; self-hosted editions available . | Cloud Startup: Free (3 admins, 12 rooms, 2 GB); Enterprise/Developer: quote-only | **Free (Startup)**: 3 admins, unlimited users/visitors, 12 rooms, 2 GB storage |
| **[Coda](https://coda.io/)** | Document-platform hybrid with tables, buttons, and automations. Billed only for Doc Makers (creators); Editors and Viewers are free . | Pro: $10/month per Doc Maker; Team: $30/month per Doc Maker | **Free**: unlimited unshared docs, 1 GB per doc, 7-day version history |
| **[Slite](https://slite.com/)** | Collaborative knowledge base and document editor with AI-powered search. Free plan available with limited documents and version history . | Paid plans available; free tier offered | **Free**: basic document editing, limited AI features, community support |
| **[Apple Pages iCloud](https://www.icloud.com/)** | Web version of Apple Pages accessible via iCloud.com from any browser. Real-time collaboration, rich formatting, and export to DOCX/PDF . | **Free** with an Apple ID | **Free forever**: full Pages editor via iCloud.com, real-time collaboration, export options |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[LibreOffice Writer](https://github.com/LibreOffice/core)** | [![Stars](https://img.shields.io/github/stars/LibreOffice/core?style=social&color=white)](https://github.com/LibreOffice/core/stargazers) | The flagship open-source word processor from The Document Foundation. Native ODF plus solid DOCX compatibility. Runs fully offline with no account required and no telemetry. The desktop reference for free document editing . |
| **[OnlyOffice Document Server](https://github.com/ONLYOFFICE/DocumentServer)** | [![Stars](https://img.shields.io/github/stars/ONLYOFFICE/DocumentServer?style=social&color=white)](https://github.com/ONLYOFFICE/DocumentServer/stargazers) | Self-hosted collaborative document editing server. Integrates with Nextcloud, ownCloud, SharePoint, and custom apps via API. Strong Microsoft format compatibility and real-time co-editing. AGPL for community edition . |
| **[Etherpad](https://github.com/ether/etherpad)** | [![Stars](https://img.shields.io/github/stars/ether/etherpad?style=social&color=white)](https://github.com/ether/etherpad/stargazers) | Real-time collaborative text editor with a plugin ecosystem. Lightweight and embeddable; often used as a building block for custom document workflows. Self-hosted with no per-seat fees . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[CryptPad](https://github.com/cryptpad/cryptpad)** | [![Stars](https://img.shields.io/github/stars/cryptpad/cryptpad?style=social&color=white)](https://github.com/cryptpad/cryptpad/stargazers) | Privacy-first, end-to-end encrypted collaboration suite with rich text, sheets, slides, code, and kanban. Zero-knowledge architecture means the server cannot read document contents. Self-hostable . |
| **[Nextcloud Office](https://github.com/nextcloud/richdocuments)** | [![Stars](https://img.shields.io/github/stars/nextcloud/richdocuments?style=social&color=white)](https://github.com/nextcloud/richdocuments/stargazers) | Nextcloud integration with Collabora Online or ONLYOFFICE, turning a self-hosted Nextcloud instance into a full productivity suite with file storage, sharing, and real-time document editing . |

**Frameworks for building custom systems**: Combine **LibreOffice Writer** for offline authoring, **OnlyOffice Document Server** or **Collabora Online** for web-based real-time editing, and **Nextcloud** for file storage and sharing—deployable entirely on-premises or in a private cloud with Docker Compose.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Collaborative word processors handle potentially sensitive business and personal documents; review data processing terms and access controls before uploading confidential information.
- Self-hosted open-source editors require proper backups, security updates, and collaborative editing server hardening; misconfigured document servers can expose sensitive files or allow unauthorized editing. Free tier limits and pricing change frequently—verify against vendor pages before committing.

---

**Made for writers, editors, operations teams, and developers building document collaboration infrastructure.**  
Let's make collaborative word processing more open, sovereign, and collaborative.
