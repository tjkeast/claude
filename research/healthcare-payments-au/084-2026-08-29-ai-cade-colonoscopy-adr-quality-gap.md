# AI-Assisted Colonoscopy and the ADR Quality Gap: Can Technology Solve What Governance Cannot?

**Report 084 — 2026-08-29**

**Summary:** Computer-aided detection (CADe) systems for colonoscopy improve adenoma detection rates by approximately 20% in randomised controlled trials — but real-world gains are far smaller, Australia has no dedicated MBS funding for the technology, and a landmark 2025 Lancet study found that continuous AI exposure actually deskills endoscopists when AI is removed. The technology holds genuine promise for equalising quality across the endoscopist skill spectrum, but cannot substitute for the governance reforms documented in Report 083.

**Why this follows from yesterday:** Report 083 established that Australia cannot report colonoscopy quality nationally because adenoma detection rate (ADR) data is absent from the National Cancer Screening Register — histopathology form return is required but not mandated, and no legal enforcement mechanism exists. This report examines the frequently-raised counter-argument: whether AI-powered detection technology might neutralise the consequences of poor ADR before the governance problem is solved.

---

## Background: What CADe Systems Do

Computer-aided detection (CADe) systems use convolutional neural networks trained on large colonoscopy image datasets to identify suspicious mucosal lesions in real time during colonoscopy, producing a visual alert — typically a green bounding box — on the endoscopist's monitor. The system works continuously during the withdrawal phase, flagging candidate polyps as the colonoscope is slowly withdrawn through the colon. It does not remove polyps, perform any characterisation, or generate any report — it is a second set of eyes, designed to prompt the endoscopist to inspect areas they might otherwise pass over.

Three major commercial systems are currently available in Australia via TGA registration: **GI Genius** (Medtronic), **CAD EYE** (Fujifilm), and **Endo-AID** (Olympus). A 2025 network meta-analysis ranking these and two Asian-market systems (EndoAngel, EndoScreener) found modest differences in efficacy: Endo-AID showed the highest ADR improvement (OR 1.64 vs conventional colonoscopy), followed by CAD EYE (OR 1.46) and GI Genius (OR 1.45). All three showed statistically significant ADR improvement over conventional colonoscopy in controlled trial settings.

---

## Key Findings

### 1. RCT Evidence: Real, Significant, But Narrowly Applicable

The evidence base from randomised controlled trials is robust. A comprehensive systematic review and meta-analysis incorporating prospective RCT data demonstrates:

- **~20% improvement in ADR** with CADe vs conventional colonoscopy
- **50–55% reduction in adenoma miss rate** — from approximately 26% to 13%
- Pooled RCT ADR: **44.0% (CADe) vs 35.9% (conventional)** — an absolute difference of 8.1 percentage points

These figures reflect conditions in academic and high-volume referral centres where the trials were predominantly conducted. The clinical logic is compelling: a system that reliably flags mucosal lesions provides the most benefit precisely where those lesions would otherwise be missed — by lower-performing endoscopists working under the cognitive and time pressures of routine practice.

### 2. The Real-World Gap: A Near-Null Effect in Observational Settings

The transition from RCT to clinical practice has revealed a striking attenuation of effect. When restricting analysis to observational studies of CADe in routine clinical environments, the pooled ADR improvement shrinks dramatically:

- **Observational studies pooled ADR: 36.3% (CADe) vs 35.8% (conventional)**

An absolute difference of 0.5 percentage points is clinically negligible. Several mechanisms explain the gap. In RCTs, endoscopists often alter their withdrawal behaviour when they know CADe is active — slowing down, examining flagged lesions more carefully. In routine practice, where CADe is simply always on, the alerting becomes background noise. Experienced endoscopists — who constitute the majority of practitioners in high-volume centres where CADe has been deployed — show **no consistent ADR improvement** in real-world studies; some show a trend toward decreased ADR, possibly reflecting anchor effects (looking only where the AI flags). The greatest real-world gains appear in settings with lower baseline ADR, which tend to be lower-volume community and regional centres — precisely the settings where CADe hardware is least likely to be installed.

### 3. The Australian Real-World Experience: A Tertiary Centre With Skilled Operators

The first published Australian real-world CADe study (published January 2026, PMC) examined outcomes at a single tertiary Australian centre after introduction of the Olympus Endo-AID® CADe module in July 2023, made available for all elective procedures. The study found:

