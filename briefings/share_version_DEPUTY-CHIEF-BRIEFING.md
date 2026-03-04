# What's Behind the Cameras: A Technical Briefing on Flock Safety
From **[REDACTED]** | **[REDACTED]** Resident | **[REDACTED]**

**[REDACTED]**, thank you for the conversation **[REDACTED]** and for being open to additional information. I appreciate your directness, and I want to return that — this document is focused on the vendor's technology and business practices, not on **[REDACTED]** PD's operations or intentions. I believe the cameras have legitimate investigative value. The question is whether the vendor behind them has earned the level of trust that comes with that access.

You mentioned two things I want to address head-on:
1. **"We have a 30-day retention policy."**
2. **"The cameras only take pictures of the back of the car — license plate, no passengers."**

Both may be true for how **[REDACTED]** uses the system today. What follows is what the vendor's platform, contract, and security posture look like from the other side.

---

## 1. "30-Day Retention" — What the Contract Actually Says

**[REDACTED]** PD may have a 30-day retention setting enabled in the Flock dashboard. But the contract terms tell a different story.

On February 16, 2026, Flock rewrote its Terms and Conditions — **147 changes** in a single revision. Among the most significant:

| What Changed | What It Means |
|---|---|
| **Deleted:** "Flock does not own and shall not sell Customer Data" | There is no longer a contractual prohibition on Flock selling the data your cameras collect |
| **Deleted:** Entire Section 4.3 (Training Data guardrails) | Previously required removing personal details, separate storage, limited use, and "never sold or shared with third parties." All deleted. |
| Added: "Perpetual, irrevocable, worldwide, royalty-free" license | Flock retains the right to use all data your cameras ever captured — even after **[REDACTED]** terminates the contract. This license cannot be revoked. |
| **Added:** License to "support and improve Flock's products and services" | Previously limited to providing services during the contract. Now open-ended — product improvement, AI training, anything Flock defines as "support and improve." |
| **Added:** Liability cap regardless of fault | Even if Flock is grossly negligent, liability is capped at 12 months of fees |
| **Added:** Forced arbitration in Georgia | Disputes no longer governed by Texas law — moved to Flock's home state |
| **Added:** Restricted exit | Budget-based cancellation (called "non-appropriation") can no longer be "based on discretionary budget decisions" — narrows the city's ability to walk away |

The bottom line: Your 30-day retention setting controls when **[REDACTED]** PD can *search* the data. It does not control what Flock does with the data on their end. Under the current contract language, Flock has a perpetual license to that data regardless of your retention setting.

**Source:** haveibeenflocked.com/news/terms-feb2026 (clause-by-clause comparison)

---

## 2. "Only Pictures of the Back of the Car" — What the Platform Actually Is

The cameras **[REDACTED]** operates today may only capture rear plates. But the Flock platform those cameras feed into is significantly more than a plate reader:

### What's Live Now (Available to All Flock Customers)

| Product | What It Does |
|---|---|
| **Vehicle Fingerprint** | Searches by make, model, color, body type, bumper stickers, roof racks, damage — no plate number needed |
| **FreeForm** | AI-powered plain-English search. Flock's own product page shows searching for people by physical description — not vehicles, *people*. |
| **FlockOS** | Unified operating system tying plate readers + video + audio + AI into a single searchable platform |
| **National Lookup** | Cross-jurisdiction search. 75% of Flock law enforcement customers are enrolled. 5,000+ agencies can search across each other's camera data. |

### What's Deployed Elsewhere (Not Yet in **[REDACTED]**, But Part of the Platform)

| Product | What It Does | Why It Matters |
|---|---|---|
| **Flock video cameras** | Full video surveillance, not just plate capture | Same platform, same data system, same contract |
| **Raven** | Sold for gunshot detection. Now detects "human voices in distress." (Electronic Frontier Foundation, Oct 2025) | Microphones listening for speech — potential felony under TX Penal Code § 16.02 |
| **Condor cameras** | Pan, tilt, zoom — full-motion video surveillance | Security researcher found these on the open internet without passwords |

