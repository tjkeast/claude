# Australia's ePrescribing Ecosystem: The Active Script List, eNRMC, and the Race to Digital Medication Safety

**Report 038 — 2026-07-14**

**Summary:** Australia has generated over 370 million electronic prescriptions since nationwide rollout in 2021, with the Active Script List (ASL) emerging as the next layer of digital medication management. But the ecosystem is fragmented across three distinct domains — community prescribing, residential aged care, and controlled-drug monitoring — each operating on different technology standards, governance frameworks, and mandation timelines, with the aged care sector now facing a hard 1 December 2026 deadline to complete a digital transition that began in 2022 and has already been extended twice.

**Why this follows from yesterday:** Report 037 documented the $48.4 billion RAD capital pool and the governance reforms now required by the Aged Care Act 2024. A critical but underreported feature of that same reform wave is the requirement for residential aged care facilities to digitise medication prescribing by the end of 2026 — via the eNRMC system. Medication errors are the largest category of preventable harm in residential aged care; the digital transition is as much a safety imperative as an administrative one, linking directly to the polypharmacy problem documented in Report 031.

---

## Background

### Why Medication Safety Is Central to Aged Care

Approximately 95% of residential aged care residents are regular medicine users, and the average resident takes nine or more regular medicines (polypharmacy, as documented in Report 031). Paper-based medication charts — the historical standard — create transcription errors, poor legibility, inaccessible allergy histories, and almost no interaction-checking at the point of prescribing. For a sector where roughly 50% of medication errors are preventable and where psychotropic overuse was documented in the Royal Commission's final findings, the shift to electronic medication management is one of the most consequential structural changes underway.

The Australian Government has invested in three overlapping digital medication safety layers:

1. **Electronic prescribing (eScript/ASL)** — community and primary care digital prescriptions
2. **Electronic National Residential Medication Chart (eNRMC)** — the aged-care-specific medication management system that integrates prescribing, supply, and administration
3. **Real-time Prescription Monitoring (RTPM)** — the Schedule 8 controlled-drug surveillance network operated by states and territories

These are not a single system; they are linked through national infrastructure (My Health Record, the Healthcare Identifiers Service) but governed by separate regulatory frameworks, funded through separate mechanisms, and running on incompatible timelines.

---

## Key Findings

### 1. Electronic Prescribing at Scale: 370 Million and Counting

Since nationwide rollout in 2021, Australia has generated over **370 million electronic prescriptions** as of July 2025. The uptake has been substantial:

- More than **80,000 prescribers** are generating electronic prescriptions
- More than **99% of general practices** and **96% of community pharmacies** are connected to the My Health Record system
- As of early 2024, 189 million electronic prescriptions had been issued; this number more than doubled to 370 million by July 2025, demonstrating rapid acceleration

Electronic prescriptions work in two modes:

**Token model**: A unique token (a QR code or URL sent by SMS or email) is generated for each prescription. The patient presents the token to any pharmacy, which uses it to retrieve the prescription from the national repository. Repeats generate new tokens.

**Active Script List (ASL) model**: A more sophisticated opt-in system where a patient's active tokens are consolidated into a single digital list, accessible by any authorised pharmacist with the patient's consent. The patient does not need to manage individual tokens.

The ASL eliminates a significant practical barrier: under the token model, patients receiving multiple medicines must track multiple SMS or email tokens, which are frequently lost. The ASL creates a single pharmacy-accessible medication record for consented patients.

### 2. The Active Script List: Architecture, Consent, and the 2025 Regulatory Shift

The ASL is operated through the Healthcare Identifiers (HI) Service, managed by Services Australia. Key features:

- **Consent-based**: Each pharmacy must obtain the patient's explicit consent before accessing their ASL; patients can withdraw consent at any time
- **Patient-controlled**: Patients can view their ASL via the **1800Medicare app** (available from the Australian Government), which includes a 6-digit PIN, automatic logout after 5 minutes, and biometric support
- **Prescriber-controlled**: Prescribers can add or remove items from a patient's ASL directly; they can also "lock" tokens (e.g., for controlled drugs) so they cannot be added to the ASL without specific authorisation

