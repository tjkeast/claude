# The NCSR Data Governance Gap: Why Australia Cannot Report Colonoscopy Quality Nationally

**Report 083 — 2026-08-28**

**Summary:** The National Cancer Screening Register (NCSR), built at a cost of more than $220 million and operated by Telstra Health, is the central infrastructure through which Australia's colonoscopy quality data should flow. It is not flowing. Three of the most important quality performance indicators for the National Bowel Cancer Screening Program — adenoma detection rate (ADR), positive predictive value for adenoma detection, and cancer stage distribution — have not been reported nationally for years, because histopathology form return by individual clinicians is required but not legally mandated. The result is that Australia cannot systematically identify underperforming endoscopists, cannot measure whether quality improvement is occurring, and cannot link procedure quality to interval cancer outcomes at a population level. The September 2025 Colonoscopy Clinical Care Standard and new FHIR-based software integrations are pushing toward better compliance — but the structural gap between "required" and "mandatory" remains unresolved.

**Why this follows from yesterday:** Report 082 documented that Australia's interval cancer rate is 6.3 per 10,000 negative-screen participants — but that the surveillance framework cannot explain why, because the ADR data that would identify poorly performing endoscopists is not available from the NCSR. This report examines the underlying governance architecture that produces that absence, and what reform would be needed to close it.

---

## Background: The NCSR's Origins and Purpose

The National Cancer Screening Register was established in 2016 under a contract awarded to Telstra Health (initially valued at $178.3 million, subsequently expanded to over $220 million). It replaced the existing national cervical screening register and incorporated the nascent bowel screening data infrastructure, with the ambition of creating a single, comprehensive digital register linking GPs, colonoscopists, pathologists, radiologists, and the Commonwealth Government.

The legislative framework is the *National Cancer Screening Register Act 2016* (Cth), which governs collection, use, and disclosure of information held in the register. Under the Act, the Commonwealth retains data ownership; Telstra Health operates the register as a contracted service provider.

The NCSR's intended function for the bowel cancer screening program was comprehensive: capturing iFOBT results, tracking colonoscopy follow-up after positive screens, recording histopathology results from colonoscopies, and providing the data infrastructure for national quality monitoring — including endoscopist-level quality reporting.

The implementation, from the outset, did not meet expectations.

---

## Key Findings

### 1. A Register Built on Voluntary Reporting

The foundational problem is a structural distinction that appears in every AIHW monitoring report but rarely receives dedicated scrutiny: the return of colonoscopy and histopathology forms is **required** in accordance with the Colonoscopy Clinical Care Standard, but is **not mandated** by the NBCSP program rules for individual practitioners.

The consequence flows directly through to quality surveillance. The AIHW's 2025 and 2026 NBCSP Monitoring Reports both state that the following performance indicators are **not reported due to data incompleteness**:

- **PI 5a: Adenoma Detection Rate (ADR)** — the proportion of colonoscopies in which at least one adenoma is found
- **PI 5b: Positive Predictive Value (PPV) of diagnostic assessment for detecting adenoma**
- **PI 8: Cancer clinico-pathological stage distribution** — the staging breakdown of screen-detected cancers

These three indicators are not peripheral. ADR is the single most validated quality predictor of interval cancer risk, with evidence from landmark *New England Journal of Medicine* studies (Kaminski et al., 2010; 2013) establishing that patients of endoscopists in the highest ADR quartile face a four-fold lower interval cancer risk than those of endoscopists in the lowest quartile — and that each 1% increase in ADR is associated with a 3% reduction in interval cancer risk and a 5% reduction in fatal interval cancer risk. PI 8 is how you would measure whether early detection benefits are being realised. Without these two indicators, Australia is running a national cancer screening programme largely blind to its own quality.

The reason they cannot be reported is data: histopathology form return rates are insufficient to support population-level calculation of these indicators. And the reason form return rates are insufficient is that individual clinicians face no legal consequence for not submitting.

