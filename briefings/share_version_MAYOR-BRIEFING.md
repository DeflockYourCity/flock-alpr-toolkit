# Flock Safety Plate Reader Cameras: Follow-Up Briefing for **[REDACTED]**
From **[REDACTED]** | **[REDACTED]** Resident | **[REDACTED]**

**[REDACTED]**, thank you for your time **[REDACTED]** and for asking me to send additional information. I believe the cameras have legitimate investigative value. The question is whether the vendor behind them has earned the level of trust that comes with that access. Below is the expanded version of what I presented, along with supporting evidence and sources you can verify independently.

---

## What I Said Last Night (Expanded)

### The System Behind the Cameras

On **[REDACTED]**, **[REDACTED]** told the council that officers "only have access to still images of vehicle license plates, not vehicle occupants." That may describe how **[REDACTED]** uses the system today. It does not describe what Flock sells or what their platform is designed to do.

Flock is not a camera company. It is a **surveillance platform company** that happens to use cameras as a data collection point. Here is what the platform includes:

| Product | What It Does |
|---|---|
| **Plate readers** | Photograph every passing vehicle — plate, make, model, color, bumper stickers, damage — and store it in a searchable database |
| **Vehicle Fingerprint** | Search by vehicle characteristics without a plate number |
| **FreeForm** | AI-powered plain-English search across all data. Flock's own product page shows searching for people by physical description. |
| **FlockOS** | A unified operating system tying plate readers + video + audio + AI search into a single platform |
| **Raven** | Sold for gunshot detection. Now detects "human voices in distress" — microphones that listen for speech (Electronic Frontier Foundation, Oct 2025) |
| **National Lookup** | A cross-jurisdiction search network. 75% of Flock's law enforcement customers are enrolled. 5,000+ agencies can search each other's data. |
| **Patent US11416545B1** | Flock's own patent describes classifying people by race, gender, height, weight, and clothing — stored in a searchable database |

The question is not what **[REDACTED]** uses today. It is what the platform is designed to enable — and who controls the transition from one capability to the next. Software updates add features without new hardware, without public hearings, and without a council vote.

---

### Documented Loss of Local Control

These are not allegations. They are official government statements:

**Mountain View, CA (Jan 2026)** — Flock enabled a "nationwide" sharing setting without the police department's knowledge. The Bureau of Alcohol, Tobacco and Firearms, the Air Force, and a federal inspector general all accessed local Mountain View data for 17 months. Flock could not produce records of what was shared. The police chief recommended termination. The system was shut down February 2, 2026.

**Cambridge, MA (Dec 2025)** — Flock installed two new cameras after the city council voted to deactivate the system. The City Manager called it a "breach of trust and the agreement." Contract terminated.

**Washington State (Oct 2025)** — Border Patrol accessed Flock data from 10 police departments that never agreed to share their data. The sharing happened through Flock's network design, not departmental consent.

**Illinois (Aug 2025)** — Secretary of State audit found Customs and Border Protection accessed plate reader data in violation of state law. Over 4,000 immigration-related lookups were found nationwide, with search terms like "immigration," "ICE+ERO" (Immigration and Customs Enforcement — Enforcement and Removal Operations), and "ICE WARRANT."

**ACLU (Oct 2025)** — Documented that Flock's standard contract grants a "worldwide, perpetual, royalty-free" license to share data — and that even when departments opt to restrict sharing in system settings, the contract language may still authorize disclosure.

---

### The Contract: What Changed in February 2026

On February 16, 2026, Flock published a rewritten Terms and Conditions. An independent analysis (haveibeenflocked.com) documented **147 total changes**: 96 replacements, 21 insertions, and 30 deletions. The document grew from 12 to 15 pages. Key changes:

| What Changed | Before | After |
|---|---|---|
| **Data ownership** | "Flock does not own and shall not sell Customer Data" | **Clause deleted entirely** |
| **Training data guardrails** | Section 4.3 required removing personal details, separate storage, limited to a "small fraction of images," and "never sold or shared with third parties" | **Entire section deleted** |
| **Data license** | License limited to providing services during the contract term | **"Perpetual, irrevocable, worldwide, royalty-free"** license to use data to "support and improve Flock's products and services" — survives contract termination |
| **Liability for negligence** | Liability caps did not apply to gross negligence or willful misconduct | **Liability capped at 12 months of fees regardless of fault** — including gross negligence |
| **Dispute resolution** | Governed by customer's state law | **Forced arbitration in Georgia** — Flock's home state |
| **Exit rights** | Government customers could terminate via budget-based cancellation (non-appropriation) "without penalty" with 30 days' notice | Added restriction: budget-based cancellation (non-appropriation) "shall not be based on discretionary budget decisions." **Narrows the exit to genuine defunding scenarios only.** |
| **Where terms are hosted** | — | On Flock's own website, where they can change them at will. **Flock blocks internet archiving services (Wayback Machine)**, making it difficult to track changes over time. |