A significant regulatory change occurred on **6 March 2025**: the Healthcare Identifiers Regulations 2020 were amended via the *Healthcare Identifiers (Active Script List Registration) Regulations 2025*, allowing patients to **self-register** for an ASL. Previously, ASL registration could only be initiated through a prescriber or pharmacist. This change, combined with the 1800Medicare app functionality, shifts the ASL from a health-professional-controlled tool toward a patient-held digital record.

From July 2026, **Sharing by Default** rules were extended to cover dispensed and prescribed medicines, meaning medicines dispensed to patients with a My Health Record are automatically added to the record (patients can opt out). Budget 2026-27 allocated **$47.5 million** for this expansion, part of a broader **$598.3 million** commitment over two years to My Health Record operations and enhancement.

### 3. Electronic Prescribing by Default: The Next Mandate

Australia is moving toward making electronic prescribing the default — not merely the option — for primary care. A **trial was planned for early 2026** in selected primary care settings to test "electronic prescribing by default," under which paper prescriptions would remain a legal option only for patients without digital access or in clinically appropriate circumstances.

This represents a deliberate shift from the current voluntary-by-prescriber model. The rationale is patient safety: paper prescriptions cannot generate duplicate detection alerts, cannot feed into RTPM systems in real time, and cannot be captured automatically in the national medication record.

Western Australia is the **first state to enable electronic prescribing across its public health system**, following initial pilot work that demonstrated feasibility in the hospital inpatient setting — the most complex prescribing environment, where multiple clinicians may write orders for the same patient simultaneously.

The Budget 2026-27 allocated **$745.1 million over four years** to strengthen Medicare digital system capability and integration, with ePrescribing interoperability as a named priority.

### 4. The eNRMC: Australia's Aged Care Digital Medication Mandate

The electronic National Residential Medication Chart (eNRMC) is a purpose-built digital medication management system for **residential aged care homes (RACHs)**. Unlike a standalone prescribing tool, an eNRMC system integrates:

- Electronic prescribing by GPs, nurse practitioners, and specialist prescribers visiting the facility
- Medication supply tracking by community pharmacies under contracted arrangement
- Medication administration records (MARs) for nursing and care staff
- Drug interaction alerts and allergy flags
- Automatic medication history feeds to My Health Record

The transition from paper-based National Residential Medication Charts (NRMCs) to eNRMC was initiated with a **Transitional Arrangement** from 1 July 2022, supported by a grant program for facilities to fund the software upgrade. As of mid-2026, **8 of 10 eNRMC software vendors** have achieved full electronic prescribing conformance with the technical and legal standards.

**The hard deadline**: The Transitional Arrangement ends on **1 December 2026**, with full conformance required from all facilities by **31 December 2026**. Non-conformant software vendors were given an extension to **1 April 2026** to achieve conformance; from that date, orders created using non-conformant systems require duplicate PBS paper prescriptions — an administrative burden that effectively incentivises migration.

This deadline has already been extended twice (hence "further extension" in the DoH&DA announcement title). The pressure of repeated extensions reflects genuine implementation challenges in the sector.

**Pharmacist qualitative study (PMC 2026)**: A qualitative study of Australian pharmacists' experiences with the eNRMC found mixed results. Pharmacists identified significant safety benefits — medication history completeness, allergy alert integration, reduced transcription errors — but also documented implementation barriers: workflow disruption during changeover, software interoperability problems between the eNRMC and dispensing systems, connectivity issues at rural facilities, and inadequate training for aged care staff (including the challenge of training workers with high turnover and low baseline digital literacy). The study highlighted that the benefits were greatest where implementation was well-supported by management and where the contracted pharmacy had deep familiarity with the eNRMC software.

### 5. Real-Time Prescription Monitoring: A National System Built State by State

The **Real-Time Prescription Monitoring (RTPM)** network tracks prescribing and dispensing of Schedule 8 (controlled) medicines — primarily opioids (oxycodone, fentanyl, morphine, hydromorphone), benzodiazepines, and certain stimulants. Prescribers and pharmacists are required to check the relevant state's RTPM system before prescribing or dispensing a monitored medicine.

