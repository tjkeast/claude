# My Health Record and Digital Health Infrastructure for Aged Care: Australia's Fragmented Records Problem and the Race to Interoperability

**Report 033 — 2026-07-09**

**Summary:** Australia's national digital health record system, My Health Record, has registered 24.8 million consumers — over 90% of the population — and holds more than 2 billion uploaded documents. Yet in residential aged care, where medication safety, advance care planning portability, and care continuity are most critical, digital infrastructure remains fragmented, adoption is uneven, and interoperability between clinical information systems is largely absent. The Electronic National Residential Medication Chart (eNRMC) — the pivot technology for medication management in aged care — has missed multiple implementation deadlines and now runs on a transitional arrangement extended to 1 December 2026. The Sharing by Default Act 2025 is the legislative engine for change, but its aged care application lags other sectors. Budget 2026-27 injected $598.3 million into My Health Record modernisation and $259.9 million into aged care ICT sustainment — but money alone cannot fix a sector where only 14% of providers use fully integrated software and 75% have no digital literacy criteria in hiring.

**Why this follows from yesterday:** Report 032 found that ACQSC enforcement of the Aged Care Act 2024 depends on accurate, accessible medication records — particularly for chemical restraint monitoring under the Serious Incident Response Scheme. Today's report examines the digital infrastructure that either enables or undermines that enforcement: My Health Record's aged care integration, the eNRMC rollout, the Sharing by Default reforms, and the interoperability gap that sits at the root of both medication safety failures and advance care planning portability problems identified throughout this series.

---

## Background

My Health Record (MHR) was established under the My Health Records Act 2012 as Australia's national, opt-out personal health record system. After a failed opt-in period (2012–2018) and a landmark opt-out trial in 2016-17, the government legislated automatic registration for all Australians in 2018–19. The system is operated by the Australian Digital Health Agency (ADHA), funded directly by the Commonwealth.

The core premise is straightforward: a patient's health information — shared health summaries, discharge summaries, prescription and dispensing records, pathology and imaging results, advance care directives — is accessible to any authorised clinician treating that person, regardless of the setting in which the information was first created. This is particularly important for aged care residents, who typically have multiple comorbidities, see multiple prescribers (visiting GPs, specialists, hospital clinicians), and are at disproportionate risk of medication errors, polypharmacy harms, and preventable hospital admissions.

The challenge is that the promise of a "single source of truth" still diverges widely from the reality of aged care delivery in 2026, where information is siloed across incompatible systems, upload rates are inconsistent, and the clinical information systems used by aged care providers were not built for interoperability.

---

## Key Findings

### 1. My Health Record: System Scale and the Aged Care Gap

By February 2026, My Health Record held records for **24.8 million Australians** — over 90% of the population. The system contains **more than 2 billion documents**, including:

- **914 million clinical documents** uploaded by hospitals, pathologists, specialists, and GPs
- **1.2 billion medicine documents** uploaded by pharmacists and prescribers, primarily dispense records

These aggregate numbers represent a major achievement in health information infrastructure since the low-uptake early years of the opt-in scheme. But the composition of those documents reveals the problem for aged care: the primary contributors are pharmacists (dispense records from community pharmacy) and hospitals (discharge summaries, pathology). The chronic, longitudinal care documentation — updated care plans, medication reviews, advance care planning documents, and nursing assessments — that is most critical for aged care residents is systematically under-represented.

The Australian Digital Health Agency ran a specific **My Health Record Registration support program for Residential Aged Care Facilities** from January 2023 to June 2024, with the target of supporting 80% of residential aged care homes to connect. Connecting a facility means authorising the provider organisation to access and upload to residents' records, not that any specific documents have been uploaded or that care management software is integrated. The gap between technical connection and genuine clinical use is where the real problem resides.

### 2. The Electronic National Residential Medication Chart (eNRMC): A Delayed Pivot

The eNRMC is the medication management system for residential aged care. It replaces paper medication charts — the physical charts traditionally kept at the nurses' station for each resident — with an electronic system that:

- Provides a single, real-time medication record accessible to prescribing doctors, dispensing pharmacists, and care staff
- Enables electronic prescribing (ePrescribing) without separate paper or fax-based authority scripts
- Integrates with the PBS/RPBS claiming system
- Uploads the medication chart to the resident's My Health Record