### 2. The ANAO Audit: A Register Troubled From the Start

The structural problems of the NCSR are not newly emergent. The Australian National Audit Office (ANAO) examined the register's procurement in a performance audit that found significant governance failures. The Department of Health had signed a $220 million contract with Telstra Health without having finalised how data privacy and security would be managed — a year after contract execution, no official documentation of privacy and security protocols existed. Implementation timelines consistently slipped; the bowel cancer register had no firm go-live date as late as mid-2019. The ANAO found that key objectives had not been met, that the Commonwealth had incurred additional costs, and that value for money outcomes had been compromised.

The immediate public controversy focused on the cervical screening implementation, which had its own well-documented problems. But for the bowel cancer quality surveillance use case, the foundational weakness was the same: a register that struggled to integrate clinical systems, could not compel data submission, and was slower to deploy than the program needed.

### 3. How Data Does (and Does Not) Flow Into the NCSR

The NCSR currently receives colonoscopy and histopathology data through several mechanisms:

**Manual submission.** Colonoscopists and pathologists can complete the NCSR Colonoscopy and Histopathology Report form (updated December 2025) and submit it via the healthcare provider portal, fax, or post. This is the primary channel for the majority of providers who are not yet software-integrated. It is the channel most prone to incomplete return.

**MBS claim data.** The NCSR cross-references Medicare Benefits Schedule (MBS) claim data to identify that a colonoscopy was performed — this confirms the procedure occurred but captures almost nothing about quality. An MBS claim for a colonoscopy (item 32090 or 32093, or the newer indication-specific items 32222–32228) records that a procedure was done and billed, not what was found, removed, or at what quality.

**Participant Follow-Up Function (PFUF) data.** Since 2023, the NBCSP has used PFUF — a system where program officers contact participants who have had a positive screen but for whom no follow-up colonoscopy has been recorded — to supplement missing colonoscopy form data. If a PFUF call confirms a colonoscopy occurred, this is recorded in the NCSR. PFUF data can confirm that a procedure occurred; it cannot supply histopathology results.

**Clinical software integration.** The NCSR has developed a FHIR (Fast Healthcare Interoperability Resources) REST API 2.0 to enable direct integration from clinical information systems. EndoVault GI — the first endoscopy software to integrate with the NCSR — now allows colonoscopists to submit patient data directly from within their clinical workflow, removing the need for paper forms or portal entry. A six-month transition period (1 July to 31 December 2025) was established to allow practices not yet integrated to continue sending reports manually while the industry adopted the new pathway.

The software integration pathway is the most promising route to closing the data gap — but it covers only a subset of endoscopy providers, adoption is voluntary, and even full integration does not resolve the underlying question of what happens when a provider chooses not to submit histopathology data.

### 4. The September 2025 Standard: Expectations Without Enforcement

The updated Colonoscopy Clinical Care Standard, released in September 2025, contains nine quality statements governing pre-, intra-, and post-procedure care. Quality Statement 9 — "Reporting and follow-up" — explicitly requires that colonoscopy outcome results, including histopathology results, be shared with the patient, referring GP, and the NCSR.

This is a stronger expectation than previous iterations of the standard. But the Colonoscopy Clinical Care Standard operates within the National Safety and Quality Health Service (NSQHS) Standards framework, which applies to accredited health service organisations rather than individual clinicians. Health service organisations assessed against the NSQHS Standards are required to implement the Clinical Care Standard — but this creates accountability at the organisational level, not at the individual practitioner level.

An endoscopist operating in a public hospital in an accredited health service organisation is subject to organisational policies that should require NCSR reporting — but the failure mechanism is organisational accreditation, not individual professional consequence. A gastroenterologist in private rooms performing colonoscopies in a clinic that is not seeking NSQHS accreditation faces even less structural incentive.

The CCRTGE (Conjoint Committee for the Recognition of Training in Gastrointestinal Endoscopy) credentialling framework requires endoscopists to maintain ADR records as part of certification and recertification — but this is a matter of professional credential maintenance with the relevant colleges, not a matter of national data registry submission with legal force.

