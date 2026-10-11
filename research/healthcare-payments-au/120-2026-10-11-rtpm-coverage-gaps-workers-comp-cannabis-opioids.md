# Real-Time Prescription Monitoring in Australia: National Architecture, Coverage Gaps, and the Populations Falling Through

**One-line summary:** Australia has achieved a nationally connected real-time prescription monitoring (RTPM) system across all eight jurisdictions by 2024, but three structural gaps — workers' compensation-funded opioids, medicinal cannabis under the Special Access Scheme, and non-mandatory prescriber checking — mean that millions of high-risk prescriptions are either invisible to the system or inadequately scrutinised.

**Why this follows from yesterday:** Report 119 documented that workers' compensation-funded opioids are invisible to the PBS pharmacovigilance architecture and outside the Real-Time Prescription Monitoring (RTPM) system — a commercial driver prescribed opioids by their treating GP under a workers' comp claim is effectively unmonitored by the national safety net. Today's report examines the full scope of that problem: how RTPM works nationally, where its coverage ends, and which patient populations fall into the gaps.

---

## Background

Australia's prescription opioid and monitored-medicine problem is worsening despite a decade of monitoring investment. The Penington Institute's 2026 Annual Overdose Report (covering 2024 data) recorded 2,596 drug-induced deaths — the highest level ever recorded in the 24-year dataset. Opioids were involved in 1,083 of those deaths, making them the single largest drug class implicated. This occurred despite the national rollout of RTPM technology across every state and territory.

Real-Time Prescription Monitoring systems are designed to prevent doctor-shopping — patients obtaining overlapping or dangerous prescriptions from multiple prescribers and pharmacies — by giving prescribers and pharmacists a real-time view of a patient's dispensing history for high-risk medicines before writing or supplying them. The concept is straightforward; the implementation is a federated patchwork of state systems, each with different mandate levels, medicine lists, and data-sharing arrangements.

Understanding where RTPM works, and where it does not, is essential to understanding why Australia's opioid death toll continues to rise even as the monitoring infrastructure matures.

---

## Key Findings

### 1. The National Architecture: Eight Systems, One National Data Exchange

Australia operates eight separate RTPM systems — one per jurisdiction — all built by the same vendor (Fred IT Group) and all connected to a National Data Exchange (NDE) operated under the Australian Digital Health Agency's coordination:

| Jurisdiction | System Name | Key Characteristics |
|---|---|---|
| Victoria | SafeScript | Mandatory checking since 1 April 2020; earliest comprehensive system |
| New South Wales | SafeScript NSW | Deployed, but checking is **not mandatory** for prescribers |
| Queensland | QScript | Mandatory dispensing data upload; no mandatory prescriber checking |
| South Australia | ScriptCheckSA | Operational; similar structure to QScript |
| Western Australia | ScriptCheckWA | Went live March 2023 |
| ACT | Canberra Script | Connected to NDE; part of national 2022 rollout cohort |
| Northern Territory | NTScript | Operational |
| Tasmania | TasScript | **Final jurisdiction to join**, went live approximately May 2024 |

The NDE enables cross-jurisdiction data sharing: a patient who fills a prescription in Queensland can have that dispensing visible to a prescriber checking in Victoria. All eight systems share the same underlying Fred IT technology stack, making interoperability technically consistent.

The Intergovernmental Agreement on National Digital Health 2023–2027 lists RTPM as a strategic priority project. The Australian Digital Health Agency's 2024–25 annual report noted that RTPM priorities included "transition and embedding the revised contractual framework into day-to-day operations" and a "Data Quality Remediation Plan," signals that system maturity is still being established rather than achieved.

### 2. Evidence of Effectiveness — and Its Limits

The most rigorous evaluation of Australia's RTPM systems to date is a 2024–25 Monash University study published in the Medical Journal of Australia, covering the Victorian SafeScript system. The study analysed over 6.7 million prescriptions for more than 810,000 patients across 562 general practices in Victoria between 2017 and 2023 — spanning the pre-implementation, voluntary, and mandatory phases.