The Australian Commission on Safety and Quality in Health Care (ACSQHC) maintains the national standard for the eNRMC — the legal and clinical template that software vendors must conform to. The ADHA manages the My Health Record integration specifications.

**Implementation has been significantly delayed.** The timeline has been revised multiple times:

| Milestone | Original Date | Actual/Extended Date |
|---|---|---|
| eNRMC software vendor conformance | Earlier 2025 | October 2025 (8 of 10 vendors); 1 April 2026 (remaining 2 vendors) |
| Electronic prescribing capability mandatory in RACFs | 1 October 2025 | Transitional: 1 March 2026 extended to 31 December 2026 |
| End of Transitional Arrangement | 1 March 2026 | **1 December 2026** |

After 1 December 2026, only fully conformant eNRMC systems will be legally permitted for prescribing in residential aged care. Facilities using non-conformant systems after that date will require duplicate PBS paper prescriptions — a clunky parallel paper process that defeats the safety and efficiency purpose of digitisation.

Two of ten software vendors — Telstra Health and Strong Room Technologies — had not achieved conformance by October 2025, receiving a further extension to 1 April 2026. This is significant: software vendor market concentration means that a single non-conformant vendor can affect a substantial share of the aged care facility market.

**Why this matters for medication safety:** The connection between eNRMC and Report 031 (polypharmacy/psychotropics) and Report 032 (chemical restraint enforcement) is direct. An authorised, real-time medication record that is visible to visiting GPs, on-call pharmacists, ACQSC auditors, and emergency department clinicians is the foundation of rational medication management. Without it, the medication review processes mandated by the Aged Care Act 2024 and the Aged Care Rules 2025 cannot function effectively. The ACQSC's most common complaint category — medication administration and management — reflects in part the absence of complete, accessible records.

### 3. The Sharing by Default Act 2025: New Legal Architecture

The **Health Legislation Amendment (Modernising My Health Record – Sharing by Default) Act 2025** is the most significant legislative development in My Health Record's history. It amends the My Health Records Act 2012 to establish a framework where uploading specific health information to My Health Record is a legal obligation, not an optional contribution.

**First tranche — pathology and diagnostic imaging (from 1 July 2026):**

From 1 July 2026, every pathologist and radiologist is legally required to upload their reports to My Health Record by default (absent an exception or time extension). This is a fundamental departure from the previous voluntary upload model and is directly relevant to aged care residents, who undergo frequent blood tests (including for medication monitoring — drug levels, renal function, full blood count) and diagnostic imaging.

The practical implication: a visiting GP in a residential aged care facility, or an ED clinician receiving an aged care resident, will for the first time be able to rely on My Health Record as a *complete* repository of recent pathology results — assuming the tests were ordered after 1 July 2026.

**Second tranche — medicines (announced January 2026):**

In January 2026, the government announced that **medicines-related information from online prescribing services** will be the next category subject to mandatory sharing. Design consultation is underway, with a target completion by December 2026. This directly addresses the problem of telehealth prescribers and online pharmacy platforms (which have grown substantially since 2020) operating outside the shared medicines record.

The longer-term roadmap is a **National Medicines Record** — a comprehensive, near-real-time view of what a patient is currently prescribed and dispensed, assembled from all prescriber and pharmacy sources and accessible through My Health Record. The ADHA has $4.4 million allocated for initial design and stakeholder consultation. Full implementation will require:
- All prescribers (not just online platforms) uploading prescribing records by default
- All dispensing pharmacies (including in-facility aged care pharmacies) uploading dispense records in real time
- Integration of the eNRMC as an additional data source for RACF residents

**What the Aged Care Act 2024 and Aged Care Rules 2025 require:**

The Aged Care Rules 2025 impose data-sharing obligations on registered providers, including requirements to:
- Maintain up-to-date medication records for each resident
- Share clinical information when transferring a resident between care settings (the "Aged Care Transfer Summary" via My Health Record)
- Ensure resident advance care planning documents are accessible

The "Aged Care View" in My Health Record provides a consolidated display of clinical documents uploaded by residential aged care providers — including reason for transfer, medication chart, health summary — and links to other key documents (advance care directives, discharge summaries, immunisations). But the quality of this view depends entirely on what providers have actually uploaded — and that in turn depends on whether their clinical information system has been integrated.

### 4. The Aged Care Clinical Information System (ACCIS) Standards