RTPM operates through **state- and territory-specific systems**:

| Jurisdiction | System | Status |
|---|---|---|
| Victoria | SafeScript | Mandatory (from 1 April 2020) |
| New South Wales | SafeScript NSW | Mandatory |
| Queensland | QScript | Mandatory |
| South Australia | ScriptCheckSA | Mandatory |
| Tasmania | TasScript | Mandatory (replaced DORA) |
| Western Australia | WA RTPM | Active |
| ACT | QScript (shared) | Active |
| Northern Territory | NTScript | Active |

The federal layer is the **National Data Exchange (NDE)** — an interoperability infrastructure that allows state RTPM systems to share dispensing data across borders. However, **full cross-jurisdictional interoperability has not been achieved**: a NSW clinician checking their SafeScript NSW system will primarily see NSW data, even if the patient has active prescriptions in Victoria or Queensland. The NDE is a Strategic Priority under the Intergovernmental Agreement on National Digital Health 2023-2027, but integration progress varies by jurisdiction.

**SafeScript outcome evidence (Monash University, 2026)**: The first Australian study to directly link RTPM to prescribing change analysed **6.7 million prescriptions** for over **810,000 patients** across **562 general practices** in Victoria, covering 52% of the Victorian population, between 2017 and 2023.

Key findings:
- When SafeScript was introduced on a **voluntary basis (April 2019)**: immediate **15% drop** in patients seeing four or more prescribers for monitored medicines
- When SafeScript use became **mandatory (April 2020)**: reductions were sustained, with further decline
- **96%** of multiple prescriber cases occurred within the same clinic (challenging the assumption that "doctor shopping" primarily occurs across different clinics)
- **85%** of multiple prescriber episodes involved at least one opioid prescription

Victoria's Coroner's Court noted a "continuing decline in the proportion of overdose deaths involving pharmaceutical opioids and benzodiazepines" following SafeScript implementation, though attribution to any single intervention is cautious.

**The opioid balloon problem**: A 2025 *Medical Journal of Australia* analysis by Daniels et al. raised a structural caution. RTPM reduces supply through formal prescription channels but does not reduce demand. Patients displaced from pharmaceutical opioids may switch to illicit opioids (fentanyl analogues, heroin) or obtain medicines through informal channels. The study documented evidence of "squeezing the balloon" — prescribing reductions accompanied by increases in illicit opioid-related deaths in some population segments. This is a genuine and unresolved tension in RTPM policy.

### 6. The Aged Care Intersection: Medication Safety as a Structural Reform Test

The three ePrescribing layers intersect most acutely in residential aged care. Consider a resident with multi-morbid conditions prescribed nine regular medicines:

- Her GP prescribes via an eNRMC-connected software system at the facility
- The eNRMC system checks My Health Record for her medication history and allergy flags
- Two of her medicines are Schedule 8 (opioids for pain management); the prescribing GP must check SafeScript (or the relevant state RTPM) before ordering
- The facility pharmacy receives the prescription electronically through the eNRMC system
- Dispensed medicines are automatically recorded in her My Health Record (Sharing by Default from July 2026)
- A pharmacist reviewing her medication record can view her current prescriptions via the ASL (with consent)

When this chain works as designed, the pharmacist conducting an annual medication review — a key component of the Aged Care Act 2024 quality standards — has a complete, real-time picture of her medicines across all prescribers. This is transformational compared to the paper chart model, where the medication review pharmacist may be working from an incomplete hand-transcribed document.

When the chain breaks — eNRMC vendor not conformant, connectivity failure at a rural facility, RTPM cross-border data gap, or resident without My Health Record — the safety benefit disappears and the administrative burden may exceed the paper system it replaces.

**The MEGA-MAC study (UNSW/PMC 2025)**: A protocol was published for a national quality improvement collaborative to implement Australia's new guiding principles for medication management in RACHs, specifically targeting embedded pharmacists in medication advisory committees. This program recognises that digital tools are necessary but insufficient without pharmacist-level clinical governance — the human layer on top of the eNRMC infrastructure.