**Key findings:**
- "Multiple-prescriber episodes" (patients receiving monitored medicines from four or more prescribers within a defined period) fell from **15.73 per 1,000 people to 12.6 per 1,000** following SafeScript's launch — approximately a **15% reduction** in the doctor-shopping proxy measure.
- The largest reductions occurred during the **voluntary phase** (April 2019 to April 2020), with relatively modest additional reductions after the system became mandatory.

**Important caveats:**
- "Multiple prescriber episodes" is a proxy measure for doctor-shopping, not a direct measure of opioid-related harm, overdose, or death. The study did not demonstrate that opioid volumes fell, that prescribed opioid deaths declined, or that patients diverted from doctor-shopping did not shift to illicit supply.
- Critics noted that the observed effect may partly reflect low-risk prescribers and patients changing behaviour, rather than identifying and disrupting high-risk patterns.
- The ACSQHC's own 2024 fact sheet notes that "an absence of an alert doesn't rule out risk" — the system is not a safety guarantee.

Despite this work, the population-level effect of RTPM on overdose mortality in Australia has still not been formally evaluated. Australia's opioid death toll continued rising through the RTPM rollout period.

### 3. Coverage Gap 1: Workers' Compensation-Funded Opioids

This is the gap most directly relevant to the prior report's findings, and it operates at two levels.

**Level 1: The prescribing and dispensing flow.**
When a pharmacist dispenses a Schedule 8 opioid — regardless of how it is funded — the dispensing record should in principle be captured by the RTPM system in that jurisdiction (most systems require pharmacies to upload dispensing records). This means that at the dispensing level, workers' compensation-funded opioids *may* appear in state RTPM systems.

**Level 2: The system-to-system data gap.**
The critical gap is not at the dispensing counter — it is between the workers' compensation insurer's data systems and the RTPM/NDE infrastructure. State workers' compensation insurers maintain their own medication claims data separately from both the PBS and RTPM systems. The implications are significant:

- **Workers' comp claims data is isolated.** A 2025 Monash University study on opioid prescribing to Victorian injured workers noted that the lead researcher's team could only conduct their analysis in Victoria because it is "one of only two states in the country where this sort of analysis is possible, because the other state workers' compensation systems aren't collecting detailed information on the medicines they are paying for."

- **Most states have no medicine-level workers' comp prescribing data.** Across six of eight jurisdictions, the workers' compensation insurer cannot tell you which opioids it has funded, at what dose, or for how long — because it doesn't collect that information in a clinically useful form. This means system-wide pharmacovigilance is impossible.

- **RTPM cannot flag the funding context.** When a prescriber checks RTPM before writing a new Schedule 8 opioid, the system shows them dispensing history — but not whether that history was funded by workers' comp, private insurance, the PBS, or out-of-pocket payment. A treating GP cannot tell from RTPM that their patient's previous 18 months of oxycodone was workers' comp funded and therefore absent from PBS dispensing data.

- **SIRA NSW has internal medication coding.** The NSW State Insurance Regulatory Authority developed its own medication coding system distinguishing PBS, non-PBS, injectable, and other opioid categories — but this data feeds the workers' comp scheme's internal analytics, not SafeScript NSW or the NDE. It is a parallel data silo, not an integrated one.

The practical consequence: a commercial truck driver who has been prescribed escalating doses of opioids for two years under a workers' compensation claim, whose prescriptions are funded by icare NSW rather than the PBS, may have a largely empty RTPM profile — not because the system failed to record anything, but because the prescribing context it cannot see is the one that matters most.

### 4. Coverage Gap 2: Medicinal Cannabis Under the Special Access Scheme

Approximately 177,000 SAS-B approvals were processed in 2024 for medicinal cannabis products (covered in Report 114 of this series). The majority of these products are unapproved therapeutic goods — not TGA-registered, not PBS-listed, not using standardised Australian Medicines Terminology (AMT) coding.