The ADHA released the **Aged Care Clinical Information System (ACCIS) Standards** — the technical specifications that aged care software vendors must implement to enable interoperability with My Health Record and with the national data reporting infrastructure.

The ACCIS Standards define minimum software requirements for:
- Residential aged care homes' care management systems
- Electronic medication management (EMM) systems (the eNRMC)
- Home care support management systems

They are built on **HL7 FHIR (Fast Healthcare Interoperability Resources) AU Core** — the same standard used across the Australian health system (hospitals, GPs, pathology). This standardisation is the critical technical precondition for interoperability: different software products can exchange data if they all speak the same data language.

The AEHRC (Australian e-Health Research Centre, a CSIRO division) published its **Australian Aged Care Data Landscape Report** in March 2025, co-authored with the Digital Health CRC. The report found:

- Despite aged care and healthcare having largely similar data requirements, data exchange between the two sectors is "limited by the lack of system interoperability"
- The aged care sector lacks a coordinated national approach to data access and use
- Consistent and standardised data sharing "is vital to the provision of connected and coordinated care" but has not been achieved
- The ACCIS Standards are a necessary but not yet implemented step toward this

The report outlined a 14-recommendation framework for a national approach, including promoting common data languages, improving data governance, and developing minimum dataset standards for aged care.

### 5. Budget 2026-27: The Investment Pipeline

Budget 2026-27 (announced May 2026) directed substantial funding toward the digital health infrastructure stack relevant to aged care:

| Program | Amount |
|---|---|
| My Health Record — continued operations and enhancement | $598.3 million (over 2 years) |
| Aged care ICT system sustainment and digital infrastructure uplift | $259.9 million (in 2026-27) |
| ACQSC ICT governance, delivery processes, and cybersecurity | $33.7 million |
| States/territories: national digital health reforms in public hospitals | $79.2 million (over 3 years) |
| National Digital Child Health Record (via ADHA, Thriving Kids) | $19.1 million (over 2 years) |
| National Medicines Record — initial design and consultation | $4.4 million |

The $598.3 million for My Health Record represents the largest investment in the system since the opt-out transition. The breakdown includes targeted system improvements to support the expanded Sharing by Default requirements, infrastructure modernisation for the legacy My Health Record platform (built on technology from the 2012-era contract with Accenture and now requiring significant technical uplift), and the expanded pathology/imaging/medicines upload pipelines.

The $259.9 million for aged care ICT sustainment is specifically for the Department of Health's suite of aged care administration systems (My Aged Care, the AN-ACC funding system, the Support at Home payment infrastructure, and the data quality reporting systems), not directly for individual providers' care management software.

### 6. The Digital Maturity Gap: Infrastructure vs. Uptake

The most sobering finding in this space is the gap between infrastructure availability and actual provider use.

The Ageing Australia (formerly ACSA) **ACIITC Digital Maturity in Aged and Community Care Survey** — the most comprehensive benchmarking of its kind in the Australian aged care sector — found:

- Sector average digital maturity score: **58.4 out of 109** (a scale measuring software adoption, integration, data analytics capability, and workforce digital literacy)
- Only **14% of aged care providers** use fully integrated software systems — where clinical, care management, HR, and financial software share a common data environment
- **75% of providers have no digital literacy criteria** in their recruitment processes
- Most organisations surveyed had "generally not attained functional external interoperability" — meaning their systems cannot exchange data with external parties (including My Health Record) in a structured, automated way
- Rural providers lag metropolitan providers significantly on virtually every dimension

This is the structural constraint that funding alone cannot solve quickly. A provider that has not achieved internal integration between its care management software, medication management software, and workforce rostering system cannot then achieve external interoperability with My Health Record. Each layer must be built before the next is possible.

The digital workforce gap is parallel to the clinical workforce gap identified in Report 023 (aged care workers) and Report 031 (pharmacists). Providers in rural and thin markets cannot attract the IT staff and cannot afford the implementation consultancy required for system integration. This creates a technology access equity problem that mirrors every other access equity problem documented in this series.

---

## Tensions and Open Questions

**1. The eNRMC vendor lock-in risk.** The aged care medication management software market is concentrated among a small number of vendors. When two of ten vendors — one of which is Telstra Health, a significant market player — cannot achieve conformance, the entire sector is at risk of a compliance failure or continued fragmentation. Multiple deadline extensions suggest that the regulatory timetable has been vendor-driven rather than patient-safety-driven.