- Partial CADe use (50–99% of procedures) significantly improved ADR compared to no use
- High-frequency users (>99% CADe use) maintained high ADR; total adenomas per colonoscopy increased — capturing more sessile serrated lesions (SSLs) than conventional colonoscopy
- The centre was a **tertiary referral hospital with a high-volume skilled endoscopy service**, not a community or rural setting

These findings are encouraging for technology adoption but do not resolve the core equity question: this centre is exactly the kind of facility where ADR is already high. The NBCSP quality problem — documented in Report 083 — is concentrated in community, rural, and private-room settings where histopathology data is most absent and where CADe hardware is least available.

### 4. Community Practice Null Results Confirm the Access Paradox

A 2025 pragmatic RCT in a Japanese community hospital setting found **no statistically significant improvement in ADR** from CADe, attributed to the already-high baseline ADR of the control group (well above the national benchmark). A commentary by Hassan and colleagues in *Digestive Endoscopy* (2025) on null community-practice CADe results draws the critical inference: "Rigorous trials need to include operators and sites with genuine room for improvement; otherwise, null results tell us more about participant selection than about device efficacy."

This is the access paradox. CADe improves detection most where baseline ADR is lowest. But CADe adoption is concentrated where baseline ADR is already high. The intervention flows to the least-needed sites.

### 5. The Deskilling Signal: AI May Reduce Unaided Performance

The most consequential finding for NBCSP policy emerged from a 2025 *Lancet Gastroenterology & Hepatology* multicentre observational study (Budzyń et al.) — the first real-world evidence of AI-induced deskilling linked to patient outcomes in clinical medicine. The study, conducted across four Polish endoscopy centres participating in the ACCEPT trial (AI introduced late 2021), found:

- **ADR for colonoscopies conducted WITHOUT AI assistance fell by 6.0 percentage points** after AI was introduced
- Unassisted ADR dropped from **28% to 22%** following regular exposure to AI-assisted colonoscopy
- Endoscopists became habituated to AI alerts and degraded in independent polyp recognition

The implications for Australian endoscopy are significant. The NBCSP relies on colonoscopy services distributed across geographically diverse, differentially-resourced settings. If CADe is deployed in metropolitan referral centres, endoscopists at those centres may become deskilled in unaided detection — a risk that would emerge whenever the technology is unavailable (equipment failure, infrastructure outages in regional or remote deployments, or procedures performed at facilities without the module). The technology creates a dependency structure that is poorly suited to the uneven infrastructure landscape of the Australian healthcare system.

### 6. False Positives, Polypectomy Cascade, and Surveillance Overload

CADe systems generate false positive alerts — flagging non-neoplastic tissue (normal mucosa, residual stool, angioectasias) as potential polyps. Systems differ substantially in false positive rate: a 2024 comparative study found FP rates of 3.2% vs 0.6% across two leading systems, with the higher-FP system paradoxically showing lower net ADR improvement, likely because noise in the alerting signal reduces endoscopist responsiveness to genuine alerts.

Even true positive alerts create a downstream cost challenge. Every additional adenoma detected by CADe requires either polypectomy (with associated complication risks, theatre time, and consumable costs) or a surveillance interval assignment. An increase in adenoma detection rates — even genuine ones — **increases the demand for surveillance colonoscopy** at 3-year or 5-year intervals. Australia already has a documented shortfall of approximately 50,000 colonoscopy procedures per year (Report 080). Increasing the number of surveillance participants through CADe-enhanced detection without simultaneously expanding colonoscopy capacity would extend waiting lists further, potentially negating the clinical benefit by delaying surveillance colonoscopies beyond therapeutically safe intervals.

### 7. No MBS Funding for CADe Technology: An Unrecognised Cost

There is no dedicated MBS item number for AI-assisted colonoscopy in Australia. The colonoscopy MBS items introduced in March 2021 (items 32222–32228, the indication-specific framework replacing items 32090/32093) fund the procedure based on clinical indication and complexity — not the technology used to perform it. The AI module is a device cost borne by the health service organisation or endoscopy practice.

A dedicated CADe module carries purchase or lease costs — typically in the range of USD 4,000–10,000 per annum per module in comparable international markets — plus maintenance, software licensing, and integration costs. Public hospital endoscopy units operating under block-funded budgets face pressure to absorb this cost without any MBS return. Private gastroenterologists in rooms-based practice have no billing mechanism to recoup it from insurers or patients. The absence of a reimbursement pathway means adoption is driven by institutional procurement decisions and philanthropic capital investment rather than by clinical evidence or screening program priorities.