This creates a structural capture problem for RTPM:

- **AMT coding is the key.** RTPM systems identify medicines through standardised product codes (AMT). A dispensing record submitted without a valid AMT code cannot be matched to a specific drug, formulation, or dose — making clinical risk assessment by the receiving prescriber or pharmacist impossible.

- **Monash's 2026 submission to the TGA** described this directly: "all legally supplied medicinal cannabis in Australia is supplied via prescription, but these prescriptions are not currently captured consistently by SafeScript." The submission characterised the lack of compulsory inclusion as "a critical blind spot in real-time prescription monitoring platforms."

- **Queensland (QScript) requires Schedule 8 cannabis dispensing records to be uploaded**, including for unapproved products — but the upload requirement sits with pharmacists, and there is "no requirement for prescribers to upload prescription information to QScript when prescribing a monitored medicine." The asymmetry between dispensing-side upload and prescribing-side upload requirements creates partial visibility.

- **Most unapproved cannabis products lack standard coding.** The Monash submission notes that "most unapproved products are private (unsubsidised) prescriptions, so they are not captured by the PBS, nor do they currently utilise standardised Australian Medicines Terminology." Without AMT coding, a dispensing record is effectively uninterpretable by the RTPM system's clinical decision support layer.

The significance extends beyond cannabis itself. A patient concurrently prescribed high-dose opioids through the PBS and high-THC cannabis through SAS-B has a drug interaction risk profile that no RTPM system can currently assess in full, because the cannabis component may be invisible or coded as a generic entry.

### 5. Coverage Gap 3: The Prescribing vs. Dispensing Asymmetry — and Non-Mandatory Checking

The RTPM architecture primarily captures **dispensing** data: when a pharmacist fills a prescription, that event is recorded. The **prescribing** side — when a doctor writes the script — is less consistently captured, because requirements vary:

- **Victoria (mandatory):** Prescribers must check SafeScript before prescribing or dispensing a monitored medicine. This creates two-sided visibility.
- **NSW (voluntary):** SafeScript NSW operates with alerts for prescribers (e.g., alert fires when a patient has received prescriptions from four or more prescribers in 90 days), but checking is not legally mandated. A prescriber who ignores the alert faces no automatic sanction.
- **Most other jurisdictions:** Similar to NSW — dispensing upload is required of pharmacists, but prescriber checking is either advisory or not yet mandated.

This creates a system that can tell you what was *dispensed* but cannot guarantee that *prescribers* were informed before writing a high-risk script. The Victorian evidence suggests that voluntary checking can achieve meaningful behaviour change — but it also leaves a gap: a prescriber who chooses not to check RTPM, or who is unaware of alert triggers, does not benefit from the safety mechanism.

The ACSQHC's 2024 fact sheet includes an under-discussed warning: "emergency supply by a pharmacist" may not appear in the system. Emergency supply — typically for a patient who cannot wait for a GP appointment — is one of the pathways through which continuous opioid supply occurs in patients at highest risk of dose escalation and dependence.

### 6. The Death Toll in Context

The Penington Institute's 2026 Annual Overdose Report (covering 2024 data) found:

- **2,596 drug-induced deaths** in 2024 — the highest on record in a 24-year dataset, surpassing the previous record set in 2023 (2,272 deaths)
- Unintentional drug-induced deaths exceeded 2,000 for the first time
- **Opioids** were involved in 1,083 deaths — the most frequent drug class
- **Stimulants** were involved in 843 deaths; **benzodiazepines** in 696 deaths
- Middle-aged and older Australians (50–59) have seen a 305% increase in unintentional overdose deaths since 2001

These deaths are occurring across a period (2019–2024) when the national RTPM rollout was underway and, in Victoria, mandatory. The monitoring system has demonstrably reduced doctor-shopping for monitored medicines; it has not yet demonstrably reduced opioid-induced deaths. The three coverage gaps documented above — workers' compensation funding, medicinal cannabis capture, and non-mandatory prescriber checking — represent part of the explanation for why real-time monitoring is necessary but insufficient.

