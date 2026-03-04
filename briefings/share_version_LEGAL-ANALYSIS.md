# Legal Analysis: Laws Implicated by Flock Safety Plate Reader Technology
## Prepared for **[REDACTED]** City Council Presentation — **[REDACTED]**

> **Note:** Every statute, case, and legal finding below is drawn from published legal sources, court opinions, government records, or official legislative text. No speculation. Where the law is unsettled, that is stated explicitly.

> The agenda includes Consent Item **[REDACTED]**: Council is placing on file the **[REDACTED]** PD 2025 Racial Profiling Analysis. Flock's own patent (US11416545B1) describes classifying people by race, gender, height, and weight. The legal questions in this document — particularly regarding the patent's profiling system, Fourth Amendment protections, and Texas constitutional privacy guarantees — should be evaluated alongside the profiling standards the council is reviewing tonight.

---

## 1. WHAT REQUIRES A WARRANT (AND WHAT CURRENTLY DOES NOT)

### The Core Constitutional Question: Is Plate Reader Data Collection a "Search"?

**Current legal status: Unsettled, trending toward warrant requirements.**

| Court / Body | Ruling | Date | Implication |
|---|---|---|---|
| **U.S. Supreme Court — *Carpenter v. United States*, 585 U.S. 296** | Government acquisition of historical cell tower location data is a Fourth Amendment **search requiring a warrant**. Chief Justice Roberts: *"A person does not surrender all Fourth Amendment protection by venturing into the public sphere."* | 2018 | Carpenter's logic about comprehensive, automated location tracking applies directly to plate reader networks. No Supreme Court ruling specifically on plate readers yet. |
| **Norfolk Circuit Court — *Commonwealth v. Church*** | **Threw out** plate reader evidence, finding plate reader tracking invades reasonable expectation of privacy: *"Prolonged tracking of public movements with surveillance serves to invade the reasonable expectation citizens possess in their entire movements and thus requires a warrant."* | June 2024 | First Virginia trial court to require a warrant for plate reader data. |
| **Virginia Court of Appeals — *Commonwealth v. Church*** | **Reversed** the lower court. Held that plate reader cameras simply take pictures of plates on public roads and **no warrant is required**. | Oct 14, 2025 | The Electronic Frontier Foundation, ACLU of Virginia, and the National Association of Criminal Defense Lawyers filed legal briefs urging a warrant requirement. Case may be appealed to Virginia Supreme Court. |
| **U.S. District Court, E.D. Virginia — Norfolk plate reader lawsuit** | Ruled without trial **for the city**. Rejected Fourth Amendment challenge to warrantless plate readers. | Jan 2026 | Federal trial court level; not a ruling other courts must follow. |
| **ACLU/Electronic Frontier Foundation — *San Jose plate reader lawsuit*** | Challenges San Jose's warrantless plate reader mass surveillance under the Fourth Amendment. | Filed 2025 | Pending. Could produce significant precedent. |
| **Congressional Research Service (IF13068)** | *"No federal appeals court has decided whether law enforcement queries of plate reader databases amount to a Fourth Amendment search."* | Jul 2025 | The question is legally **open** at the federal appeals level. |

### What This Means for **[REDACTED]**

