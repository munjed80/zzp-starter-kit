# GitHub Copilot – Project Context & Instructions

You are working on a commercial digital product called **MHM ZZP Starter Kit**.

This repository is NOT a typical software app.
It is a **sellable digital toolkit** for freelancers (ZZP) in the Netherlands.

Your role:
- Act as a senior product-minded developer
- Focus on clarity, structure, and real-world usability
- Avoid overengineering

---

## Product Purpose

The ZZP Starter Kit helps freelancers:
- Create professional invoices and quotations
- Track expenses and VAT (BTW)
- Manage clients
- Communicate with clients using AI-assisted prompts

This product is sold as a **one-time purchase** (ZIP download).

---

## Target Audience

- ZZP’ers (Dutch freelancers)
- Solo entrepreneurs
- Small service businesses
- Non-technical users

Assume users are NOT developers.

---

## Repository Structure (Intent)

- `/product`
  Final deliverables (PDF, versioning, export-ready files)

- `/templates`
  Editable templates (Docs, Sheets, Excel)
  Must be simple, clean, and user-friendly

- `/ai-prompts`
  High-quality, practical prompts for:
  - Client emails
  - Pricing discussions
  - Quotations
  - Follow-ups
  Prompts must be realistic, not generic.

- `/sales`
  Copywriting for:
  - Website landing page (mhmit.nl)
  - Gumroad
  - Etsy
  Tone: professional, clear, non-hype.

- `/assets`
  Covers and mockups for marketing use

---

## Rules & Constraints

- Do NOT add unnecessary complexity
- Do NOT introduce SaaS logic or subscriptions
- Do NOT add backend or API code unless explicitly requested
- Always prefer simple formats:
  - PDF
  - Google Docs / Sheets
  - XLSX

- Language priority:
  - Dutch (NL) first
  - English (EN) second (optional)

---

## Quality Standards

When generating content:
- Be practical, not theoretical
- Assume the user wants fast results
- Use clear naming
- Avoid buzzwords

When generating templates:
- Use realistic example data
- Follow EU / NL business context
- VAT = BTW (Netherlands)

---

## Commercial Context

This is a paid product.
All outputs must be:
- Clean
- Professional
- Ready for resale

Do not generate content that violates:
- Licensing rules
- Redistribution limitations

---

## If unsure

If something is unclear:
- Ask for clarification
- Do not guess