---

## Tensions and Open Questions

**1. Does "capturing dispensing" equal pharmacovigilance?**
The fundamental architecture of most Australian RTPM systems is dispensing-centric: pharmacists upload records, prescribers (optionally) check them. This design assumes that the high-risk moment is at the dispensing counter — but for many patients, the high-risk moment is the initial prescribing decision, or the dose escalation in a GP review, which may not generate a dispensing event for weeks. A monitoring system built around dispensing events will systematically miss prescribing decisions.

**2. The voluntary compliance problem.**
Victoria's mandatory model achieved most of its doctor-shopping reduction during the voluntary phase — but voluntarism works only when system adoption is high and clinical culture is strong. NSW has the nation's highest burden of opioid-dependent patients and a voluntary SafeScript system. The policy case for NSW mandating SafeScript checking has been made repeatedly; the reform has not been made.

**3. Workers' comp data fragmentation is a national governance failure.**
The finding that only two states can conduct medicine-level analysis of workers' compensation opioid prescribing is extraordinary given the known occupational injury pathway to chronic opioid use. No national body — not the NHVR, not the ACSQHC, not the DoHDA — has been charged with connecting workers' compensation pharmacy claims data to the RTPM/NDE architecture. This is a structural omission in Australia's pharmacovigilance governance.

**4. Cannabis monitoring is actively resisted by the industry.**
Medicinal cannabis prescribers and platforms (see Report 113 and 114) have commercial interests in remaining outside the most scrutinised prescribing channels. Requiring consistent AMT-coded capture of all SAS-B cannabis prescriptions in RTPM systems would represent a material compliance cost and transparency constraint on a $1 billion private market that has grown largely outside the PBS infrastructure. TGA's 2026 review of the SAS framework received 790 submissions, but the monitoring capture gap was not among the headline reform proposals.

**5. Cross-jurisdiction data quality is still being remediated.**
The Australian Digital Health Agency's own description of its 2024–25 RTPM priorities included a "Data Quality Remediation Plan" and "centralised process for coordinating nationwide and jurisdictional system enhancements." A system that still needs data quality remediation four years into national rollout is not yet a reliable basis for life-safety clinical decisions — though it is better than no system.

---

## Threads to Branch Into Next

1. **Real-Time Prescription Monitoring reform — mandating NSW and the national prescriber-checking gap**: what would it take to make prescriber checking mandatory in every Australian jurisdiction, and what is the political economy of that reform?
2. **Chronic pain MBS reform and the Faculty of Pain Medicine's campaign**: whether a structured chronic opioid prescribing review item — already proposed — could incorporate RTPM checking as a mandated component and close the prescribing-side gap
3. **Cross-scheme data linkage — workers' compensation to PBS and RTPM**: the technical feasibility and legal barriers to connecting state workers' comp pharmacy claims systems to the NDE; whether the NTC/NHVR reform process creates a hook for this
4. **Opioid dependence treatment and the RTPM interaction**: how RTPM alerts interact with patients in opioid substitution therapy (methadone, buprenorphine) — the risk of flags being misinterpreted as diversion when patients are in legitimate treatment, and whether RTPM is being used appropriately in harm reduction contexts
5. **The occupational medicine workforce gap** (flagged in Report 119): the mismatch between AFTD's recommendation for specialist input in complex opioid driver assessments and Australia's roughly 250 practising occupational and environmental medicine specialists nationally

---

## Sources