- **Currently:** Most courts have not required warrants for plate reader data access. Police can typically query the Flock system without a warrant.
- **The trend:** Courts are beginning to hear challenges. Trial courts have split. No federal appeals court has ruled definitively. The legal landscape is shifting.
- The risk: If a court eventually holds that comprehensive plate reader tracking requires a warrant (following Carpenter's logic), evidence collected without warrants could be thrown out. **[REDACTED]** could see prosecutions built on warrantless Flock searches overturned.
- The governance question: Even where a warrant is not currently *required*, nothing prevents **[REDACTED]** from *choosing* to require warrant-level justification as a policy matter. This is a governance choice, not a legal limitation.

---

## 2. TEXAS STATE LAWS IMPLICATED

### A. Texas Has No State Law Governing Plate Readers — And That Is the Problem

**Texas currently has no enacted state statute requiring a written plate reader policy, setting retention limits, or restricting data sharing.** Multiple bills have been introduced — all by Republican legislators — and none have passed:

| Bill | Sponsor | What It Would Have Required | Result |
|---|---|---|---|
| **SB 78** (86th Legislature, 2019) | Sen. Bob Hall (R) | Regulate plate reader use | Died in committee |
| **HB 3999** (88th Legislature, 2023) | Rep. Brian Harrison (R) | Written policy, warrant requirement, data destruction | Did not receive a hearing |
| **HB 961** (89th Legislature, 2025) | Rep. Brian Harrison (R) | Warrant requirement, restricted use | Did not advance |
| **HB 1607** (89th Legislature, 2025) | — | Additional plate reader restrictions | Did not advance |

What this means for **[REDACTED]**: There are zero state-level guardrails on plate reader use. No required written policy. No mandatory retention limit. No sharing restrictions. No audit requirements. Everything depends on what the city chooses to require — and currently, **[REDACTED]** has adopted none of these protections.

**Other Texas cities have acted voluntarily:**
- **Austin PD** — published written plate reader policy
- **Texarkana PD** — published written plate reader policy
- **Universal City PD** — published written Flock-specific policy
- **Galveston PD** — published written plate reader policy

**[REDACTED]** PD has published exactly one policy on its Professional Standards page: "PO 614 Unbiased Policing." No plate reader, surveillance technology, or Flock Safety policy is posted.

Key question for council: In the absence of state law, the only guardrails are the ones this council creates. Right now, **[REDACTED]** has none.

### B. Texas Penal Code § 16.02 — Unlawful Interception of Communications (Wiretapping)

This statute is directly implicated by Flock's **Raven audio product.**

| Element | Texas Law | Raven Implication |
|---|---|---|
| **Scope** | Prohibits intentional interception of **oral, wire, or electronic communications** | If Raven microphones detect "human voices in distress" — i.e., analyze human speech — they are intercepting oral communications |
| **Consent requirement** | Texas is a **one-party consent state** — at least one party to the communication must consent | Street-level microphones listening for voices have **no one's consent** — neither party to the conversation has agreed to be recorded |
| **"Oral communication" definition** | Communication uttered by a person with a **reasonable expectation that it is not subject to interception** | Conversations on public streets are not inherently without expectation of privacy. Context matters (e.g., a private conversation on a sidewalk) |
| **Penalty** | **Second-degree felony** — 2-20 years imprisonment | Operating microphones that intercept human speech without party consent could constitute a felony under Texas law |
| **Civil liability** | Person recorded can sue for **$10,000 per recording** plus actual damages and attorney fees | Potential class-action exposure for a city operating voice-detecting microphones |

Key question for council: If **[REDACTED]** ever deploys Raven or any audio sensor that analyzes human voices, does that constitute "interception of oral communications" under Texas Penal Code § 16.02? The answer may depend on how the technology works — but the legal risk is real and the penalty is a felony.

### C. Texas Occupations Code, Chapter 1702 — Private Security Act

| Fact | Source |
|---|---|
| Texas DPS determined Flock was **not licensed** under the Private Security Act | TX DPS advisory committee minutes, Jul 17, 2024 |
| DPS issued a **cease-and-desist** ordering Flock to stop operations at private homes/businesses | Fox 26 Houston; KHOU; The Texan |
| Flock operated **without required licensure from 2019 to 2024** — five years | KHOU; DPS investigation reporting |
| DPS lifted the suspension **Nov 4, 2024** — license valid through **Sept 30, 2026** | KHOU follow-up reporting |
| DPS investigation was related to Flock providing services to HOAs and businesses — functions regulated as "investigations company" or "security services contractor" under Ch. 1702 | Texas DPS Private Security Bureau |

Key question for council: Is Flock currently in full compliance with all Texas licensing requirements for the specific services being provided to **[REDACTED]**? Given the five-year compliance gap, this should be verified in writing as a condition of any contract expansion.

### D. Texas Constitution, Article I

| Section | Protection | Plate Reader Relevance |
|---|---|---|
| **Section 9** (Search and Seizure) | "The people shall be secure in their persons, houses, papers and possessions, from all unreasonable seizures or searches" | Texas courts have interpreted this as providing **broader** protections than the Fourth Amendment. A Texas court could require warrants for plate reader data access even if federal courts do not. |
| **Section 19** (Due Course of Law) | No citizen deprived of liberty except by "due course of the law of the land" | Mass surveillance without judicial oversight may implicate due course protections |
| **Section 8** (Free Speech) | Liberty to speak, write, publish opinions | Surveillance has a well-documented **discouraging effect** on constitutionally protected speech, assembly, and association |

---

## 3. FEDERAL LAWS IMPLICATED

### A. Fourth Amendment (via Carpenter v. United States)

As detailed in Section 1 above, the legal question of whether comprehensive plate reader tracking constitutes a Fourth Amendment "search" is **open at the federal appeals level.** Carpenter's reasoning about automated, comprehensive location tracking directly applies, but no federal appeals court has extended Carpenter to plate readers specifically.

The **Congressional Research Service** (July 2025) identified potential Fourth Amendment weak points:
- Sustained tracking of a particular person through plate reader networks
- Comprehensive plate reader databases that can reconstruct a person's movements over time
- Warrantless searching of plate reader records for historical location data

### B. Electronic Communications Privacy Act (ECPA) / Stored Communications Act

| Law | What It Covers | Plate Reader Gap |
|---|---|---|
| **Federal Wiretap Act (Title III of ECPA)** | Prohibits unauthorized interception of wire, oral, and electronic communications in transit | May apply to Raven audio interception; does not clearly cover plate reader image capture |
| **Stored Communications Act (18 U.S.C. §§ 2701-2712)** | Governs government access to stored electronic communications and data | Plate reader data stored by Flock (a third-party service provider) may fall under these protections, but the government has argued plate reader data is not "communications" |
| **Pen Register / Trap and Trace (18 U.S.C. §§ 3121-3127)** | Governs real-time capture of basic communication details (who contacted whom, when, where) | Plate reader captures may be analogous — capturing basic details (plate number, time, location) without content |

**The gap:** ECPA was written in 1986 and does not clearly address modern plate reader systems. Congress has not updated it. This creates a legal gray zone that vendors like Flock exploit.

### C. The Immigration Nexus: Federal Access to Local Data

| Documented Incident | Law Potentially Violated | Source |
|---|---|---|
| Customs and Border Protection accessed Illinois plate reader data | Illinois state law prohibiting sharing plate reader data for immigration enforcement (passed 2023) | IL Secretary of State audit, Aug 2025 |
| Federal agencies accessed Mountain View data via unauthorized "nationwide" setting | Mountain View's local sharing policies; potentially California state privacy law | City of Mountain View statement, Jan 2026 |
| Border Patrol accessed 18 Washington police agencies' Flock data for immigration enforcement | Washington **Keep Washington Working Act** — prohibits local cooperation with federal immigration enforcement | VPM / investigative reporting, Oct 2025 |
| 3,000+ immigration-related searches on Virginia Flock network | Virginia state law regarding plate reader data use limitations | VPM, Oct 2025 |
| Denver Flock cameras tied to immigration searches | Colorado state privacy protections | Denver Clarion, Feb 2026 |

Texas-specific note: Texas is not a sanctuary state — in fact, SB 4 (2017) requires local law enforcement to cooperate with federal immigration authorities. However, the principle remains: who authorized this data sharing, and does the council know it's happening? The issue is not sanctuary policy; it is whether **[REDACTED]**'s data flows to agencies and purposes the council never authorized.

---

## 4. FLOCK'S BACKEND: DATA SHARING THAT MAY EXCEED AUTHORIZED PURPOSES

### The Contract Problem: "Worldwide, Perpetual, Royalty-Free"

The ACLU documented (October 2025) that Flock's standard contract grants the company:

> *"a non-exclusive, worldwide, perpetual, royalty-free right and license"* to *"disclose the Agency Data"* to enable *"law enforcement monitoring against law enforcement hotlists as well as provide Footage search access to law enforcement for investigative purposes."*

What this means: Under the standard contract, Flock has a perpetual license to share **[REDACTED]**'s data with any law enforcement entity for "investigative purposes." This is not time-limited. It is not restricted to specific agencies. The word "worldwide" is in the contract.

### Data Sharing Even When Departments Opt Out

The ACLU found that **even when departments opt to restrict sharing in Flock's system settings, the contract language may still authorize disclosure.**

In Washington state, **Border Patrol accessed data from at least 10 police departments that never agreed to share their data** — the sharing happened through Flock's network design, not through departmental consent.

### The Integration Ecosystem

| Platform | Relationship to Flock | Data Flow Risk |
|---|---|---|
| **Axon Fusus (Real-Time Crime Center)** | Former integration partner (partnership ended early 2025 after Axon acquired Fusus) | Flock data could be fed into Fusus crime center platforms where it is combined with other data sources |
| FlockOS | Flock's own operating system tying plate readers + video + audio + AI search | All data streams converge in a single searchable platform. Patent US11416545B1 describes classification by race, gender, height, weight — a profiling system operating within the same system **[REDACTED]**'s racial profiling standards are meant to govern. |
| **Flock Data Connection** | Open data connection allowing third-party integrations | Terms define "Data" to include images, video, audio, time, location, and anything derived from them |
| **Genetec** | Third-party integration documented | Genetec systems can pull in Flock plate reader data via documented integration |
| **Palantir** | No confirmed direct contract found | However, any data accessible via Flock's data connection or exported to a crime center could be fed into Palantir's Gotham platform by law enforcement intermediaries |
| **National Lookup Network** | Flock-operated cross-jurisdiction search | Opted-in agencies can search across 5,000+ departments' camera data |

### Federal Agency Access: Documented Scale

| Agency | Access Method | Documented Scale | Source |
|---|---|---|---|
| **Customs and Border Protection (CBP)** | Direct pilot program; network queries | 4,000+ immigration-related lookups documented nationwide | IL Secretary of State audit; VPM reporting |
| **Homeland Security Investigations (HSI)** | Direct pilot program | Part of Flock's acknowledged federal pilot | AP, Aug 2025; Flock CEO statement |
| **Bureau of Alcohol, Tobacco and Firearms (ATF)** | Accessed Mountain View data | Confirmed by Mountain View city audit | Mountain View statement, Jan 2026 |
| **U.S. Air Force** | Accessed Mountain View data | Confirmed by Mountain View city audit | Mountain View statement, Jan 2026 |
| **GSA Inspector General** | Accessed Mountain View data | Confirmed by Mountain View city audit | Mountain View statement, Jan 2026 |
| **U.S. Border Patrol** | Accessed 18 Washington state agencies' data | 18 agencies' data accessed for immigration enforcement | Investigative reporting, Oct 2025 |
| **ICE / Enforcement and Removal Operations** | Search terms in Illinois Flock system | 4,000+ lookups with terms like "immigration," "ICE+ERO," "ICE WARRANT" | IL Secretary of State audit |

---

## 5. LAWS THAT MAY BE VIOLATED BY FLOCK'S OPERATIONS

### Summary Table

| Law / Requirement | How It May Be Violated | Severity | Status |
|---|---|---|---|
| No Texas state law requires a written plate reader policy | **[REDACTED]** has no adopted policy. Multiple bills introduced (HB 3999, HB 961) — all died in committee. Zero state guardrails. | Governance gap | Other TX cities (Austin, Texarkana, Universal City) adopted policies voluntarily. **[REDACTED]** has not. |
| Flock contract — "worldwide, perpetual, royalty-free" data license | Standard contract authorizes sharing beyond what **[REDACTED]** may intend. Feb 2026 rewrite: 147 unilateral changes. Deleted: "Flock does not own and shall not sell Customer Data." | Contract/governance issue | Verify **[REDACTED]**'s specific terms. Contract hosted on Flock's website — they can change it at will. |
| No sharing restrictions | No published policy limiting who **[REDACTED]** PD shares Flock data with. 75% of Flock customers in National Lookup network. | Governance gap | Unknown if **[REDACTED]** is in the National Lookup network. |
| TX Penal Code § 16.02 — Wiretapping | Raven audio detecting "human voices" = intercepting oral communications without consent | Second-degree felony (2-20 years) | Applies if Raven or similar audio deployed in **[REDACTED]** |
| **TX Occupations Code Ch. 1702** — Private Security Act | Flock operated unlicensed 2019-2024; current license expires Sept 30, 2026 | Regulatory violation | Currently licensed; verify ongoing compliance |
| **TX Constitution Art. I, § 9** — Unreasonable searches | Mass, warrantless location tracking may violate Texas constitutional protections (interpreted broader than Fourth Amendment) | Constitutional violation | No Texas appeals court ruling on plate readers specifically — unsettled |
| **Fourth Amendment (U.S. Constitution)** — Warrantless search | Under Carpenter logic, comprehensive plate reader tracking may constitute a search | Constitutional violation | Unsettled at federal appeals level; Congressional Research Service confirms no appeals court has ruled |
| Flock standard contract — "worldwide, perpetual" data license | May authorize data sharing beyond what **[REDACTED]** intended or voters expect | Contract/governance issue | Verify **[REDACTED]**'s specific contract terms |
| Federal/state data sharing — Immigration lookups | If federal agencies search **[REDACTED]** data for immigration purposes without **[REDACTED]**'s knowledge or authorization | Governance violation; potential state law violation depending on future TX legislation | Documented in other states; verify **[REDACTED]**'s sharing settings |

---

## 6. ACTIVE LAWSUITS AND LEGAL ACTIONS

### Federal Constitutional Challenges

**Institute for Justice v. City of Norfolk, VA (E.D. Va., filed Oct 2024)**
- Norfolk deployed 176 Flock cameras. Court filings revealed plaintiff Lee Schmidt was tracked **526 times in 4 months** (avg. 4x/day). Co-plaintiff Crystal Arrington was tracked **849 times** (avg. 6x/day).
- Argued: warrantless mass plate reader surveillance violates the Fourth Amendment.
- **Jan 27, 2026:** U.S. District Judge Mark Davis ruled for the city without trial, finding Flock cameras do not constitute an unconstitutional search.
- **Next:** Institute for Justice has announced appeal to the **4th U.S. Circuit Court of Appeals** — which could produce the first federal appeals ruling on plate readers and the Fourth Amendment.
- Flock attempted to intervene in the case and was **rejected by the court.**
- Sources: NBC News; Institute for Justice (ij.org); Courthouse News; The Virginian-Pilot

**ACLU / Electronic Frontier Foundation v. City of San Jose (Santa Clara County Superior Court, filed 2025)**
- Challenges warrantless plate reader mass surveillance under the **California Constitution** (interpreted as stronger than the Fourth Amendment) and California privacy statutes.
- Named defendants: the City, Police Chief Paul Joseph, and Mayor Matt Mahan.
- Seeks court order requiring warrants before searching plate reader databases.
- **Status: Active. Pending.**
- Sources: Electronic Frontier Foundation press release; KQED; 404 Media

### State Law Enforcement Actions

**California Attorney General v. City of El Cajon (San Diego Superior Court, filed Oct 3, 2025)**
- AG Rob Bonta sued El Cajon for sharing Flock plate reader data with **over 100 out-of-state law enforcement agencies** in 26 states — violating California Senate Bill 34 (2015), which prohibits plate reader data sharing with out-of-state agencies.
- Despite prior contact from the California Department of Justice warning El Cajon to stop, the city continued sharing.
- **Status: Active.**
- Sources: CA AG press release (oag.ca.gov); The Record; NBC San Diego; CBS 8

**ACLU v. Oakland Police Department (CA state court, filed Nov 2025)**
- Alleges Oakland PD **repeatedly and illegally** shared Flock surveillance data with federal authorities.
- **Status: Active.**
- Source: The Oaklandside

### Licensing and Regulatory Actions

**NC Private Protective Services Board v. Flock Safety (Wake County, NC, Oct 2023)**
- Wake County Judge Vincent Rozier issued a **court order** requiring Flock to stop installing cameras statewide.
- Found: Flock had been operating **unlicensed in North Carolina for years.**
- The NC board had sent a cease-and-desist in January 2022. Flock did not apply for a license until June 2023.
- **Resolution:** Flock eventually obtained a license valid through July 31, 2026.
- Sources: WRAL; GovTech; CBS 17

**Texas DPS v. Flock Safety (Administrative, Jul 2024)**
- Texas DPS determined Flock was **not licensed** under the Private Security Act (TX Occupations Code Ch. 1702).
- Issued **cease-and-desist** on July 10, 2024, ordering Flock to stop operations at private homes/businesses.
- DPS investigation confirmed Flock operated without a license **from 2019 to 2024** — five years.
- **Resolution:** DPS lifted suspension Nov 4, 2024. License valid through Sept 30, 2026.
- Sources: Fox 26 Houston; KHOU; The Texan; TX DPS advisory committee minutes

### Public Records Lawsuits

**ACLU of Oregon v. City of Eugene (filed Oct 2025)**
- Sued for refusing to disclose public records about Flock camera locations and operations.
- **Status: Active.**
- Sources: Oregon Capital Chronicle; ACLU of Oregon

**Rodriguez v. City of Stanwood, WA (Snohomish County Superior Court)**
- Alleges violation of Washington Public Records Act for failing to provide Flock footage.
- **Status: Active.**
- Source: Everett Herald

### Contract Terminations for Cause

**Cambridge, MA — Contract terminated Dec 10, 2025**
- Flock installed two new cameras *after the council voted to deactivate the system.* City Manager stated: "breach of trust and the agreement."
- Sources: City of Cambridge official statement; Boston.com; Harvard Crimson

Mountain View, CA — System shut down Feb 2, 2026; termination vote **[REDACTED]**, 2026
- Audit revealed 17 months of unauthorized federal access via a "nationwide" setting enabled without police knowledge.
- Police chief recommended termination.
- Sources: Mountain View Voice; City of Mountain View official statement

### Federal Investigation Request

**Wyden/Krishnamoorthi to Federal Trade Commission (Nov 3, 2025)**
- Senator Ron Wyden (D-OR) and Representative Raja Krishnamoorthi (D-IL) sent formal letter requesting the Federal Trade Commission investigate Flock Safety for:
 - Failure to require extra login security (multi-factor authentication)
 - At least 35 customer accounts with stolen passwords
 - Serving 5,000+ police departments and 1,000+ businesses without basic cybersecurity protections
- Argued: failure to require extra login security is an **unfair business practice under Section 5 of the Federal Trade Commission Act** (citing Uber, Chegg, Drizly, Blackbaud precedents).
- **Status: Pending Federal Trade Commission action.**
- Sources: wyden.senate.gov; The Record; Biometric Update

### Class Action Investigation

**Gibbs Mura Law Group — Class action investigation (ongoing)**
- Investigating potential class action lawsuit against Flock Safety for privacy violations related to plate reader data collection and sharing.
- **Status: Investigation stage.**
- Source: classlawgroup.com

---

## 7. PROPOSED TEXAS LEGISLATION (INTRODUCED BUT NOT YET PASSED)

| Bill | Sponsor | What It Would Do | Status |
|---|---|---|---|
| **SB 78** (86th Legislature, 2019) | Sen. Bob Hall (R) | Regulate plate reader use | Died in committee |
| **HB 3999** (88th Legislature, 2023) | Rep. Brian Harrison (R) | Require **warrant or court order** for plate reader use; limit data to violent crime investigations only; require data destruction "promptly after collection" | Did not receive committee hearing |
| **HB 961** (89th Legislature, 2025) | Rep. Brian Harrison (R) | Warrant requirement, restricted use | Did not advance |
| **HB 1607** (89th Legislature, 2025) | — | Additional plate reader restrictions | Did not advance |

**Key point for council:** The Texas Legislature has considered — but not yet passed — warrant requirements and strict retention limits for plate readers. The fact that these bills were introduced by *Republican* legislators undermines any claim that plate reader governance concerns are partisan. These bills reflect bipartisan Texas concern about surveillance overreach.

---

## 8. WHAT **[REDACTED]** SHOULD DO: LEGAL RISK MITIGATION

| # | Action | Legal Basis |
|---|---|---|
| 1 | Adopt a written plate reader policy | No Texas state law requires one — but Austin, Texarkana, and Universal City adopted policies voluntarily. **[REDACTED]** has none. In the absence of state guardrails, the only protections are the ones this council creates. |
| 2 | **Review and renegotiate contract** to remove "worldwide, perpetual, royalty-free" data license | ACLU documentation of standard contract terms |
| 3 | **Explicitly prohibit federal agency access** without council authorization | Documented Customs and Border Protection / ICE / ATF access in other jurisdictions |
| 4 | **Prohibit audio sensors / Raven** | TX Penal Code § 16.02 — intercepting oral communications without consent is a **felony** |
| 5 | **Cap retention at 30 days by ordinance** | Flock's policy allows up to 1 year without a local cap. No state law sets a limit — the only restriction is what the city requires. |
| 6 | **Require warrant-level justification** for historical location tracking searches | Anticipates likely extension of Carpenter to plate readers; protects prosecutions from future challenges |
| 7 | **Require annual Texas licensing verification** | Flock operated unlicensed 2019-2024; current license expires Sept 2026 |
| 8 | Demand contract language that Flock cannot share data except as explicitly authorized by **[REDACTED]**'s written policy | Prevents "worldwide perpetual" sharing from overriding local governance |
| 9 | Evaluate Flock's profiling system against **[REDACTED]**'s racial profiling standards | Patent US11416545B1 describes classification by race and gender. Council is reviewing the PD's 2025 Racial Profiling Analysis (Consent Item **[REDACTED]**) — the technology should be evaluated against the same standards |

---

## Sources

| Source | URL / Citation |
|---|---|
| TX plate reader bills (HB 3999, HB 961, SB 78, HB 1607) — all died in committee | capitol.texas.gov |
| Flock Feb 2026 contract changes (147 edits) | haveibeenflocked.com/news/terms-feb2026 |
| TX Penal Code § 16.02 | codes.findlaw.com/tx/penal-code/penal-sect-16-02 |
| TX Occupations Code Ch. 1702 | statutes.capitol.texas.gov/GetStatute.aspx?Code=OC&Value=1702 |
| TX Constitution, Art. I | statutes.capitol.texas.gov/Docs/CN/htm/CN.1.htm |
| Carpenter v. United States, 585 U.S. 296 (2018) | supreme.justia.com/cases/federal/us/585/296 |
| Commonwealth v. Church (VA Ct. App., Oct 2025) | vacourts.gov/static/opinions/opncavwp/0737251.pdf |
| Congressional Research Service IF13068 (Jul 2025) | congress.gov/crs-product/IF13068 |
| ACLU — "Flock Can Share Data Even When Departments Opt Out" | aclu.org/news/privacy-technology/flock-massachusetts-and-updates |
| Electronic Frontier Foundation — Virginia warrant brief | eff.org/deeplinks/2025/09/eff-urges-virgina-court-appeals-require-search-warrants-access-alpr-databases |
| ACLU/Electronic Frontier Foundation — San Jose plate reader lawsuit | aclunc.org/news/lawsuit-challenges-san-jose-s-warrantless-alpr-mass-surveillance |
| HB 3999 text | capitol.texas.gov/tlodocs/88R/billtext/html/HB03999I.htm |
| IL SOS audit | ilsos.gov/news/2025/august-25-2025-... |
| Mountain View statement | mountainview.gov/Home/Components/News/News/1203/284 |
| VPM — Virginia immigration searches | vpm.org/news/2025-10-09/flock-safety-cameras-alprs-federal-immigration-enforcement |
| TX DPS cease-and-desist | fox26houston.com; khou.com; thetexan.news |
| NPR — cities canceling contracts | npr.org/2026/02/17/nx-s1-5612825/flock-contracts-canceled-immigration-survillance-concerns |
| Brennan Center — plate reader legal status | brennancenter.org/our-work/research-reports/automatic-license-plate-readers-legal-status-and-policy-recommendations |
| GovTech — Virginia judge rejects plate reader evidence | govtech.com/public-safety/virginia-judge-rejects-alpr-evidence-without-warrant |

---

*Every citation in this document references a published court opinion, enacted statute, government record, or reporting from identified news organizations. No anonymous sources, no speculation, no advocacy claims presented as legal conclusions.*
