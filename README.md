# Online Scam Checker — Paste a Suspicious Job Offer or Message, Get a Red-Flag Verdict

"Congratulations, you've been selected!" — for a job you never applied to, paying $850 a week, starting as soon as you pay a small fee in gift cards. This free **online scam checker** analyzes suspicious job offers, DMs, emails and "opportunities" for the persuasion patterns scammers reuse everywhere: **urgency, upfront fees, gift-card or crypto payment, too-good pay, no-interview hiring, off-platform moves, and requests for banking details or ID**. Every matched red flag is explained in plain language, and the message gets a risk score and verdict — all computed **100% in your browser**; the pasted text never leaves your device.

**Live Demo:** https://anaskhan0009.github.io/online-scam-checker/

## Features

- **12-pattern heuristic engine** — weighted red flags (upfront fee +18, gift cards +18, bank-detail requests +16, fake-cheque pattern +16, crypto payment +14, impossible pay +14, urgency +12, off-platform push +12…) combined into a 0–98 risk score
- **Clear verdicts** — LIKELY SCAM / SUSPICIOUS / SOME RED FLAGS / NO KNOWN RED FLAGS, each with the right next action (block & report, verify independently, proceed with verification anyway)
- **Every flag explained** — not just a score: why gift cards are untraceable cash, why "no interview" means there is no job, why moving to WhatsApp removes your safety net
- **Saved scan history (full CRUD)** — save scans with your own labels and notes; edit labels/notes anytime; delete; build a personal pattern library of the scams aimed at you
- **Sample scam built in** — one tap fills a realistic fake offer so you can see the engine catch it
- **Free local account system** — sign up / log in (salted SHA-256 hashed passwords, browser-only), guest mode, JSON export/import

## How to Use

1. Open the [live demo](https://anaskhan0009.github.io/online-scam-checker/) (or `index.html` locally).
2. Paste the complete suspicious text — details matter; scammers hide hooks in the middle.
3. Read the verdict and every red flag. If it's a scam: don't reply, don't pay, report it on the platform where it arrived, and block.
4. Log in and save the scan with a label and what you did — your future self will thank you when the same script returns wearing a new logo.

## Why a Checker, Not Just Instinct?

Scam scripts are industrial products, A/B-tested on millions of people. They don't need to fool you completely — just enough, once, while you're tired or hopeful. A boring checklist of known patterns never gets tired and never gets hopeful. That said, no analyzer is proof: a clean score means "no known patterns matched", and independent verification through official channels is always the final step.

## Ethical Use

This is a **defensive analysis tool** for messages *you received*. Analysis runs entirely client-side; pasted text is never transmitted or stored anywhere except your own saved history on your own device.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript (heuristic pattern engine), WebCrypto (SHA-256 password hashing), localStorage persistence.

---

Built by **Dinal Studios** — free cyber security tools and web apps.
GitHub: https://github.com/anaskhan0009

*Keywords: scam checker, is this job a scam, fake job offer checker, work from home scams, telegram job scam, whatsapp job scam, upfront fee scam, gift card scam, online fraud detection*
