# GhostWriter ✍️
### Translate your situation into the language institutions understand — no lawyer needed.
https://ghostwriter-nolawywer.netlify.app/
---

## The Problem

A farmer in Telangana. A worker whose salary hasn't been paid. A tenant whose deposit was stolen.

They know they were wronged. But to fight back, they need to file RTI applications, consumer forum complaints, legal notices — documents that require formal legal language, specific formats, and knowledge of specific acts and deadlines.

They go to a lawyer. The lawyer charges ₹5,000–₹50,000. They can't afford it. So they give up.

**The powerful win by default — not because they're right, but because the powerless can't speak the language of institutions.**

This happens millions of times every day in India.

---

## What GhostWriter Does

The user opens the app, enters their API key, and describes their problem in plain language — Telugu, Hindi, or English.

**Step 1 — Describe:** User describes their problem by typing or using the voice input feature.

**Step 2 — Clarify:** AI asks 3–4 simple clarifying questions (state, dates, amounts, proof available).

**Step 3 — Identify:** AI identifies the correct legal pathway — which law applies, which forum to approach, filing fee, time limit.

**Step 4 — Generate:** AI produces a properly formatted legal document — RTI application, consumer forum complaint, legal notice, or labour court complaint — ready to print and submit.

No lawyer needed. No legal knowledge needed. Just describe what happened.

---

## Features

### 🎤 Voice Input
Users can speak their problem instead of typing. Supports English, Telugu, and Hindi voice recognition. Powered by the browser's Web Speech API (works best on Chrome).

### ✏️ Editable Document
After the document is generated, users can switch to Edit Mode and directly modify any part of the document — fill in placeholders, correct details, or add missing information — without regenerating from scratch.

### 📍 Nearby Office Locator (GPS)
After document generation, users can click "Find Nearest Office" to share their location. GhostWriter uses AI and the user's GPS coordinates to identify the nearest Consumer Forum and District Legal Services Authority (DLSA) office, complete with address and a direct Google Maps link.

### 📬 Step-by-Step Submission Guidance
GhostWriter doesn't just generate the document — it tells users exactly what to do next:
1. Print the document and fill in placeholders
2. Gather supporting documents (receipts, agreements, photos)
3. Visit the nearest office or file online
4. Keep the acknowledgement receipt

### 🔗 Online Submission Portals
Direct links to government submission portals:
- **eDaakhil** (edaakhil.nic.in) — Consumer Forum online filing
- **CPGRAMS** (pgportal.gov.in) — Government grievance portal
- **RTI Online** (rti.india.gov.in) — RTI applications
- **NALSA** (nalsa.gov.in) — Free legal aid locator

### ⬇️ Download & Print
Users can download the document as a .txt file or print directly as a PDF — ready to walk into any government office.

---

## Disclaimer

GhostWriter generates legal documents to help citizens navigate the formal complaint system. **This is not legal advice.** The documents generated are templates based on the user's description and may require verification before filing.

For complex, high-stakes, or disputed matters, users are strongly advised to contact their nearest **District Legal Services Authority (DLSA)** for free legal aid, or consult a qualified lawyer.

GhostWriter does not store any user data. No personal information, problem descriptions, or generated documents are saved anywhere — everything runs locally in the browser.

---

## Track

**Track 3 — Economic Empowerment & Education**

---

## How to Run

1. Download `index.html`
2. Open it in any browser (Chrome recommended for voice input)
3. Enter your Anthropic API key (get one free at https://console.anthropic.com)
4. Describe your problem — by typing or speaking
5. Answer 3–4 clarifying questions
6. Get your document, edit it, find the nearest office, and submit

No installation. No backend. No dependencies. No data stored.

---

## Tech Stack

- Pure HTML, CSS, JavaScript (single file)
- Claude API (claude-sonnet-4) via Anthropic
- Web Speech API for voice input
- Browser Geolocation API for GPS office finder
- No frameworks, no build tools, no backend

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
- User retains full control — they review, edit, and file the document themselves
- No data stored — zero privacy risk

**What we don't do:**
- Make decisions for users
- Store any personal data (no backend, no database)
- Replace lawyers for complex cases — we explicitly recommend professional help when needed

**Potential risks and mitigations:**
- Wrong document type generated → we identify legal pathway first before generating
- Inaccurate legal sections cited → we recommend verification and provide DLSA referral
- Over-reliance on AI → disclaimer is prominent, professional help always recommended
- GPS data → location is only used in the moment to find offices, never stored

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

## AUTHORS
Masuna Vivekananda
Bhukya Sahithi
Built at AIC x Anthropic Claude Hackathon — 24 hour sprint.