### 5. Comparison: How the UK Resolved This Problem

The contrast with the UK NHS Bowel Cancer Screening Programme is instructive. The Joint Advisory Group (JAG) accreditation framework — mandatory for all colonoscopists performing NHS bowel cancer screening — requires each accredited colonoscopist to:

- Commit to a minimum volume of screening colonoscopies (approximately 120 per annum)
- Demonstrate caecal intubation rates ≥90%
- Maintain and submit ADR data, which is monitored against national benchmarks
- Participate in direct observation of procedural skills (DOPS) assessments

JAG accreditation is a condition of participation in NHS bowel cancer screening. Colonoscopists who cannot demonstrate meeting quality thresholds are removed from screening lists. This creates a direct enforcement pathway: poor ADR is not just a local quality governance matter — it terminates the colonoscopist's participation in the national programme.

Australia has no equivalent mechanism. CCRTGE credentialling is a professional credential for maintaining one's license to perform colonoscopy — it is not a condition of participation in NBCSP follow-up colonoscopy service delivery. A colonoscopist who has never submitted a single histopathology form to the NCSR can continue to receive NBCSP referrals and to bill the MBS for NBCSP-related colonoscopies.

### 6. The Economic Argument for a Mandatory Data System

The case for resolving the NCSR data gap has a payment system logic as well as a quality logic. The NBCSP is funded by the Commonwealth at approximately $42 million per year in direct program costs, with colonoscopy follow-up funded through the MBS at approximately $2,000 per procedure (or public hospital costs for those without private insurance). The interval cancer rate of 6.3 per 10,000 generates a stream of late-stage cancer diagnoses whose treatment costs the system dramatically more than prevention.

Report 079 established that stage I colorectal cancer costs approximately $37,000 to treat, while stage IV costs approximately $282,000 — a ratio of approximately 8:1. Every interval cancer that could have been prevented by detecting the precursor at an adequately-quality colonoscopy represents a net cost to the public system of at least $245,000 above the stage I comparator. If Australia's interval cancer rate of 6.3 per 10,000 reflects in part the consequences of unmonitored low-ADR endoscopists — as international evidence strongly suggests — then the governance failure of the NCSR data system is not merely a measurement problem. It is a cost driver.

Implementing a binding data submission requirement, combined with endoscopist-level ADR reporting and a minimum performance threshold tied to NBCSP participation rights, would create an accountability mechanism whose downstream savings in avoided interval cancer treatment costs would almost certainly exceed the system costs of compliance.

---

## Tensions and Open Questions

### Tension 1: "Required" Versus "Mandatory" — The Legal Gap

The current position is that form return is "required" under the Colonoscopy Clinical Care Standard but not "mandated" by the NBCSP. Closing this gap would require one of three mechanisms: (a) legislative amendment to the NCSR Act or the relevant Health Insurance Act provisions to create a legal duty to submit data; (b) amending MBS billing rules so that NBCSP-related colonoscopy items are conditional on NCSR data submission (a provider number condition); or (c) incorporating NCSR data submission as a condition of NBCSP participation, such that colonoscopists who fail to submit data are removed from the NBCSP referral pathway. Option (c) mirrors the UK JAG model and requires the least legislative change, but faces strong opposition from the gastroenterology college community, which tends to resist mandatory participation models.

### Tension 2: Privacy Architecture vs. Disclosure Requirements

The NCSR Act creates a privacy framework governing disclosure of data — including endoscopist-identified quality data. Endoscopist-level ADR reporting, if published, would effectively name individuals against a quality metric. The clinical college position has historically been that quality data should be available only for internal peer review, not public reporting. The UK JAG model does not publish individual endoscopist ADR data publicly either — it uses the data for programme management and to remove low performers. Whether Australian governance culture could accept even this limited use of individual endoscopist performance data — without public disclosure — is untested.