### 7. The Funding Cliff and the Post-2027 Uncertainty

Budget 2026-27 delivered substantial short-term digital health investment:
- **$598.3 million** over two years for My Health Record
- **$47.5 million** for Sharing by Default medicines expansion
- **$745.1 million** over four years for Medicare digital systems

But analysis by *Health Services Daily* (2026) identified a **sharp funding cliff after 2027-28**. The ADHA — the national digital health coordinating body — relies on time-limited Commonwealth grants. If ongoing operational funding is not confirmed, core infrastructure including the national ePrescribing repository and the ASL registry faces uncertainty. This is structurally analogous to the health workforce problem: substantial upfront investment, followed by a funding taper, with uncertain longer-term sustainability.

---

## Tensions and Open Questions

**1. The eNRMC mandate and market concentration.** Only 10 software vendors hold eNRMC conformance — a thin market for a national aged care requirement. Two vendors had not achieved conformance by April 2026. Facilities locked into non-conformant software face a disruptive system migration during the same period as major workforce and funding reforms under the Aged Care Act 2024. The government's extension history (two already) suggests a third may be politically necessary if the December 2026 deadline is not met.

**2. RTPM interoperability is incomplete.** The NDE exists but full cross-state visibility is not achieved. A patient travelling between Victoria and Queensland who receives an opioid prescription in Queensland may not appear in Victoria's SafeScript. This gap is clinically significant for patients with chronic pain managed across state lines, and for aged care residents who travel to see family interstate.

**3. The opioid balloon paradox.** SafeScript demonstrably reduces formal-channel overprescribing. But the displacement to illicit supply is documented. Prescription monitoring systems address pharmaceutical supply but not drug dependence; the policy question of how RTPM pairs with addiction treatment access (Report 017 on psychosocial disability) is unresolved.

**4. Digital exclusion in aged care.** The ASL and eNRMC both assume reliable internet connectivity. Rural and remote aged care facilities with poor connectivity face a structural disadvantage: the very facilities that already lag in workforce and infrastructure are also the least well-positioned to implement digital medication systems. The facility grants program for eNRMC transition did not specifically weight remote facilities more heavily.

**5. The 1800Medicare app and patient agency.** The shift toward patient self-management of the ASL (self-registration from March 2025; 1800Medicare app) assumes digital and health literacy. Aged care residents — many with cognitive impairment — cannot manage their own ASL. The system depends on aged care facility staff and GPs managing ASL on behalf of residents, which is not what the patient-directed consent model was primarily designed for. Adapting the ASL governance for the cognitively impaired is an unresolved design problem.

---

## Threads to Branch Into Next

1. **International medical graduate dependency** — IMGs fill 42% of projected Australian medical workforce growth to 2048; Section 19AB rural distribution requirements; global competition for health workers intensifying; deferred from Reports 034–037; the most persistently deferred remaining major thread

2. **Long-term care insurance feasibility for Australia** — CEPAR modelling (Park, Sherris 2024/2026); German and Japanese social LTCI models; the aged care levy proposal from the Royal Commission; why no LTCI market exists despite actuarial feasibility findings; directly connected to Reports 036-037

3. **Accommodation supplement and thin-market equity** — government accommodation subsidy for residents below means-testing thresholds; supplement adequacy under Aged Care Act 2024; rural/remote facility supplement rates vs local construction costs; equity dimension of a capital-holding model

4. **Aged care provider market exits and consolidation** — KPMG/StewartBrown project smaller provider exits; how the Aged Care Act 2024 registration framework handles exits; what happens to residents when a facility closes; experience of large-scale Bupa enforcement cases 2022-24

5. **Pharmacist scope of practice expansion and PBS prescribing** — state-by-state variation in pharmacist prescribing rights (UTI, contraception resupply, minor ailments); interaction with the PBS prescribing authority framework; whether pharmacist prescribing can relieve GP pressure or creates a two-tier quality risk

---

## Sources