- Penington Institute, *Australia's Annual Overdose Report 2026* (covering 2024 data): https://www.penington.org.au/australias-annual-overdose-report-2025
- Penington Institute, *More middle-age and older Australians dying from drug overdoses* (2025): https://www.penington.org.au/more-middle-age-and-older-australians-dying-from-drug-overdoses-new-figures-from-the-penington-institute-reveal/
- ACSQHC, *Real-Time Prescription Monitoring* (program overview): https://www.safetyandquality.gov.au/our-work/e-health-safety/real-time-prescription-monitoring
- ACSQHC, *Real-Time Prescription Monitoring: Fact Sheet for Prescribers and Pharmacists* (August 2024): https://safetyandquality.gov.au/publications-and-resources/resource-library/real-time-prescription-monitoring-fact-sheet-prescribers-and-pharmacists
- Australian Digital Health Agency, *Real-Time Prescription Monitoring*: https://www.digitalhealth.gov.au/healthcare-providers/initiatives-and-programs/real-time-prescription-monitoring
- Australian Digital Health Agency, *Annual Report 2024–25: Improving Connectivity and Advancing Real-Time Data Exchange*: https://www.transparency.gov.au/publications/health-disability-and-ageing/australian_digital_health_agency/australian-digital-health-agency-annual-report-2024-25/part-2.-performance/improving-connectivity-and-advancing-real-time-data-exchange
- Fred IT Group, *RTPM Systems across Australia* (vendor page): https://erx.com.au/pharmacists/real-time-prescription-monitoring
- Medical Republic, *SafeScript linked to sharp drop in doctor-shopping for opioids and benzos* (2024–25 MJA study coverage): https://www.medicalrepublic.com.au/safescript-linked-to-sharp-drop-in-doctor-shopping-for-opioids-and-benzos/126640
- AusDoc, *Fewer patients seeing multiple prescribers since SafeScript, MJA study finds*: https://www.ausdoc.com.au/news/fewer-patients-seeing-multiple-prescribers-since-safescript-mja-study-finds-but-is-it-a-safety-achievement-or-statistical-artefact/
- Monash University, *Study raises concern about opioid prescribing to injured Australian workers* (2025): https://www.monash.edu/medicine/news/latest/2025-articles/study-raises-concern-about-opioid-prescribing-to-injured-australian-workers
- PMC, *Early High-Risk Opioid Prescribing and Persistent Opioid Use in Australian Workers with Workers' Compensation Claims* (CNS Drugs, 2025): https://pmc.ncbi.nlm.nih.gov/articles/PMC11982141/
- PMC, *Can GP Opioid Prescribing to Compensated Workers Be Detected Using Administrative Payments Data?* (2024): https://pmc.ncbi.nlm.nih.gov/articles/PMC11839698/
- Monash Addiction Research Centre (MARC), *Supplementary Submission on Medicinal Cannabis and RTPM* (2026): https://www.monash.edu/__data/assets/pdf_file/0009/4431375/MARC_SuppSUB_DPCSImpactAnalysis_Final_Redacted.pdf
- SIRA NSW, *Medication Management in the NSW Personal Injury Schemes: Better Practice Guide* (updated December 2024): https://www.sira.nsw.gov.au/__data/assets/pdf_file/0007/882223/Medication-management-in-the-NSW-personal-injury-schemes-better-practice-guide.pdf
- SIRA NSW, *Best Practice Opioid Management* (rapid review): https://www.sira.nsw.gov.au/resources-library/research-library/completed-research/best-practice-opioids-management
- Queensland Health, *QScript and Legislative Requirements — Monitored Medicine Data Upload Requirements*: https://www.health.qld.gov.au/clinical-practice/guidelines-procedures/medicines/monitored-medicines/monitored-medicine-data-upload-requirements
- PulseIT, *Tasmania to join national RTPM with TasScript* (April 2024): https://www.pulseit.news/?p=27035
- Pulse+IT / RACGP, *Progress made on national real-time prescription monitoring*: https://www1.racgp.org.au/newsgp/professional/progress-made-on-national-real-time-prescription-m
- Scimex/Expert Reaction, *Australia's prescription drug monitoring programs need to look out for unintended harms*: https://www.scimex.org/newsfeed/australias-prescription-drug-monitoring-programs-need-to-look-out-for-unintended-harms