### Tension 3: Infrastructure Uneven Across Jurisdictions and Settings

The FHIR API integration that allows automated NCSR submission via EndoVault covers a growing but still incomplete share of colonoscopy providers. Public hospital endoscopy units, private hospitals, and community-based rooms face very different IT infrastructure and budget environments. A mandatory submission requirement that is technically impossible for some providers — those without compatible clinical software and without resources to implement it — would create a compliance burden that falls unequally on smaller, rural, and regional services, which are precisely the services where quality data is most absent and most needed.

### Tension 4: The Chicken-and-Egg of Data Quality Reform

Improving the NCSR's data quality requires colonoscopists to trust that submitting data will not expose them to adverse credentialling consequences for a performance metric they have not previously been required to demonstrate. But building that trust requires demonstrating that the data system is functioning, that quality improvement support is available, and that the regulatory response to poor ADR will be remediation rather than punishment. The UK took approximately a decade from the launch of its bowel cancer screening programme (2006) to establish a mature ADR accountability system. Australia is running behind a comparable timeline from its own programme's expansion (2019–).

---

## Threads to Branch Into Next

1. **AI-assisted colonoscopy and its impact on ADR: is technology solving the quality problem before governance can?** Computer-aided detection (CADe) systems demonstrated in 2025 trials a statistically significant improvement in ADR without affecting overall polyp detection rate, suggesting AI may equalise quality between high- and low-performing endoscopists. The MBS funding question for these systems and their potential to transform the NBCSP quality debate.

2. **Stool DNA testing and multi-target approaches: supplementing iFOBT for high-risk subgroups.** The iFOBT has inherent sensitivity limits for right-sided and serrated lesions. Combined FIT/DNA stool tests (as in the US Cologuard model) detect more proximal lesions but generate more false positives and cost more. The case for a high-risk supplemental pathway in Australia.

3. **CT colonography as a colonoscopy alternative: the MBS funding gap.** CT colonography detects lesions ≥6mm with sensitivity approaching optical colonoscopy, can be performed without sedation, and could absorb some of the colonoscopy capacity shortfall — but is not funded by MBS for routine NBCSP follow-up. A funding reform analysis.

4. **Colorectal cancer screening equity for First Nations Australians: the NT interval cancer rate and NCSR data gaps.** The Northern Territory's interval cancer rate of 8.4 per 10,000 is the highest in Australia. First Nations Australians face lower NBCSP participation and lower colonoscopy follow-up rates — and the data quality problem in remote-area colonoscopy services is the most acute in the country.

5. **MBS billing as a data collection mechanism: provider number conditions and healthcare payment reform.** The mechanism most capable of creating binding NCSR submission — conditional MBS billing — is used in other areas of Australian health policy (e.g., pathology). What would it cost to implement, what would it miss, and who would resist?

---

## Sources