### What the Patent Describes

**US Patent US11416545B1** (filed 2022) describes a system for classifying people by:
- Male / female
- Race
- Height and weight
- Clothing

This data is stored in a searchable database. Whether this capability is active today is unknown. That it is *designed and patented* is a fact.

### How Features Get Added

This is the key point: software updates expand capability without new hardware. No new cameras need to be installed. No city council hearing is required. No vote is taken. Flock pushes an update, and the platform gains new features. The question is whether **[REDACTED]** has any contractual or policy mechanism to control that — and if it does, it has not been made public.

---

## 3. The Security Problem — What May Not Be in the Sales Pitch

Security researcher **Jon Gaines** is a Principal Security Researcher at Contrast Security with 10+ years in offensive security and 50+ confirmed security vulnerabilities disclosed. He presented at DEFCON (the world's largest security conference). He published his Flock findings through a formal reporting process with the federal agencies that catalog security flaws.

His research report documents **51 findings, 22 confirmed CVEs** in the National Vulnerability Database:

### The Highlights

| Finding | CVE | Severity |
|---|---|---|
| No password needed for full remote camera control | CVE-2025-59403 | Critical |
| Camera broadcasts Wi-Fi password in plain text | CVE-2025-59409 | Critical |
| Security key stored with guessable password | CVE-2025-59407 | High |
| Physical button sequence creates Wi-Fi hotspot — full access in 30 seconds | CVE-2025-47822 | High |
| Cameras run Android 8, no longer supported or updated since 2021 — no patches available | — | Critical |
| Built-in Wi-Fi password that can't be changed: "security" (shared across devices) | — | Critical |
| Maintenance access left turned on in live devices | — | High |
| Images stored on device without encryption (no scrambling to protect data if the device is accessed) | — | High |
| Police portal does not require multi-factor authentication (a second verification step, like a code texted to your phone) | — | High |

### What This Means Operationally

- Any camera **[REDACTED]** has deployed can be compromised in 30 seconds by someone who walks up to it, presses a button sequence, and connects to the default Wi-Fi hotspot. Full device control.
- **Condor (PTZ) cameras were found on the open internet** without passwords — live footage viewable by anyone, anywhere. 404 Media documented 60+ cameras streaming without authentication, including footage of children on a playground.
- **35+ Flock customer accounts** had passwords stolen. The police portal does not require multi-factor authentication (a second login step) — the same basic protection required for a personal Gmail account.
- **The cameras run Android 8**, which stopped receiving updates in 2021. There are no security patches. The operating system itself is permanently vulnerable.

### Independent Verification

This is not one person's opinion. The findings have been independently corroborated by:

- **National Vulnerability Database** (nvd.nist.gov) — 22 CVEs formally cataloged
- **9News (NBC Denver)** — "Researchers claim Flock cameras are easy to hack"
- **404 Media** — 60+ cameras streaming live without authentication
- **The Security Ledger** — cybersecurity trade publication deep-dive
- **Electronic Frontier Foundation** — year-in-review of Flock security/surveillance failures
- **Senator Wyden / Rep. Krishnamoorthi** — formal letter asking the Federal Trade Commission to investigate Flock for cybersecurity failures (Nov 2025)

### Flock's Response

Flock acknowledged the findings and claims exploitation requires "physical access and intimate knowledge of hardware." The 30-second button-press exploit requires neither intimate knowledge nor special tools — Gaines demonstrated it on video. The "physical access only" defense is also undermined by the 60+ cameras found accessible remotely without any authentication.

### The Video

A 40-minute investigative video demonstrates these vulnerabilities step by step: **youtube.com/watch?v=uB0gr7Fh6lY**. The presenter (Benn Jordan, 953K subscribers) collaborates directly with Gaines. The technical findings are independently verified by the sources listed above.

**Formal research report:** github.com/GainSec/anti-crime-ecosystem-research

---

## 4. Data Sharing — What Happens Behind the Dashboard

You may have full control over what **[REDACTED]** PD *searches for*. You may not have full control over where **[REDACTED]**'s data *goes*.

**Mountain View, CA (Jan 2026):** Flock enabled a "nationwide" sharing setting without the police department's knowledge. ATF, the Air Force, and a federal inspector general all accessed local data for 17 months. Flock could not produce records of what was shared. The police chief recommended termination.

**Washington State (Oct 2025):** Border Patrol accessed Flock data from 10 police departments that never agreed to share. The ACLU documented that the standard Flock contract grants a "worldwide, perpetual, royalty-free" license to disclose data — even when departments opt to restrict sharing in the system settings.

**Illinois (Aug 2025):** Secretary of State audit found over 4,000 immigration-related lookups on the state's plate reader network, with search terms like "ICE+ERO" (Immigration and Customs Enforcement — Enforcement and Removal Operations) and "ICE WARRANT."

The question: Is **[REDACTED]** enrolled in Flock's National Lookup network? If so, which agencies can search **[REDACTED]**'s data? Has anyone from **[REDACTED]** PD reviewed who has access? Mountain View's police department didn't know — and they had safeguards and audits too.

---

## 5. What I'd Recommend — From One Tech Professional to Another

I'm not a police officer, and I respect that you know your operational needs better than I do. But from a technology and vendor management perspective, here's what I'd flag:

| # | Recommendation | Rationale |
|---|---|---|
| 1 | Verify your contract terms against the Feb 2026 rewrite | 147 changes were made. Does **[REDACTED]**'s contract include the perpetual data license? The forced Georgia arbitration? The deleted data ownership clause? |
| 2 | Confirm whether **[REDACTED]** is in the National Lookup network | If so, determine which agencies can search your data — and whether that was a deliberate decision or a default setting |
| 3 | **Request Flock's formal response to the GainSec findings** | Ask specifically what has been fixed, what the fix timeline is, and whether your deployed cameras still run Android 8 |
| 4 | **Require multi-factor authentication on all Flock portal accounts** | 35+ accounts compromised. This is a standard security practice. |
| 5 | **Adopt a written plate reader policy** | Austin, Texarkana, Universal City, and Galveston have one. It protects the department as much as the public — it documents that you're operating with controls. |
| 6 | **Prohibit audio sensors without council authorization** | Raven's "human voice" detection is a potential felony under TX Penal Code § 16.02. This protects the department from legal exposure. |
| 7 | **Request a contract clause preventing vendor setting changes without written authorization** | Mountain View's experience proves this is necessary — Flock changed their sharing settings without telling the police department. |

---

## Sources

| Source | Where to Find It |
|---|---|
| GainSec research report | github.com/GainSec/anti-crime-ecosystem-research |
| Jon Gaines credentials | gainsec.com/whoami |
| CVE-2025-59403 | nvd.nist.gov/vuln/detail/CVE-2025-59403 |
| Flock patent US11416545B1 | patents.google.com/patent/US11416545B1 |
| Flock Feb 2026 contract changes | haveibeenflocked.com/news/terms-feb2026 |
| Flock's current terms (live) | flocksafety.com/legal/terms-and-conditions |
| Flock's official security response | flocksafety.com/blog/response-to-compiled-security-research-on-flock-safety-devices |
| ACLU data sharing report | aclu.org/news/privacy-technology/flock-massachusetts-and-updates |
| Mountain View statement | mountainview.gov — News, Jan 30, 2026 |
| 9News — hack demonstration | 9news.com |
| 404 Media — 60+ cameras exposed | 404media.co |
| EFF — Flock abuses 2025 review | eff.org — Dec 2025 |
| Video demonstration | youtube.com/watch?v=uB0gr7Fh6lY |

---

*Every claim in this document is sourced from the National Vulnerability Database, government audits, court filings, the vendor's own documents, or named investigative reporting. I welcome verification and am happy to discuss any of this further.*

Prepared by **[REDACTED]** | **[REDACTED]** Resident | February 2026
