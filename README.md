# Dealership IT Security & AI Training

**A ready-to-run security awareness and responsible-AI training program built for car dealerships**, with New York, New Jersey and federal rules built in.

Seven short animated videos (about 42 minutes total) walk every department through the threats dealerships actually face: fake lender emails, gift-card texts from the "GM", changed payoff wire instructions, shared DMS logins, ransomware, and staff pasting credit details into free chatbots. This repo holds the facilitator guide, the quiz answer key, the legal reference table and a sign-off template so another dealership group can run the same program.

> I created this program as IT Manager for a dealership group with stores across New York and New Jersey. Everything here is generic: the characters, lender and scenarios are invented, and no real company, employee or customer appears in it.

---

## Why dealerships need their own training

Generic security training talks about "the finance team" and "a vendor invoice". Dealership staff deal with credit applications, deal jackets, lender portals, payoff wires, DMS logins and trade-ins with customer phones still paired to the infotainment system. Dealers that arrange financing are also financial institutions under the **FTC Safeguards Rule**, which expects documented security awareness training. The 2024 CDK Global ransomware attack showed how quickly a single incident can stop every store in a group.

## The modules

| # | Module | Example scenarios | Key takeaways |
|---|---|---|---|
| 1 | Don't Take the Bait | Fake lender portal email (Sales); gift-card text from the "GM" (Service); changed payoff wire instructions (Accounting); fake DMS support call asking for an MFA code (F&I) | Five red flags; verify through a known number; two-person approval for wires; report to IT, no blame |
| 2 | Lock It Down | Shared sales-desk login on a sticky note; MFA fatigue push spam at 11 PM; unlocked screen in the showroom | 14+ character passphrases; never share logins or codes; deny unexpected MFA prompts; Win+L; no found USB drives |
| 3 | Protect the Deal Jacket | Credit app contents; license photo texted from a personal phone; customer asks to delete their data | What counts as protected info; clean desk and shredding; reset infotainment on trade-ins; route privacy requests to management |
| 4 | Code Red | CDK Global ransomware (June 2024); ransom note on a PC | Disconnect, don't power off, call IT; NY, NJ and FTC breach notice clocks; no social media or outside talk |
| 5 | AI: Smart & Safe | Credit details pasted into a free chatbot; AI invents a warranty and rebate; AI voice clone of the GM requests a wire | Approved tools only; no customer data in unapproved AI; verify outputs; no fake reviews |
| 6 | AI & the Law | Personalized website pricing; AI spokesperson in a social ad; AI voice bots; AI hiring tools; F&I fairness | NY algorithmic pricing and synthetic performer disclosures; deepfake laws; TCPA and AI voices; AI hiring bias rules; ECOA |
| 7 | Federal Rules of the Road | ID and credit app that don't match; credit pull on a relative "just to see"; deceptive email subject line; promo texts | Red Flags Rule; FCRA permissible purpose; CAN-SPAM; TCPA consent, STOP opt-outs and calling hours |

There is also a standalone **AI Compliance Masterclass** (14:45) that combines Modules 5–7 for AI-focused assignments.

## How the videos are made

- **Format:** narrated MP4s, 4:53 to 7:03 each, with Pixar-inspired 3D-look animation set in a dealership showroom.
- **Cast:** Byte, a wisecracking cyber-safety mascot car, narrates with car puns. Sam (Sales), Joe (F&I), Rosa (Service), Mike (Accounting), Tony (GM) and Anthony (Marketing) act out each scenario.
- **Built-in quizzes:** every video ends with 2–3 on-screen questions, pauses 3 seconds, then reveals the answer.
- **Accessibility:** each video has a matching `.srt` caption file for screen readers and LMS upload.
- **Built with AI:** scripts, legal research, narration and animation were produced with AI tools (including Claude) and reviewed by a human before rollout.

## What's in this repo

| File | What it is |
|---|---|
| [facilitator-guide.md](facilitator-guide.md) | Rollout plan, audience, module details and the checklist to customize before launch |
| [quiz-answer-key.md](quiz-answer-key.md) | Every on-screen quiz question with its answer |
| [legal-references.md](legal-references.md) | Federal, New York and New Jersey laws the videos cite, with what each video says |
| [acknowledgment-form.md](acknowledgment-form.md) | A one-page employee sign-off template for your training records |

## Run it at your dealership

1. Have counsel review [legal-references.md](legal-references.md).
2. Upload the videos and captions to your LMS, SharePoint or a shared drive.
3. Assign Modules 1–4 (security) in week 1 and Modules 5–7 (AI and federal rules) in week 2.
4. Collect a signed [acknowledgment](acknowledgment-form.md) from each employee.
5. Repeat every year, and refresh Module 6 whenever state AI laws change.

## Disclaimer

This is training content, not legal advice. Laws are cited as of September 2026 and change often; check them with your own counsel before use.

## License

Text in this repo is licensed under [CC BY 4.0](LICENSE). You can use and adapt it with credit.

## About me

I'm Michael Riveira, IT Manager for a dealership group across New York and New Jersey. I focus on IT automation, dealership technology, AI tools and agentic workflows. See also my [Dealership IT Dashboard](https://github.com/MikeRiveira/dealership-it-dashboard). [Connect on LinkedIn](https://www.linkedin.com/in/michael-riveira-874a06178/).