- AIHW. *National Bowel Cancer Screening Program Monitoring Report 2025 — Latest NBCSP Performance Indicator Results.* https://www.aihw.gov.au/reports/cancer-screening/nbcsp-monitoring-2025/contents/data-at-a-glance/latest-nbcsp-performance-indicator-results
- AIHW. *National Bowel Cancer Screening Program Monitoring Report 2026 — Latest NBCSP Performance Indicator Results.* https://www.aihw.gov.au/reports/cancer-screening/nbcsp-monitoring-2026/contents/data-at-a-glance/latest-results
- AIHW. *National Bowel Cancer Screening Program Monitoring Report 2025 — Performance of the screening program.* https://www.aihw.gov.au/reports/cancer-screening/nbcsp-monitoring-2025/contents/performance-of-the-screening-program
- AIHW. *National Bowel Cancer Screening Program Monitoring Report 2025 — Diagnosis.* https://www.aihw.gov.au/reports/cancer-screening/nbcsp-monitoring-2025/contents/performance-of-the-screening-program/diagnosis
- Australian Commission on Safety and Quality in Health Care. *Colonoscopy Clinical Care Standard 2025.* Released September 2025. https://www.safetyandquality.gov.au/resources/colonoscopy-clinical-care-standard-2025
- Australian Commission on Safety and Quality in Health Care. *Reporting and Follow-up — Colonoscopy Clinical Care Standard.* https://www.safetyandquality.gov.au/standards/clinical-care-standards/colonoscopy-clinical-care-standard/quality-statements-scope-and-goal/reporting-and-follow
- NCSR. *Colonoscopy and Histopathology Report (NBCSP_GCH_25).* Updated December 2025. https://www.ncsr.gov.au/content/dam/ncsr/forms/Bowel-screening-colonoscopy-and-histopathology-report.pdf
- NCSR. *Quick Start Guide: Colonoscopy & Histopathology.* https://www.ncsr.gov.au/content/dam/ncsr/quick-start-guides/Quick-Start-Guide-Colonoscopy-Histopathology.pdf
- NCSR. *Clinical Software Integration.* https://www.ncsr.gov.au/about-us/how-to-interact-with-the-NCSR/for-healthcare-providers/clinical-software-integration
- NCSR. *EndoVault GI integration announcement.* https://ncsr.gov.au/about-us/news-and-media/EndoVault-is-now-integrated-with-the-NCSR.html
- Cancer NSW. *Participant Follow-Up Function (PFUF) — National Bowel Cancer Screening Program.* https://www.cancer.nsw.gov.au/getmedia/607ce8d6-c84c-4d18-bceb-7d8130c3f1f3/PFUF-FactSheet-Bowel-Program.pdf
- Australian National Audit Office. *Procurement of the National Cancer Screening Register.* https://www.anao.gov.au/work/performance-audit/procurement-national-cancer-screening-register
- iTWire. *Telstra attacked over $220 million cancer screening register contract win.* https://itwire.com/government-tech-news/technology-tenders/73042-telstra-attacked-over-$220-million-cancer-screening-register-contract-win.html
- Computerworld Australia. *Government should consider tearing up Telstra cancer contract: Inquiry.* https://www.computerworld.com.au/article/648425/government-should-consider-tearing-up-telstra-cancer-contract-inquiry
- Kaminski et al. *Quality Indicators for Colonoscopy and the Risk of Interval Cancer.* New England Journal of Medicine. 2010. https://www.nejm.org/doi/full/10.1056/NEJMoa0907667
- Kaminski et al. *Adenoma Detection Rate and Risk of Colorectal Cancer and Death.* New England Journal of Medicine. 2013. https://www.nejm.org/doi/full/10.1056/NEJMoa1309086
- National Cancer Control Indicators. *Colonoscopy follow-up and median time.* https://ncci.canceraustralia.gov.au/screening-and-immunisation/colorectal-screening-test-follow/colonoscopy-follow-and-median-time
- Safercare Victoria. *Promoting Best Practice Colonoscopy — Recommendations Report.* March 2025. https://www.safercare.vic.gov.au/sites/default/files/2024-10/Promoting%20best%20practice%20colonoscopy%20recommendations%20report.pdf
- Joint Advisory Group (JAG). *Accreditation of Screening Colonoscopists Guidelines.* https://www.bcsa.thejag.org.uk/CMS_Documents/Scheme/SAAS/200131-%20Bowel%20Cancer%20Screener%20Accreditation%20Guidelines%20-%20Colonoscopists%20V1.6.pdf
- Gertig et al. *Supporting health care providers in cancer screening: the role of the National Cancer Screening Register.* Medical Journal of Australia. 2023; 219(3). https://www.mja.com.au/journal/2023/219/3/supporting-health-care-providers-cancer-screening-role-national-cancer-screening
- Department of Health and Aged Care. *The role of health professionals in the NBCSP.* https://www.health.gov.au/our-work/national-bowel-cancer-screening-program/managing-bowel-screening-for-participants/the-role-of-health-professionals-in-the-national-bowel-cancer-screening-program