**2. Sharing by default vs. privacy and consent.** My Health Record operates on a consumer-controlled consent model: Australians can restrict access to their record or exclude specific documents. The Sharing by Default Act 2025 adds mandatory upload obligations, but does not eliminate consumer control — a patient can still choose to restrict visibility of their record to specific providers. For aged care residents with cognitive impairment, this consent framework creates complexity: who exercises the resident's access controls when the resident cannot? The Aged Care Act 2024's authorised representative framework governs substituted decision-making for care decisions, but its interaction with My Health Record's digital consent architecture is still being worked through.

**3. The advance care planning portability problem persists.** Report 029 documented the critical gap: ACP documents, though legally and clinically essential for aged care residents, are not systematically accessible across care transitions. Advance Care Planning Australia and the ADHA have an active Discovery Project on interoperability. But as at mid-2026, ACP upload to My Health Record remains a voluntary action by either the consumer/resident or their GP — there is no mandatory share-by-default requirement for ACP documents, no technical standard for ACP document format that most aged care CIS vendors implement, and no systematic enforcement of ACP portability under the Aged Care Act.

**4. The National Medicines Record: a 2027+ horizon.** The most transformative element of the medicines digitisation agenda — a real-time national medicines record visible to every prescriber and clinician — is still at design and consultation stage. Its completion depends on extending sharing-by-default obligations from online prescribers to all prescribers, and on integrating the eNRMC as a data source. The practical horizon is 2027 at the earliest. In the interim, medication reconciliation at care transitions — the moment when errors are most likely — still depends on paper charts, phone calls, and fax.

**5. Investment in national infrastructure without equivalent investment in provider capability.** The $598 million for My Health Record and $260 million for aged care ICT sustainment fund the government's own systems and platforms. They do not fund individual providers' software upgrades, integration implementation, or digital workforce development. Small and medium aged care providers — a significant segment of the sector, particularly in rural and regional areas — lack the capital and operational capacity to implement integrations even when the technical specifications exist.

**6. ACQSC enforcement depends on data that doesn't yet exist.** The enforcement architecture created by the Aged Care Act 2024 — chemical restraint monitoring via SIRS, medication management quality indicators in the Star Ratings, care minutes compliance — all require reliable, accessible, real-time data. But if the provider's care management system is not integrated with My Health Record, the ACQSC's audit capability is limited to what documents have been manually uploaded. The Inspector-General's finding (Report 032) that transformation is "disparate and disconnected" is directly reproduced in the digital domain: the enforcement framework and the digital infrastructure are advancing on different timelines.

---

## Threads to Branch Into Next

1. **Health Workforce Australia reconstitution and the health workforce planning gap** — the aged care workforce crisis (Report 023) and the clinical shortage issues identified across the series have a common root: the absence of a central health workforce planning body since Health Workforce Australia was abolished in 2014; proposals to reconstitute a national body; how HWA's abolition affects the pipeline for RNs, pharmacists, and allied health professionals in aged care

2. **Aged care Star Ratings and quality measures in depth** — the five quality indicators published in Star Ratings (falls resulting in hospitalisation, pressure injuries, unplanned weight loss, restraint use, medication-related incidents) are the public-facing accountability mechanism for the sector; how data is collected and audited; whether the indicators are driving genuine quality improvement or strategic gaming; the antipsychotic/restraint use indicator as a direct link from Reports 031 and 032

3. **PHI at end of life: the hospital-aged care boundary in private coverage** — private health insurance ceases to pay aged care facility costs on permanent residential entry; but PHI remains relevant for acute hospital episodes (medication-related admissions, falls fractures) that residents cycle through; the interaction between PHI hospital cover and aged care funding for the ~40% of residents who hold hospital cover on entry

4. **The Active Script List and electronic prescribing infrastructure** — the eNRMC sits on the broader ePrescribing ecosystem including the Active Script List (ASL), the electronic prescribing legislation, and the Schedule 8 controlled drugs monitoring systems (state-territory DORA/SONDA databases); how these interact in an aged care context and what happens with the 1 December 2026 transition

5. **Aged care financial governance and the RAD capital pool** — the Refundable Accommodation Deposit (RAD) pool, now subject to mandatory disclosure under the Aged Care Act 2024, represents a multi-billion dollar pool of resident capital managed by providers; financial compliance audits by the ACQSC; sustainability risk and its quality implications

