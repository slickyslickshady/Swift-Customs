# Swift Customs — Customs Clearance Accounting System

An interactive **prototype** of *Swift Customs*, a customs clearance accounting system
built for customs brokers and clearing agents in Jordan. Developed as a Graduation
Project (GP1) at **Middle East University**, Faculty of Information Technology.

## About
Swift Customs automates customs duty and tax calculations, manages declarations and
clients digitally, generates invoices, records payments, and authenticates receipts
through Jordan's national **JoFotara** e-invoicing platform (QR-code verification with
the Income & Sales Tax Department, ISTD).

This repository contains:
- **`index.html`** — a clickable front-end prototype (single HTML file, no backend) that
  demonstrates the full user journey with sample data.
- **`Swift_Customs_GP1_Report.docx`** — the full GP1 project report.

## Live demo
With GitHub Pages enabled (**Settings → Pages → Deploy from branch → `main` / root**),
the prototype is served at:
`https://<your-username>.github.io/<repo-name>/`

## Features demonstrated
- Broker Admin / Staff sign-in (role-based)
- Dashboard with live summary metrics
- Client management (create & search)
- Customs declarations with **automatic duty + 16% sales-tax calculation**
- Invoice generation with a **JoFotara-authenticated QR code** (click to verify)
- Payment recording (invoice status updates to *Paid*)
- **Tariffs & tax-rate** configuration (HS codes)
- **Staff account** management
- **Company profile** & JoFotara integration settings
- **Audit log** that records actions live as you use the system
- Reports

## Tech (target build)
Oracle APEX · Oracle Database · PL/SQL · Oracle REST Data Services (ORDS) · JoFotara API

## Team
- **Osama Ibrahim** — Oracle APEX Developer & Database Designer
- **Abdalrahman Saeed** — Oracle APEX Developer & System Analyst

Supervised by **Dr. Hani Al-Bloush**.
