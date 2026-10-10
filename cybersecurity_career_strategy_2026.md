# Cybersecurity Career Strategy, Resume, and Advancement Roadmap (2026–2030)

_Prepared: October 2026 · Owner: William · Status: Living document_

---

## 1. Executive Summary

You are an experienced Boeing security professional (Technology & Engineering Security Test Conductor since ~April 2024, Product Security Analyst Aug 2022–Apr 2024, with prior defense-system administration experience and U.S. Army infantry team leader background from 2012). You hold a Master of Information and Cybersecurity (MICS) from UC Berkeley (GPA 3.922), GIAC GPEN / GCIH / GSEC / GFACT, and CompTIA Security+. You are actively studying for CPTS (HTB Academy's Certified Penetration Testing Specialist, currently 3/28 modules) and OSCP, building a Python-based API pentesting portfolio project ("numnum"), and have ~1 year of runway at Boeing before possible team restructuring.

**Primary recommendation:** Pursue a **Technical Leadership → Independent Consultant** hybrid path, leveraging aerospace/product-security specialization. Target a Senior/Lead Penetration Tester or Principal Security Consultant role within 12–18 months (either internal Boeing engineer-level promotion or external consulting firm), then transition to independent consulting in year 3–4, and consider a boutique aerospace/embedded-systems security firm by year 5+.

**Why this path:**
- Your aerospace + GPEN + MICS combination is scarce and defensible.
- Pure IT pentesting is commoditized; aerospace/embedded/product security commands premium rates.
- Military + leadership experience supports client-facing and firm-ownership stages.
- You already have the hands-on offensive foundation most consultants spend years building.

**Immediate next 90 days (must-do):**
1. Finish 6 more CPTS modules (web app + AD focus).
2. Push "numnum" to a presentable public GitHub state (README, screenshots, one OWASP API finding demo).
3. Rewrite resume for external consulting market (see §6).
4. Begin PortSwigger Web Security Academy JWT/OAuth/SSRF tracks.
5. Document Boeing conflict-of-interest / outside-work policy before any paid side work.

**Compensation targets (defensible, see §3 for sources & assumptions):**
- Senior Pentester (Seattle/remote, cleared or clearable): **$150k–$200k base, $170k–$230k total.**
- Principal / Lead Consultant: **$180k–$250k base, $210k–$300k total.**
- Independent (billable 1,200–1,500 hrs/yr at $200–$350/hr): **$240k–$525k gross; $140k–$320k owner earnings after costs.**

---

## 2. Verified Professional Profile and Assumptions

### 2.1 Fact Inventory

| Item | Status | Source |
|---|---|---|
| Current role: Boeing Technology & Engineering Security Test Conductor (~Apr 2024–present) | User-reported | Prompt + Notion |
| Prior role: Boeing Product Security Analyst (~Aug 2022–Apr 2024) | User-reported | Prompt |
| Prior Boeing defense-system admin / InfoSec on P-8, tanker, AWACS, C-17 simulators | User-reported | Prompt |
| Led/coordinated ~4 penetration testers at Boeing | User-reported | Prompt |
| U.S. Army infantry team leader (~2012) | User-reported | Prompt |
| MICS, UC Berkeley, GPA 3.922 | User-reported | Prompt |
| Bachelor's in kinesiology and/or cybersecurity/forensics | **Needs verification** — exact institution, degree title, completion status unclear |
| ASU D.Eng. (Engineering Management) & WGU CS | **Not completed** — described as "considered" |
| Bachelor's in Cybersecurity (second attempt) started ~June 2026 | Notion Career Plan | **Needs verification** — institution not named |
| GIAC GPEN, GCIH, GSEC, GFACT | User-reported | Prompt — verify current/expired status |
| CompTIA Security+ | User-reported | Prompt |
| Active study: CPTS (3/28 modules), OSCP prep, PortSwigger, TCM, HTB | Notion |
| "numnum" Python assessment tool: modular, SQLite, Nmap recon, resume/retry | User-reported — **not yet public portfolio-ready** |
| Residence: Kent, WA area; family (two children) | Notion |
| Clearance status | **Unknown — must verify.** Many defense/aerospace roles require active clearance |

**Items that must be confirmed before external resume submission:**
1. Exact bachelor's degree title, institution, dates, completion status.
2. Current/active status of GPEN, GCIH, GSEC (GIAC renewals).
3. Clearance level and current status (Secret? TS? Inactive?).
4. Legal/HR title and dates for each Boeing role (resume must match internal records if background-checked).
5. Scope metrics for Boeing work: # of systems/programs assessed, team size led, # of vulnerabilities documented, # of test procedures authored.

### 2.2 Assumptions used in this plan

- You have a Secret clearance (common for your program list) — if not, cleared-roles compensation data is still informative but availability narrows.
- The "team of ~4 pentesters" was a lead/coordination role, not formal people-management with hire/fire authority. Resume will say "led," not "managed."
- Your "numnum" project does **not** contain any Boeing-proprietary code or program data — this needs explicit confirmation before publishing.
- You are not currently monetizing side work and have not reviewed Boeing's outside-work policy. All independent-consulting steps in §10 are gated on that review.

---

## 3. 2026 Career Market and Compensation Analysis

### 3.1 Market context (2025–2026)

Penetration-testing demand continues to grow, but the market has bifurcated:

- **Commodity external pentesting / web app** — downward pressure from offshoring, automation, and continuous pentesting platforms (Cobalt, HackerOne Pentest, Synack). Mid-level salaries flat.
- **Specialized assessment work** — cloud/Kubernetes, embedded/IoT, OT/ICS, aerospace product security, red team ops, AI/ML security — strong demand and salary growth.
- **Cleared defense/aerospace** — stable demand, premium for active clearance + domain expertise. Boeing, Lockheed, Northrop, RTX, L3Harris, BAE, and prime subcontractors (Leidos, Booz Allen, Mantech, Peraton, SAIC) all actively hiring product-security and offensive-security engineers in 2026.
- **Boutique consulting** — firms like Bishop Fox, NetSPI, TrustedSec, Praetorian, GuidePoint, IOActive continue to dominate higher-end work and typically pay 15–30% above big-four cyber practices for senior IC roles.

**Sources & caveats:** Compensation ranges below are synthesized from publicly observable 2025–2026 job postings on employer career pages (Boeing, Bishop Fox, NetSPI, IOActive, Leidos, Booz Allen), BLS OEWS 15-1212 Information Security Analysts (national + Seattle-Bellevue-Tacoma MSA), Levels.fyi, and recruiter reports (Hays, Robert Half, Mondo 2025 Cyber salary guides). **Ranges should be treated as estimates with ±15% uncertainty.** Where I cite a specific range, verify against two live postings before using it in a negotiation.

### 3.2 Career ladder — titles, scope, and compensation

| Stage | Common titles | Years exp | Typical US base | Typical total comp | Seattle/Puget Sound adj. |
|---|---|---|---|---|---|
| **1. Senior Pentester** | Sr. Penetration Tester, Sr. Offensive Security Engineer, Sr. Red Team Operator, Sr. Security Assessment Engineer | 4–8 | $130k–$180k | $150k–$215k | +5–10% |
| **2. Sr. Security Consultant** | Sr. Security Consultant, Sr. Pentest Consultant, Sr. Offensive Security Consultant | 5–9 | $140k–$190k | $165k–$235k | +5–10% |
| **3. Staff / Principal / Lead Consultant** | Principal Consultant, Lead Pentester, Staff Offensive Security Engineer, Technical Lead | 8–12 | $170k–$230k | $200k–$290k | +5–10% |
| **4. Red Team Lead / Assessment Lead** | Red Team Lead, Principal Red Teamer, Head of Offensive Security, Assessment Lead | 9–13 | $180k–$245k | $210k–$320k | +5–10% |
| **5. Practice Lead / Technical Director** | Director of Offensive Security, Consulting Practice Lead, Security Services Manager, Technical Director | 10–15 | $200k–$275k | $240k–$400k (bonus/equity heavier) | +5–10% |
| **6. Independent Consultant** | Independent Pentest Consultant, 1099 Sr. Consultant, Fractional Security Lead | 8+ | Billings $200–$350/hr; est. gross $240k–$525k on 1,200–1,500 billable hrs | Owner earnings ~55–65% of gross after costs | Rate elastic to specialty, not geography |
| **7. Boutique Firm Owner** | Founder / Principal / Managing Consultant | 10+ | Owner salary $150k–$300k early; profit distributions variable | High variance; sustainable firms $500k+ owner comp in years 4–6 | Primarily specialty-driven |

**Aerospace / product-security premium:** For stages 1–5, an active Secret clearance + aerospace product-security experience typically adds **$10k–$25k to base** and significantly broadens role availability (Boeing engineer ladder, Lockheed, Northrop, Leidos). This is your single largest market differentiator.

### 3.3 Employee vs. independent vs. firm-owner economics

| Dimension | W-2 Employee | 1099 Independent | Boutique Firm Owner |
|---|---|---|---|
| Gross income | Base + bonus + equity | Billings × utilization | Firm revenue |
| Benefits | ~25–30% of base in value | Self-funded (health, 401k, disability) | Firm-funded, varies |
| Unpaid time | PTO + holidays paid | PTO, holidays, sick days unpaid | Owner absorbs |
| Business dev | None | 10–25% of time, unbilled | 20–40% of leadership time |
| Utilization | N/A | Realistic 60–75% (1,200–1,500 hrs/yr) | Target 70–80% per consultant |
| Insurance | Employer-paid | E&O $2k–$5k/yr, liability, health $20k+/yr family | Firm overhead; add D&O |
| Taxes | W-2 withholding | SE tax (self-employment) 15.3% up to cap; quarterly estimates | Pass-through or C-corp; payroll obligations |
| Admin overhead | None | 5–10 hrs/wk accounting, contracts, scheduling | Full back-office or outsourced |
| Income volatility | Low | Moderate–high | High in years 1–3, moderate thereafter |

**Rule of thumb:** Independent gross ÷ 1.4–1.5 ≈ comparable W-2 total comp. A $300k billings year is roughly equivalent to a $200k–$215k W-2 total-comp job once benefits, unpaid time, and overhead are modeled.

### 3.4 Example 2026 postings used as compensation anchors

(Representative only — URLs/titles rotate; verify at search time.)

- Boeing Cybersecurity Engineer / Senior (Seattle, Berkeley, St. Louis) — product security, test, assurance. Base typically $120k–$180k + bonus; see Boeing careers portal.
- Leidos Senior Penetration Tester (cleared, remote/Reston/Seattle) — $130k–$190k.
- Bishop Fox Senior Consultant / Principal — $160k–$220k base + bonus, remote.
- NetSPI Senior/Principal Pentester — $140k–$210k base + bonus, remote.
- IOActive Senior Security Consultant (embedded/aerospace lean) — $150k–$220k, remote.
- Booz Allen / SAIC / Peraton cleared offensive security — $130k–$190k, clearance required.

**Action:** Before any negotiation, pull five live postings for your target title and geography, record base + bonus + equity, and use the 25th/50th/75th percentiles rather than a single data point.

---

## 4. Career Ladder and Role Requirements

### 4.1 Senior Penetration Tester (Stage 1)

- **Responsibilities:** Scope and execute external/internal network, web app, and (increasingly) cloud/API assessments; lead one engagement end-to-end; write client-ready reports; mentor juniors on 1–2 engagements/quarter.
- **Experience signals:** 4–7 years hands-on; 50+ engagements or equivalent; demonstrable portfolio; one of OSCP / CPTS / GPEN; comfortable presenting findings to engineering + leadership.
- **Technical bar:** AD attack chains end-to-end (Kerberoasting, delegation abuse, AD CS, DCSync); web top-10 and OWASP API top-10 with proof; competent Linux priv-esc; one scripting language fluent (Python). Report writing is now a graded skill.
- **Your gap:** External validation that your Boeing work maps to this scope. Public portfolio evidence (writeups, tool, blog) to counterbalance regulated-industry opacity.

### 4.2 Senior Security Consultant (Stage 2)

- Adds: client-facing scoping calls, SOW input, status communication, kickoff/readout meetings, remediation validation, defensible estimate on effort.
- **Your gap:** Consulting-firm process (methodology adherence, time tracking, utilization) and client-communication reps. Boeing has "stakeholders" but not "clients."

### 4.3 Principal / Lead Consultant (Stage 3)

- Adds: methodology ownership, novel-vulnerability class work, pre-sales technical support, mentorship across multiple consultants, internal R&D (tool, training).
- **Required evidence:** Original research, conference talk or CVE, mentorship record, delivered multi-engagement programs.
- **Your gap:** Published research or at least substantial public blog/tool presence.

### 4.4 Red Team Lead / Assessment Lead (Stage 4)

- Adds: multi-week adversary emulation, C2 operations, OPSEC under detection, cross-team coordination with blue team, custom tooling (loaders, C2 profiles).
- **Required evidence:** CRTO / OSEP level work; prior red team ops leadership; detection evasion track record.
- **Your gap:** Red team operator depth (vs. assessment-style pentesting) — large investment; evaluate against ROI (see §7).

### 4.5 Practice Lead / Technical Director (Stage 5)

- Adds: hire/fire, utilization and margin ownership, service-line roadmap, major-client ownership, pre-sales leadership, methodology and QA ownership.
- **Required evidence:** 2+ years senior IC + direct reports + P&L exposure.

### 4.6 Independent Consultant (Stage 6)

- Needs: credible personal brand, referral pipeline, repeatable service offerings, standardized SOW/MSA templates, E&O + general liability insurance, business entity (LLC or S-corp), accounting, invoicing cadence, utilization discipline.

### 4.7 Boutique Firm Owner (Stage 7)

- Needs: everything in Stage 6 plus: hiring/onboarding, consultant ladder, delivery QA, legal/HR counsel, cash management (3–6 months of payroll reserve), customer concentration <30%, defensible niche (yours would be aerospace / embedded / product security).

---

## 5. Recommended Career Strategy and Target Roles

### 5.1 Path comparison

| Path | Fit (your background) | Earnings potential | Time to competitive | Autonomy | Risk | Transferability of aerospace exp. |
|---|---|---|---|---|---|---|
| **A. Technical Specialist** (Sr → Principal pentester) | Strong | Good ($200–$290k) | 12–24 mo | Low–Med | Low | Medium (unless pivoting to embedded/product) |
| **B. Technical Leadership** (Lead → Practice Lead) | Good — leverages military + Boeing lead experience | Very good ($240k–$400k) | 24–48 mo | Medium | Low–Med | High |
| **C. Independent Business** (Consult → Boutique) | Moderate now, strong by year 3 | Highest ceiling, highest variance | 36–60 mo | High | High | Very high (aerospace niche) |

### 5.2 Recommended: hybrid B → C

1. **Now–18 months:** Push into a Senior/Lead external-market role (or internal Boeing engineer-level promotion with pentesting scope). Build a public portfolio and specialty signal.
2. **18–36 months:** Establish Principal / Lead title at a boutique or defense prime. Start side consulting under a documented Boeing/employer-approved arrangement, or begin niche content/research publication.
3. **36–60 months:** Transition to independent consulting with established pipeline. Evaluate boutique firm only once you have >12 months of consistent referrals + at least one anchor client willing to sign a multi-engagement MSA.

### 5.3 Alternative: Path B pure (technical leadership inside aerospace/defense)

If independence proves unappealing (family stability, risk tolerance), stop at Stage 4–5 inside a defense prime or boutique. $300k+ total comp is achievable without equity risk.

### 5.4 Target roles by horizon

- **Now (0–6 months):** Senior Penetration Tester, Senior Offensive Security Engineer, Senior Product Security Engineer (Boeing engineer ladder), Senior Security Consultant (Bishop Fox, NetSPI, IOActive, Leidos, Booz Allen).
- **6–12 months:** Add Lead / Principal titles at same firms; Senior Red Team Operator at defense primes.
- **12–24 months:** Principal Consultant, Lead Pentester, Technical Lead for Offensive Security.
- **24–60 months:** Director/Practice Lead or Independent Consultant specializing in aerospace / embedded product security.

---

## 6. ATS-Friendly Resume

> _Below is the primary resume positioned for Senior/Lead Penetration Tester / Senior Security Consultant roles. Uses only user-reported facts; placeholders flagged `[VERIFY: …]` must be confirmed before submission._

```
WILLIAM [LAST NAME]
Kent, WA · [phone] · [email] · [LinkedIn] · [GitHub]
Active [VERIFY: clearance level & status]

SUMMARY
Offensive security practitioner with [VERIFY: X]+ years in aerospace product security
and penetration testing. GPEN-certified, UC Berkeley MICS graduate, with hands-on
experience leading security assessments across defense training and simulation
systems. U.S. Army veteran. Building toward senior consulting and independent
advisory work in embedded and aerospace product security.

CORE SKILLS
Penetration Testing · Product Security · Security Assessment Methodology ·
Web/API Testing (OWASP Top 10 / API Top 10) · Active Directory Attack Chains ·
Network & Host Enumeration · Nmap / Burp Suite / Metasploit · Python Scripting ·
Technical Report Writing · Stakeholder Communication · Test Procedure Development ·
Vulnerability Analysis · Security Certification Support

CERTIFICATIONS
GIAC GPEN — Certified Penetration Tester                       [VERIFY: date / active]
GIAC GCIH — Certified Incident Handler                         [VERIFY: date / active]
GIAC GSEC — Security Essentials                                [VERIFY: date / active]
GIAC GFACT — Foundational Cybersecurity Technologies           [VERIFY: date / active]
CompTIA Security+                                              [VERIFY: date / active]
In progress: HTB CPTS (2026) · OSCP preparation

EXPERIENCE

The Boeing Company                                    Seattle, WA / Puget Sound
Technology and Engineering Security Test Conductor     Apr 2024 – Present
- Plan and conduct offensive security assessments against engineering and
  product systems supporting [VERIFY: program scope — non-sensitive wording].
- Lead a team of [VERIFY: ~4] penetration testers through engagement planning,
  execution, evidence collection, and findings reporting.
- Develop test cases and test procedures aligned to product security
  certification requirements; coordinate with engineering stakeholders on
  remediation and verification.
- Identify attack vectors across network, host, and application layers;
  document findings with reproducible proof and risk-weighted recommendations.
- Mentor junior testers on methodology, tooling, and reporting standards.

The Boeing Company                                    Seattle, WA / Puget Sound
Product Security Analyst                              Aug 2022 – Apr 2024
- Supported product security certification activities across [VERIFY: # of]
  programs, including documentation review, control assessment, and
  evidence collection.
- Conducted network security assessments and reviewed system documentation
  to identify design and implementation weaknesses.
- Partnered with engineering teams to translate security requirements into
  verifiable test cases.

The Boeing Company                                    Seattle, WA / Puget Sound
Information Systems Security / Systems Administrator  [VERIFY: dates]
- Administered defense training and simulation systems supporting P-8, KC-46
  tanker, AWACS, and C-17 programs. [VERIFY: wording approved by Boeing]
- Executed configuration management, patching, hardening, and audit support
  under regulated environment controls.

United States Army                                    [VERIFY: location]
Infantry Team Leader                                  ~2012 – [VERIFY: end]
- Led a fire-team of [VERIFY: #] soldiers through training and operations.
- Accountable for mission planning, equipment readiness, and small-unit
  tactical execution.

EDUCATION
University of California, Berkeley
Master of Information and Cybersecurity (MICS)        GPA 3.922
[VERIFY: graduation year]

[VERIFY: Bachelor's degree — exact title, institution, year, completion status]

SELECTED PROJECTS
numnum — Python Security Assessment Framework
- Modular Python assessment tool with SQLite persistence, Nmap-based
  reconnaissance, assessment state management, and resume/retry capability.
- Personal project; no employer-owned code. [VERIFY: GitHub URL]

[Optional once published:] API Pentesting Portfolio
- Reproducible OWASP API Top-10 demonstrations against OWASP crAPI / vAPI
  with report-style write-ups.

PROFESSIONAL DEVELOPMENT
- Hack The Box Academy — CPTS track (in progress)
- PortSwigger Web Security Academy — JWT, OAuth, SSRF modules
- TCM Security — Web API Pentesting
```

### 6.1 Tailoring guidance (brief)

- **For aerospace/defense primes (Boeing engineer, Leidos, Booz Allen):** Lead with clearance, GIAC, and program support experience; demote the API portfolio.
- **For boutique consulting (Bishop Fox, NetSPI, IOActive):** Lead with assessment methodology, portfolio project, and reporting evidence; move "Systems Admin" to a one-line entry.
- **For independent consulting proposals (future):** Replace this with a one-page capability statement, not a resume. Lead with specialty (aerospace product security), representative engagements, methodologies, and references.

### 6.2 Resume quality notes

- No invented metrics. Every number is a `[VERIFY: …]` placeholder.
- "Led" is used instead of "managed" for your pentester-coordination role, which matches scope accurately without overstating authority.
- Military entry is kept short and professional; expand only for federal/cleared roles that value veteran status.

---

## 7. Skills Gap and Certification Priority Matrix

### 7.1 Technical skill gaps vs. Senior/Lead Pentester bar

| Area | Current (self-reported) | Target | Gap | Priority |
|---|---|---|---|---|
| Web app testing | Fundamentals + study in progress | Fluent OWASP Top 10 + API Top 10 with report-grade PoCs | Medium | **High** |
| JWT / OAuth / SSRF | Studying | Confident exploitation and reporting | Medium | **High** |
| Active Directory | Strong per Notion (Kerberoasting, DCSync, BloodHound) | Maintain + add AD CS, cert services | Low | Medium |
| Cloud (AWS/Azure/Entra) | Limited | Baseline AWS + Entra ID assessment | Large | **High** (market demand) |
| Python scripting under pressure | Learning | Modify and chain exploits mid-engagement | Medium | High |
| Reverse engineering / exploit dev | Fundamentals | Baseline Ghidra + simple ROP; not a specialization unless pivoting | Large | Conditional (see 7.3) |
| Report writing & risk communication | Partial | Senior-consultant level, exec-ready | Medium | **High** |
| Scoping / estimation / SOW | Limited | Owns scoping call for an engagement | Large | Medium (unlocks Stage 2+) |
| Red team ops (C2, OPSEC) | Limited | Baseline CRTO level | Large | Low–Conditional |
| Embedded / aerospace product security specialty | Strong Boeing exposure | Published/credible specialty signal | Small (depth), Large (visibility) | **High** (your differentiator) |

### 7.2 Certification priority

**High priority (pursue in order):**
1. **CPTS (HTB)** — already in progress; strong practical value, modest cost (~$8–$18/mo Academy sub + $210 exam). Finish by month 10–12.
2. **OSCP** — ~$1,650 bundled with PEN-200 lab access; still the hiring filter for many consulting firms. Pursue after CPTS to leverage momentum.
3. **CRTO (Zero-Point Security)** — ~£399; the most cost-effective "I can red team" credential. Only if targeting red-team roles (Stage 4) — otherwise defer.

**Conditional:**
- **OSEP / OSWE** (OffSec $1,650 each) — only if moving toward exploit dev / advanced web. OSWE is a better fit for your API portfolio direction.
- **AWS Certified Security Specialty** — $300 — pursue if cloud assessment work becomes a target.
- **CCSP / CISSP** — primarily for Stage 5+ leadership roles, hiring filters at large consultancies. Low urgency now; CISSP has value only if you move into leadership requiring it.
- **Offensive Security Experienced Penetration Tester (OSEP)** — conditional on red-team pivot.

**Low priority:**
- Additional GIAC certs (GXPN, GWAPT) — expensive ($$$8k+) for marginal signal over existing GIAC stack. Only if employer pays.
- CEH, PenTest+ — redundant with your existing credentials.
- CRTP / CRTE — AD-focused; strong technically but less employer-recognized than CRTO for red-team roles.

**Deliberately NOT recommended right now:** D.Eng (ASU), additional master's, PhD. Your MICS already exceeds credential expectations for every stage in §4. Time is better spent on portfolio, specialty content, and client-facing reps.

**Bachelor's degree note:** The Notion Career Plan references starting a bachelor's in cybersecurity in June 2026 "needed for Boeing engineer path." If that is a hard Boeing requirement for your internal promotion track, keep it on the plan but minimize scope (fastest path, cheapest institution — WGU B.S. Cybersecurity is a common choice because it's self-paced and credit-friendly). Externally, your MICS makes a second bachelor's low-value.

---

## 8. Month-by-Month 24-Month Roadmap

**Assumptions:** 10–12 focused hours/week sustainable (Notion target); first month = October 2026. Each month lists must-do (M) and stretch (S). "Portfolio artifact" means something linkable from your GitHub / blog.

### Phase 1 — Baseline & high-value gaps (Months 1–3, Oct–Dec 2026)

**Month 1 — Oct 2026**
- M: Finish 2 CPTS enumeration/footprinting modules.
- M: Finalize "numnum" README + add a demo asciinema; make the repo presentable (even if private initially).
- M: Resume rewrite v1 using §6; collect `[VERIFY]` answers.
- M: Confirm GIAC renewal status for GPEN/GCIH/GSEC; schedule renewals as needed.
- M: Read Boeing outside-work / IP / COI policy; document in a private file.
- S: Start PortSwigger JWT labs.
- Weekly: 10–12 hr. Success: resume shared with 1 trusted reviewer; 2 CPTS modules complete.

**Month 2 — Nov 2026**
- M: 2 CPTS web app modules; complete PortSwigger JWT + OAuth labs.
- M: "numnum" — add OWASP API #2 (broken auth) demonstration + JSON report output.
- M: Draft a 2-page HTB box writeup in **engagement-report format** (exec summary, finding, PoC, impact, remediation). Publish on blog or GitHub.
- S: Pull 5 live Senior Pentester job postings; build a target-role bullet-match matrix.

**Month 3 — Dec 2026**
- M: 2 CPTS modules (web app / AD transition).
- M: Second engagement-style writeup published.
- M: Resume v2 after bullet-match matrix.
- M: Quarterly checkpoint (see §9).
- S: One short conference talk / lunch-and-learn at Boeing on a non-sensitive topic (practice senior-level communication).

### Phase 2 — Advanced technical depth (Months 4–9, Jan–Jun 2027)

**Month 4 — Jan 2027**
- M: 2 AD attack modules (CPTS).
- M: PortSwigger SSRF + Access Control labs complete.
- M: "numnum" — add fuzzing module (injection class, OWASP API #3).
- S: Begin AWS fundamentals (Security Specialty-aligned).

**Month 5 — Feb 2027**
- M: 2 CPTS modules.
- M: Build and document end-to-end AD lab engagement (self-hosted, documented from recon → DA).
- M: Write 1 blog post on "how I'd pentest an aerospace product system" — generic, no employer IP.

**Month 6 — Mar 2027**
- M: 2 CPTS modules; begin mock exam prep.
- M: AWS Security baseline work; S3 + IAM misconfig lab writeup.
- M: Quarterly checkpoint — decide: external applications now, or wait until CPTS passed?

**Month 7 — Apr 2027**
- M: Finish any remaining CPTS modules.
- M: CPTS exam attempt.
- M: "numnum" v1.0 release — tag it, write release notes.

**Month 8 — May 2027**
- M: Retake CPTS exam if needed; otherwise start OSCP PEN-200.
- M: Begin PortSwigger / HackTricks advanced web (SSTI, deserialization).
- S: First outside conference submission (BSides Seattle talk CFP).

**Month 9 — Jun 2027**
- M: OSCP prep in earnest — HTB OSCP-like boxes.
- M: Publish a tool, module, or research write-up substantial enough to serve as "principal-level evidence."

### Phase 3 — Senior-level capability demonstration (Months 10–15, Jul–Dec 2027)

**Month 10 — Jul 2027**
- M: OSCP exam attempt.
- M: Build a methodology document (your personal pentest methodology) — this is a consulting-firm interview artifact.

**Month 11 — Aug 2027**
- M: Retake OSCP if needed.
- M: Start applying to 3–5 external Senior Pentester / Sr. Consultant roles. Negotiate using §3 anchors.
- M: Resume v3 (post-CPTS/OSCP).

**Month 12 — Sep 2027**
- M: Interview reps; iterate on gaps found.
- M: Decide: accept external offer, use external offer to leverage Boeing promotion, or stay-and-build.

**Month 13 — Oct 2027**
- M: Begin Lead/Principal preparation: own at least one engagement end-to-end at current employer with full scoping + readout.
- M: Draft a public "service capability statement" (even if unused) to clarify your specialty.

**Month 14 — Nov 2027**
- M: Mentor a junior formally — document the engagements you lead them through.
- M: Specialty content — one piece/month on aerospace or embedded product security.

**Month 15 — Dec 2027**
- M: Quarterly checkpoint. CRTO decision gate (see §9).

### Phase 4 — Lead / principal readiness (Months 16–21, Jan–Jun 2028)

**Month 16 — Jan 2028**
- M: If CRTO chosen, begin Red Team Ops course.
- M: Build a "statement of work" template and a "test plan" template — both are consultant toolkit items.

**Month 17 — Feb 2028**
- M: Scoping / estimation practice — estimate 3 past engagements and compare to actuals.
- M: Specialty publication piece 4+.

**Month 18 — Mar 2028**
- M: Quarterly checkpoint. Decide: Principal track at current employer, external Principal role, or begin independent-consulting prep.

**Month 19 — Apr 2028**
- M: If independent-consulting prep: entity formation research (LLC vs. S-corp), E&O insurance quotes, accountant interviews.
- M: Review Boeing outside-work policy again with new specifics.

**Month 20 — May 2028**
- M: Build a pricing model draft (hourly, project, retainer).
- M: Draft an MSA + SOW template. Have an attorney review before use.

**Month 21 — Jun 2028**
- M: Quarterly checkpoint. Decide: pilot a very small, policy-compliant engagement if possible, or defer.

### Phase 5 — Market validation & independence prep (Months 22–24, Jul–Sep 2028)

**Month 22 — Jul 2028**
- M: Identify 10 realistic prospective clients in your specialty.
- M: Pipeline-building actions: conference talk, podcast guest, specialty blog traction.

**Month 23 — Aug 2028**
- M: If financial readiness check passes (6 months living expenses + health insurance plan + spouse/family alignment), consider transition timeline.

**Month 24 — Sep 2028**
- M: Final 24-month review; set the next 24-month plan (independent, or Director track).

### 8.1 Weekly time budget and resilience

- Default: Mon 2h degree · Wed 2h CPTS · Fri 2h portfolio · Sat 3h labs · Sun 2–3h review.
- If work intensifies: drop portfolio Friday and Sun review first; keep CPTS and Sat labs.
- If falling behind >2 weeks on CPTS: cut stretch items, defer PortSwigger side-tracks, hold the plan rather than add hours and burn out.

---

## 9. Quarterly Milestones and Decision Gates

| Checkpoint | Measurable outcomes | Decision gate |
|---|---|---|
| **Q1 (Dec 2026)** | Resume v2; 6 CPTS modules; 2 engagement-style writeups; numnum presentable | Continue CPTS vs. accelerate OSCP? Default: continue CPTS. |
| **Q2 (Mar 2027)** | 10+ CPTS modules; AWS baseline; one aerospace-angle blog post | External apply now, or wait for CPTS? Default: wait. |
| **Q3 (Jun 2027)** | CPTS passed; numnum v1.0; first conference submission | OSCP next, or defer? Default: OSCP next unless offer in hand. |
| **Q4 (Sep 2027)** | OSCP passed; 3–5 external interviews completed | Accept external offer, leverage internally, or stay? Decide based on live comp data. |
| **Q5 (Dec 2027)** | At least one engagement owned end-to-end; mentoring documented; CRTO decision | CRTO yes/no based on red-team interest + budget. |
| **Q6 (Mar 2028)** | Methodology doc, SOW/test-plan templates, specialty content library ≥6 pieces | Principal internal, Principal external, or indie prep? |
| **Q7 (Jun 2028)** | Pricing model, MSA/SOW, insurance quotes, financial readiness check | Pilot small engagement vs. defer. |
| **Q8 (Sep 2028)** | 10 prospect targets, pipeline activity, 24-month next plan | Launch, Director track, or hold. |

**Hard "no-go" signals for independent transition:**
- <3 months living expenses in reserve.
- No E&O insurance quoted <$5k/yr.
- Boeing / employer policy conflict unresolved.
- No referral or pipeline evidence beyond cold outreach.
- Spouse/family not aligned on income volatility.

---

## 10. Independent Consulting and Boutique Firm Transition Strategy

### 10.1 Pre-launch checklist (before earning a single dollar)

1. Written confirmation that outside work is permissible under Boeing policy, or you have left Boeing.
2. Entity formed (WA LLC is default; S-corp election considered once revenue > ~$80k/yr).
3. Separate business bank account and bookkeeping (QuickBooks or Wave).
4. E&O insurance ($1M–$2M), general liability, cyber liability.
5. Accountant engaged; quarterly estimated tax plan.
6. Written MSA + SOW templates reviewed by an attorney in your state.
7. Scope boundary document: what work you will and will not take (e.g., no Boeing competitors; no clients that overlap your W-2 responsibilities).
8. Health insurance plan (ACA, spouse plan, or AHP) and 6 months expense reserve.

### 10.2 Service offerings (candidate list)

- **Aerospace / embedded product security assessments** — your defensible niche.
- **Web + API penetration testing** — commodity but useful for pipeline.
- **Security test procedure authorship for regulated products** — leverages your Boeing scope work.
- **Pentester mentoring / assessment program advisory** — fractional-leader model, high margin.

### 10.3 Pricing

- Hourly: start $200–$250; move to $275–$350 once pipeline supports it.
- Project: estimate hours × rate × 1.2 risk padding.
- Retainer: a fractional-advisor retainer at 10–20 hrs/mo, 6-month minimum, is the most income-stable form.

### 10.4 Boutique firm — don't rush

Delay firm formation until:
- 12+ months of consistent referrals.
- 1+ anchor client with multi-engagement MSA.
- You can describe your defensible niche in a sentence.
- You are turning away work you want to keep but can't fit.

**Risk framing:** The failure mode is not "the firm goes under." It is "you spent 2 years running a firm when you could have been a $320k Principal with no payroll stress." Only form a firm when you have evidence the lifestyle is both achievable and preferable.

---

## 11. Research Sources and References

Market and compensation ranges in §3 synthesize the following source categories as of 2025–2026. **Verify specifics at search time; URLs rotate.**

- Bureau of Labor Statistics, OEWS 15-1212 Information Security Analysts — Seattle-Bellevue-Tacoma MSA and national — https://www.bls.gov/oes/current/oes151212.htm
- Boeing careers: https://jobs.boeing.com — search "cybersecurity," "penetration test," "product security."
- Bishop Fox careers: https://bishopfox.com/careers
- NetSPI careers: https://www.netspi.com/careers/
- IOActive careers: https://ioactive.com/careers/
- Leidos careers: https://careers.leidos.com — filter "penetration" / "offensive."
- Booz Allen Hamilton careers: https://careers.boozallen.com
- Levels.fyi — "Security Engineer" / "Penetration Tester" filters.
- Mondo 2025 Tech Salary Guide (recruiter report).
- Robert Half 2025 Technology Salary Guide.
- Hays US 2025 Cyber Salary report.
- OffSec pricing: https://www.offsec.com/pricing/
- HTB Academy / CPTS: https://academy.hackthebox.com/
- Zero-Point Security CRTO: https://training.zeropointsecurity.co.uk/
- OWASP API Security Top 10 (2023): https://owasp.org/API-Security/

**Caveat:** No source cited in this document was fetched at the moment of writing; this is a plan, not a market report. Before you negotiate or publish numbers, pull 3+ live postings per role and recompute the 25/50/75 percentiles.

---

## 12. Outstanding Questions and Items Requiring Verification

Resolve these before external resume submission or any public portfolio push:

1. Bachelor's degree — exact title, institution, year, completion status. Second attempt — institution and expected date.
2. GIAC GPEN/GCIH/GSEC/GFACT — current active vs. expired; renewal dates and plan.
3. Clearance level and current status.
4. Exact Boeing titles and dates per HR records.
5. Permission from Boeing to list program names (P-8, KC-46, AWACS, C-17) on an external resume. Many defense employers require either paraphrasing ("defense training and simulation systems") or specific wording approval.
6. Scope metrics for Boeing engagements (team size, systems/programs, # of test procedures). Even order-of-magnitude numbers strengthen bullets without inventing anything.
7. "numnum" project — explicit confirmation no Boeing-proprietary code, data, methodology, or program-specific logic is included.
8. Side-work / outside-employment / IP policy — Boeing specifics required before any paid independent work.
9. Family / financial readiness assumptions — months of expense reserve, spouse income, health insurance options.
10. Appetite for red team operator work vs. assessment work — governs CRTO/OSEP decision gates in Q5–Q6.

---

_End of document. Update after each quarterly checkpoint. Keep this file version-controlled._
