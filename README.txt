# GhostWriter ✍️
### Translate your situation into the language institutions understand — no lawyer needed.

---

## The Problem

A farmer in Telangana. A worker whose salary hasn't been paid. A tenant whose deposit was stolen.

They know they were wronged. But to fight back, they need to file RTI applications, consumer forum complaints, legal notices — documents that require formal legal language, specific formats, and knowledge of specific acts and deadlines.

They go to a lawyer. The lawyer charges ₹5,000–₹50,000. They can't afford it. So they give up.

**The powerful win by default — not because they're right, but because the powerless can't speak the language of institutions.**

This happens millions of times every day in India.

---

## What GhostWriter Does

The user opens the app and describes their problem in plain language — Telugu, Hindi, or English.

**Step 1 — Understand:** AI asks 3–4 simple clarifying questions (state, dates, amounts, proof).

**Step 2 — Identify:** AI identifies the correct legal pathway — which law applies, which forum to approach, filing fee, time limit.

**Step 3 — Generate:** AI produces a properly formatted legal document — RTI application, consumer forum complaint, legal notice, or labour court complaint — ready to print and submit.

No lawyer needed. No legal knowledge needed. Just describe what happened.

---

## Track

**Track 3 — Economic Empowerment & Education**

---

## How to Run

1. Download `index.html`
2. Open it in any browser
3. Enter your Anthropic API key (get one free at https://console.anthropic.com)
4. Describe your problem and generate your document

No installation. No backend. No dependencies.

---

## Tech Stack

- Pure HTML, CSS, JavaScript (single file)
- Claude API (claude-sonnet-4) via Anthropic
- No frameworks, no build tools

---

## Supported Document Types

- Consumer Forum Complaint (Consumer Protection Act 2019)
- RTI Application (Right to Information Act 2005)
- Legal Notice to landlord / employer
- Labour Court Complaint
- Government grievance letter

---

## Supported Languages

- English
- Telugu (తెలుగు)
- Hindi (हिन्दी)

---

## Ethical Considerations

**What we do:**
- Generate documents, not give legal advice — the distinction matters
- Built-in disclaimer directing users to DLSA for complex cases
- AI asks clarifying questions before generating — accuracy over speed
- User retains full control — they review and file the document themselves

**What we don't do:**
- Make decisions for users
- Store any personal data (no backend, no database)
- Replace lawyers for complex cases — we explicitly recommend professional help

**Who could be harmed:**
- Wrong document type generated → we mitigate by identifying pathway first
- Inaccurate legal sections cited → we recommend verification before filing
- Over-reliance on AI → disclaimer + DLSA referral built in

---

## Who We Built This For

First-generation litigants in India — people who have been wronged by landlords, employers, or government institutions but lack the money, language, or knowledge to fight back through formal channels.

---

## Demo Cases

1. Landlord refusing to return security deposit
2. Employer not paying salary for 2+ months
3. RTI application ignored past 30-day deadline
4. Wrong treatment at government hospital
5. Agricultural land acquired without fair compensation

---

## Team

Built at AIC x Anthropic Claude Hackathon — 24 hour sprint.