What this means practically: If **[REDACTED]** signs a contract under these terms, Flock retains a perpetual, irrevocable right to use all data **[REDACTED]**'s cameras ever collected — even after **[REDACTED]** terminates the contract. There is no longer a contractual prohibition on selling that data. The city cannot revoke this license once granted.

**Source:** haveibeenflocked.com/news/terms-feb2026 (detailed clause-by-clause comparison)

---

### Hackable — Documented and Confirmed

Security researcher **Jon Gaines** (GainSec) published a formal research report documenting **51 security findings, including 22 confirmed vulnerabilities** now cataloged in the National Vulnerability Database — the same federal system used to track security flaws in government infrastructure.

Gaines is not a YouTuber or activist. He is a **Principal Security Researcher at Contrast Security** with over 10 years in offensive security, 50+ confirmed security vulnerabilities disclosed across his career, and has presented at DEFCON (the world's largest security conference). His findings were published through a formal reporting process with the federal agencies that catalog security flaws.

| What He Found | What It Means |
|---|---|
| Cameras run Android 8 (no longer supported or updated since 2021) | No security patches available — permanently vulnerable |
| A physical button sequence creates a Wi-Fi hotspot | Press a button, connect, full control in **30 seconds** |
| Built-in Wi-Fi password that can't be changed ("security") | Shared across devices — one password works on all |
| Condor cameras (pan/tilt/zoom) found on the open internet | **No password required.** Live footage viewable by anyone. |
| Images stored without encryption (no scrambling to protect data if the device is accessed) | Data on the device is unprotected |
| Maintenance access left turned on | Full remote control of the device possible over Wi-Fi |
| Police portal lacks mandatory multi-factor authentication (requiring a second verification step, like a code texted to your phone) | 35+ customer accounts had passwords stolen |

**Independent corroboration:**

- **9News (NBC Denver):** "Researchers claim Flock cameras are easy to hack" — 9news.com
- **404 Media:** Found 60+ Flock cameras streaming live without authentication, including footage of children on a playground
- **Electronic Frontier Foundation:** Year-in-review documenting Flock surveillance abuses — eff.org
- **The Security Ledger:** Cybersecurity trade publication deep-dive — securityledger.com
- **Senator Wyden / Rep. Krishnamoorthi:** Asked the Federal Trade Commission to investigate Flock for cybersecurity failures (Nov 2025)

**Video demonstration:** A 40-minute investigative video by Benn Jordan (953K YouTube subscribers) shows Gaines' findings being demonstrated on camera — step by step, reproducible. The underlying research has been independently verified by NBC, EFF, and cybersecurity trade press. Available at: youtube.com/watch?v=uB0gr7Fh6lY

**Flock's response:** Flock published a blog post acknowledging the findings were "previously disclosed" and "under review by MITRE." They claim exploitation requires physical access. This defense is undermined by the 404 Media finding that 60+ cameras were already accessible remotely without authentication.

**Formal research report:** github.com/GainSec/anti-crime-ecosystem-research

---

### The Law

**No Texas state law requires a written plate reader policy.** Multiple bills have been introduced by Republican legislators — SB 78 (2019), HB 3999 (2023), HB 961 (2025), HB 1607 (2025) — and all died in committee. That means there are **zero state-level guardrails.** Everything depends on what the city chooses to require.

Austin, Texarkana, Universal City, and Galveston adopted written plate reader policies voluntarily. **[REDACTED]** has not.

**Texas Penal Code § 16.02** makes intercepting oral communications without consent a **second-degree felony** (2-20 years). Raven microphones listening for "human voices in distress" — without the consent of anyone being recorded — may trigger this statute.

**Texas Department of Public Safety (DPS)** issued Flock a cease-and-desist in July 2024 after determining the company operated **without a required license for five years** (2019-2024). The license was reinstated November 2024 and expires September 2026.

**Carpenter v. United States (2018):** The Supreme Court held that automated location tracking is a Fourth Amendment concern. No higher court has ruled on plate readers specifically — the legal question is open. If a court extends Carpenter to plate readers, prosecutions built on warrantless Flock searches could be challenged.

---

### Cities That Reversed Course

| City/County | State | Action |
|---|---|---|
| **Austin** | **TX** | Contract ended, Jun 2025 |
| **Hays County** | **TX** | All Flock contracts ended |
| **San Marcos** | **TX** | Council declined renewal |
| **Denver** | CO | Ending Flock contract, Feb 2026 |
| Mountain View | CA | System shut down, Feb 2026 |
| Cambridge | MA | Terminated for "breach of trust," Dec 2025 |
| Eugene | OR | 57 cameras disabled |
| Evanston | IL | 19 cameras deactivated |
| **30+ cities** | Nationwide | Cancelled since Jan 2025 (NPR, Feb 17, 2026) |
| **Amazon/Ring** | — | **Killed Flock partnership, Feb 12, 2026** |

---

## What I'm Asking For

I am not asking **[REDACTED]** to remove the three cameras it has. I am asking the council to pause the expansion until governance controls are in place:

| # | Action | Why |
|---|---|---|
| 1 | Adopt a written plate reader policy | Austin, Texarkana, Universal City, and Galveston have one. **[REDACTED]** does not. |
| 2 | **Cap retention at 30 days by ordinance** | Flock's terms allow up to 1 year without a local cap |
| 3 | No sharing beyond **[REDACTED]** PD without a council vote | 75% of Flock customers are in the National Lookup network. Unknown if **[REDACTED]** is. |
| 4 | **Ban audio sensors in public right-of-way** | Texas felony risk under § 16.02 |
| 5 | **Independent security assessment** | 22 confirmed vulnerabilities. FTC investigation requested. |
| 6 | **No vendor setting changes without written city authorization** | Mountain View proves this is necessary |
| 7 | **Quarterly public audit reports** | Searches, reasons, agencies queried, match rates |
| 8 | **No new features activated without council vote** | Prevents silent AI/audio/video capability upgrades |
| 9 | **Review contract terms before any expansion** | The Feb 2026 rewrite deleted data ownership protections and added forced Georgia arbitration |

---

## Verify Everything

Every claim in this document can be independently verified:

| Source | Where to Find It |
|---|---|
| GainSec research report (51 findings, 22 CVEs) | github.com/GainSec/anti-crime-ecosystem-research |
| CVE-2025-59403 (remote takeover, no password) | nvd.nist.gov/vuln/detail/CVE-2025-59403 |
| Flock patent US11416545B1 | patents.google.com/patent/US11416545B1 |
| Flock Feb 2026 contract analysis (147 changes) | haveibeenflocked.com/news/terms-feb2026 |
| ACLU — "Flock Can Share Data Even When Opted Out" | aclu.org/news/privacy-technology/flock-massachusetts-and-updates |
| Mountain View official statement | mountainview.gov — News, Jan 30, 2026 |
| Illinois Secretary of State audit | ilsos.gov — Press releases, Aug 25, 2025 |
| Wyden/Krishnamoorthi FTC letter | wyden.senate.gov — Nov 3, 2025 |
| Electronic Frontier Foundation — Raven voice detection | eff.org — Oct 2, 2025 |
| Electronic Frontier Foundation — 2025 Flock abuses review | eff.org — Dec 2025 |
| NPR — 30+ cities cancelling | npr.org — Feb 17, 2026 |
| Denver ending Flock contract | denverpost.com — **[REDACTED]**, 2026 |
| 9News — "Researchers claim Flock cameras easy to hack" | 9news.com |
| 404 Media — 60+ cameras streaming without authentication | 404media.co |
| TX proposed plate reader bills (all died in committee) | capitol.texas.gov |
| Carpenter v. United States (2018) | supreme.justia.com/cases/federal/us/585/296 |
| Video demonstration of vulnerabilities | youtube.com/watch?v=uB0gr7Fh6lY |
| Flock Safety's official response | flocksafety.com/blog/response-to-compiled-security-research-on-flock-safety-devices |

---

*No anonymous sources. No speculation. Every claim is sourced from a government audit, court filing, official statement, the federal cybersecurity database, vendor documents, patent filings, or named investigative reporting. I welcome verification of any point.*

Prepared by **[REDACTED]** | **[REDACTED]** Resident | February 2026