---

## Sources

- [My Health Record — Statistics and Insights February 2026 | Australian Digital Health Agency](https://www.digitalhealth.gov.au/sites/default/files/documents/mhr-february-2026-statistics-landscape.pdf)
- [My Health Record | Department of Health, Disability and Ageing](https://www.health.gov.au/topics/health-technologies-and-digital-health/my-health-record)
- [My Health Record for healthcare providers | ADHA](https://www.digitalhealth.gov.au/healthcare-providers/initiatives-and-programs/my-health-record)
- [Residential aged care | ADHA](https://www.digitalhealth.gov.au/healthcare-providers/residential-aged-care)
- [Electronic National Residential Medication Charts (eNRMC) — Further Extension to timeframes for electronic prescribing | Department of Health, Disability and Ageing](https://www.health.gov.au/news/electronic-national-residential-medication-charts-enrmc-further-extension-to-timeframes-for-electronic-prescribing)
- [Electronic National Residential Medication Chart | Australian Commission on Safety and Quality in Health Care](https://www.safetyandquality.gov.au/our-work/medication-safety-and-quality/electronic-medication-charts/electronic-national-residential-medication-chart)
- [eNRMC — Conformance status tracker | Department of Health, Disability and Ageing](https://www.health.gov.au/resources/publications/electronic-national-residential-medication-charts-enrmc-conformance-status-tracker)
- [Modernising My Health Record (Sharing by Default) Act 2025 FAQ | Department of Health, Disability and Ageing](https://www.health.gov.au/sites/default/files/2025-02/frequently-asked-questions-modernising-my-health-record-sharing-by-default-act-2025_0.pdf)
- [Better access to health information | ADHA](https://www.digitalhealth.gov.au/healthcare-providers/initiatives-and-programs/better-access-to-health-information)
- [Australia to build National Medicines Record | Healthcare IT News](https://www.healthcareitnews.com/news/anz/australia-build-national-medicines-record)
- [Budget 2026: Australia funds $400M more for My Health Record | Healthcare IT News](https://www.healthcareitnews.com/news/anz/budget-2026-australia-funds-400m-more-my-health-record)
- [Budget targets My Health Record, data sharing and ICT upgrades | Pulse+IT](https://www.pulseit.news/australian-digital-health/budget-targets-my-health-record-data-sharing-and-ict-upgrades/)
- [Aged care digital reform | Department of Health, Disability and Ageing](https://www.health.gov.au/our-work/aged-care-reforms/aged-care-digital-reform)
- [Aged Care Clinical Information System (ACCIS) Standards | ADHA](https://www.digitalhealth.gov.au/standards/aged-care-clinical-information-system-accis-standards)
- [Aged Care Data and Digital Strategy 2024–2029 | Department of Health, Disability and Ageing](https://www.health.gov.au/resources/collections/aged-care-data-and-digital-strategy-2024-2029)
- [The Australian aged care data landscape: Gaps, opportunities and future directions | AEHRC/CSIRO (March 2025)](https://aehrc.csiro.au/wp-content/uploads/2025/03/25-00026_HB_REPORT_AEHRCAgedCareDataLandscape_WEB_250306-compressed.pdf)
- [Digital maturity centre stage at ITAC 2025 | Australian Ageing Agenda](https://www.australianageingagenda.com.au/technology/digital-maturity-centre-stage-at-itac-2025/)
- [Digital Maturity in Aged and Community Care | Ageing Australia (ACIITC)](https://ageingaustralia.asn.au/aciitc-reports/digital-maturity-in-aged-and-community-care/)
- [Advance care planning and My Health Record | ADHA](https://www.digitalhealth.gov.au/initiatives-and-programs/my-health-record/whats-inside/advance-care-planning)
- [Government grants extra eNRMC reprieve | The Weekly Source](https://www.theweeklysource.com.au/the-latest-hurdle-in-aged-cares-digital-rollout/)
- [Australia: Budget Bites — Digital Health | Baker McKenzie (2026)](https://www.bakermckenzie.com/en/insight/publications/2026/05/australia-budget-bites-digital-health)
- [New report provides snapshot of digital health in aged care | CSIRO News (March 2025)](https://www.csiro.au/en/news/All/News/2025/March/New-report-provides-snapshot-of-digital-health-in-aged-care)