No MSAC (Medical Services Advisory Committee) assessment for CADe in colonoscopy has been published as of this report. An MSAC assessment would be the standard pathway for any MBS listing. The absence of an assessment in progress suggests that the question of whether Australia should fund CADe through the MBS has not been formally put to government. Given the mixed real-world evidence and the absence of an Australian cost-effectiveness model, the pathway to funding is long.

---

## Tensions and Open Questions

### Tension 1: Technology as Proxy for Governance Reform

The strongest argument against investing heavily in CADe technology as an NBCSP quality strategy is that it addresses the symptom (variable ADR) rather than the cause (no accountability for ADR). If Australia were to mandate NCSR histopathology data submission, endoscopist-level ADR monitoring would become possible, low performers would be identified, improvement programmes could be directed, and accountability would follow. CADe, by contrast, would improve aggregate ADR — slightly, in real-world settings — without identifying or remediating the low performers who most need intervention.

### Tension 2: Technology Equity vs. Healthcare Equity

The sites most in need of quality improvement — rural, regional, lower-volume community endoscopy services — are the least likely to have CADe technology. The First Nations population faces the highest interval cancer rates (NT rate 8.4 per 10,000, vs national 6.3). Deploying CADe in metropolitan private hospitals does not address this population. Funding it at the MBS level without a community access requirement risks deepening existing inequity rather than narrowing it.

### Tension 3: The Deskilling Dependency Trap

Deploying AI in a healthcare system that cannot guarantee continuity of AI access — due to geography, funding, equipment, or connectivity — creates a dependency trap. If broad CADe adoption reduces unaided endoscopist performance (as the Budzyń 2025 study suggests is occurring), the system would be trading improved average performance for increased vulnerability: a technology outage at a rural centre would now affect a deskilled endoscopist, not an experienced one. The NBCSP cannot afford to create fragile dependencies in its most resource-constrained delivery contexts.

### Tension 4: How CADe Data Should Feed Quality Monitoring

CADe systems generate real-time data about each colonoscopy: when the AI fires, whether the alert was actioned, which lesions were found. This data is held by the device vendors, not the NCSR. If CADe were integrated into colonoscopy clinical workflows and linked to NCSR data submission — so that each AI-assisted colonoscopy automatically populated the quality indicators the NCSR is currently missing — CADe could solve both the detection problem and the data problem simultaneously. This would require: (a) regulatory mandating of NCSR data linkage for AI modules operating in the NBCSP context; (b) FHIR interface development between CADe platforms and the NCSR; and (c) a reimbursement model that incentivises adoption in lower-volume settings. None of these exist.

---

## Threads to Branch Into Next

1. **Stool DNA and multi-target colorectal screening: supplementing iFOBT for high-risk groups.** Australia's iFOBT has limited sensitivity for right-sided and serrated lesions — the lesion types that generate the most interval cancers. Combined FIT/stool-DNA tests (as in the US Cologuard model) improve proximal cancer detection but generate more false positives and cost more per test. The case for a high-risk supplemental pathway in the NBCSP.

2. **CT colonography as a colonoscopy alternative: the MBS funding gap.** CT colonography (virtual colonoscopy) detects polyps ≥6mm with sensitivity approaching optical colonoscopy, requires no sedation, and could absorb some of the NBCSP colonoscopy capacity shortfall — but is not funded by MBS for routine NBCSP follow-up. A funding reform analysis.

3. **Colorectal cancer screening equity for First Nations Australians.** The Northern Territory's interval cancer rate of 8.4 per 10,000 is the highest in Australia. First Nations Australians face lower NBCSP participation, lower colonoscopy follow-up rates, and the most severe NCSR data quality gaps. A dedicated equity analysis.

4. **CADx: computer-aided characterisation for optical biopsy.** The companion to CADe — systems that not only detect polyps but characterise them as neoplastic or non-neoplastic in real time. A validated CADx system could eliminate the need to remove and send small polyps to pathology (the "resect-and-discard" strategy), reducing polypectomy burden and pathology costs. No MBS framework exists for this either.