- [Electronic prescribing | Australian Government Department of Health, Disability and Ageing](https://www.health.gov.au/our-work/electronic-prescribing)
- [Electronic National Residential Medication Charts (eNRMC) — Further Extension | DoH&DA](https://www.health.gov.au/news/electronic-national-residential-medication-charts-enrmc-further-extension-to-timeframes-for-electronic-prescribing)
- [Electronic National Residential Medication Chart | ACSQHC](https://www.safetyandquality.gov.au/our-work/medication-safety-and-quality/electronic-medication-charts/electronic-national-residential-medication-chart)
- [eNRMC — Conformance Status Tracker | DoH&DA](https://www.health.gov.au/resources/publications/electronic-national-residential-medication-charts-enrmc-conformance-status-tracker)
- [Active Script List overview | HealthVitalIT](https://healthvitalit.com.au/topics/article/digital-health/eprescribing-and-active-script-lists)
- [A new era in electronic prescribing – the Active Script List | Brisbane South PHN](https://bsphn.org.au/news/a-new-era-in-electronic-prescribing-the-active-script-list)
- [Electronic Prescriptions | Australian Digital Health Agency](https://www.digitalhealth.gov.au/initiatives-and-programs/electronic-prescriptions)
- [Electronic Prescribing — Active Script List Privacy Framework | DoH&DA](https://www.health.gov.au/sites/default/files/2025-08/electronic-prescribing-active-script-list-privacy-framework.pdf)
- [Real-time Prescription Monitoring | ADHA](https://www.digitalhealth.gov.au/healthcare-providers/initiatives-and-programs/real-time-prescription-monitoring)
- [Australian-first study links RTPM to drop in high-risk prescribing | Monash University, 2026](https://www.monash.edu/medicine/news/latest/2026-articles/australian-first-study-links-real-time-prescription-monitoring-to-drop-in-high-risk-medication-prescribing)
- [Study links real-time prescription monitoring to drop in high risk medication prescribing | MedicalXpress, 2026](https://medicalxpress.com/news/2026-06-links-real-prescription-high-medication.html)
- [SafeScript and GPs credited with fall in benzo, opioid deaths | Medical Republic](https://www.medicalrepublic.com.au/safescript-and-gps-credited-with-fall-in-benzo-opioid-deaths/119180)
- [Squeezing the opioid balloon | Daniels et al., MJA 2025](https://onlinelibrary.wiley.com/doi/10.5694/mja2.52721)
- [RTPM in Australia: A Guide for Clinics | Zedmed](https://www.zedmed.com.au/news/real-time-prescription-monitoring-rtpm-in-australia-a-guide-for-clinics/)
- [Real-time Prescription Monitoring in Australia | ADF](https://adf.org.au/insights/rtpm-in-australia/)
- [Budget 2026: Australia funds $400M more for My Health Record | Healthcare IT News](https://www.healthcareitnews.com/news/anz/budget-2026-australia-funds-400m-more-my-health-record)
- [Australia: Budget Bites — Digital Health | Baker McKenzie 2026](https://www.bakermckenzie.com/en/insight/publications/2026/05/australia-budget-bites-digital-health)
- [Digital health funding surge masks looming cliff for ADHA | Health Services Daily](https://www.healthservicesdaily.com.au/digital-health-funding-surge-masks-looming-cliff-for-adha/45462)
- [Exploring Australian pharmacists' experiences with the eNRMC | PMC 2026](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12432027/)
- [MEGA-MAC study protocol: medication management in RACHs | PMC 2025](https://pmc.ncbi.nlm.nih.gov/articles/PMC12323118/)
- [2026 eScript Regulations | Prime Medic](https://www.primemedic.com.au/escript-prescription-access/escript-regulation-updates)
- [1800MEDICARE | Australian Government](https://www.1800medicare.gov.au/)
- [MedAdvisor App — Active Script List guide | MedAdvisor](https://www.mymedadvisor.com/en-au/active-script-list)
- [Funding boost will see ePrescribing expand into hospitals | RACGP newsGP](https://www1.racgp.org.au/newsgp/professional/funding-boost-will-see-eprescribing-expand-into-ho)