5. **Post-colonoscopy surveillance interval AI: risk stratification for follow-up scheduling.** Large language models and risk stratification tools are being developed to assign surveillance intervals based on polyp characteristics. This addresses the downstream burden of CADe-enhanced detection: more adenomas found → more surveillance patients to schedule → AI to prioritise who waits 3 years vs 5 years vs 10 years.

---

## Sources

- PMC. *Availability and use of computer-aided detection during colonoscopy: A real-world observational study at an Australian tertiary center.* Published January 2026. https://pmc.ncbi.nlm.nih.gov/articles/PMC12865384/
- Onlinelibrary Wiley. *Null Effect of Computer-Aided Detection in Colonoscopy: News or Illusion?* Hassan C et al. Digestive Endoscopy, 2025. https://onlinelibrary.wiley.com/doi/10.1111/den.70023
- Onlinelibrary Wiley. *Effect of Computer-Aided Detection During Colonoscopy on Adenoma Detection Rate in a Community Hospital Setting: Randomized Controlled Trial.* Yabuuchi et al. Digestive Endoscopy, 2025. https://onlinelibrary.wiley.com/doi/10.1111/den.15086
- Lancet Gastroenterology & Hepatology. *Endoscopist deskilling risk after exposure to artificial intelligence in colonoscopy: a multicentre, observational study.* Budzyń et al., 2025. https://www.thelancet.com/journals/langas/article/PIIS2468-1253(25)00290-0/abstract
- Lancet Gastroenterology & Hepatology. *Endoscopist deskilling: an unintended consequence of AI-assisted colonoscopy?* 2025. https://www.thelancet.com/journals/langas/article/PIIS2468-1253(25)00164-5/abstract
- Nature Reviews Gastroenterology & Hepatology. *AI-assisted colonoscopy and risk of endoscopist deskilling.* 2025. https://www.nature.com/articles/s41575-025-01122-3
- Gastrointestinal Endoscopy. *Use of artificial intelligence improves colonoscopy performance in adenoma detection: a systematic review and meta-analysis.* https://www.giejournal.org/article/S0016-5107(24)03471-0/fulltext
- JGH Open (Wiley). *Artificial Intelligence–Driven Colonoscopy: A Systematic Review and Network Meta-Analysis on System Performance for Colorectal Neoplasia Detection.* 2026. https://onlinelibrary.wiley.com/doi/full/10.1002/jgh3.70372
- PMC (Comparative). *Comparative Performance of AI-Based CADe Systems for Colorectal Polyps: A Systematic Review and Network Meta-Analysis.* https://pmc.ncbi.nlm.nih.gov/articles/PMC13033948/
- Nature npj Digital Medicine. *A prospective comparison of two computer aided detection systems with different false positive rates in colonoscopy.* 2024. https://www.nature.com/articles/s41746-024-01334-y
- Lancet Digital Health. *Cost-effectiveness of artificial intelligence for screening colonoscopy: a modelling study.* 2022. https://www.thelancet.com/journals/landig/article/PIIS2589-7500(22)00042-5/fulltext
- Journal of the Canadian Association of Gastroenterology. *Cost-effectiveness of Artificial Intelligence-Aided Colonoscopy for Adenoma Detection in Colon Cancer Screening.* 2023. https://academic.oup.com/jcag/article/6/3/97/7110912
- American College of Gastroenterology. *Artificial intelligence in colonoscopy: Could it be making us worse?* Zhou, eBGI, September 2025. https://gi.org/journals-publications/ebgi/zhou_sep2025/
- Australian Commission on Safety and Quality in Health Care. *Colonoscopy Clinical Care Standard 2025.* https://safetyandquality.gov.au/standards/clinical-care-standards/colonoscopy-clinical-care-standard
- Safer Care Victoria. *Promoting Best Practice Colonoscopy — Recommendations Report.* March 2025. https://www.safercare.vic.gov.au/sites/default/files/2024-10/Promoting%20best%20practice%20colonoscopy%20recommendations%20report.pdf
- Arxiv / research. *Toward a Human-Centered AI-assisted Colonoscopy System in Australia.* March 2025. https://arxiv.org/pdf/2503.20790
- MBS Online. *Changes to MBS Colonoscopy items factsheet.* https://www.mbsonline.gov.au/internet/mbsonline/publishing.nsf/Content/Factsheet-Colonoscopy-March-21
- OAE Publishing. *Artificial intelligence for post-polypectomy surveillance: a scoping review of emerging tools in colorectal cancer prevention.* 2025. https://www.oaepublish.com/articles/ais.2025.65
