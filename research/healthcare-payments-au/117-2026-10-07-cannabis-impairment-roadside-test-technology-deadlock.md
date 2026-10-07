# The Impairment Test That Doesn't Exist Yet: Cannabis Driving Detection Technology and Australia's Reform Deadlock

**One-line summary:** Eight years after Australia's National Drug Driving Working Group set a goal of developing an "evidentiary impairment test," no jurisdiction anywhere in the world has validated and deployed a technology that can reliably distinguish cannabis-impaired from unimpaired drivers at the roadside — and that gap is the single largest technical blocker to Australia's drug-driving reform.

**Why this follows from yesterday:** Report 116 documented how every Australian jurisdiction that declined to reform drug-driving laws — the ACT, Queensland, and implicitly SA, WA, and NT — cited the absence of a validated roadside impairment test as justification for maintaining zero tolerance. Even NSW's 50 ng/mL threshold scheme is a pragmatic compromise in the absence of that technology, not evidence-based policy. The question is: when, if ever, will the technology exist?

---

## Background

Australia operates the world's most intensive roadside drug testing program by volume. NSW Police conducted 677,494 roadside oral-fluid tests between 2019 and 2023 alone. Every Australian state and territory has used presence-based oral-fluid testing since at least 2007, a decade before any other jurisdiction globally.

The device used in most of that testing — the Securetec DrugWipe — detects the presence of THC in oral fluid. It does not measure THC concentration precisely. It does not assess cognitive or psychomotor function. It cannot tell whether the person swabbed is currently impaired. Its field performance includes approximately 5% false positives and 16% false negatives.

The fundamental limitation is pharmacological, not technological. Unlike alcohol, where a 0.05 g/100mL blood-alcohol concentration (BAC) has been validated over decades as having a predictable relationship to crash risk, no equivalent threshold has been established for THC. The Lambert Initiative for Cannabinoid Therapeutics at the University of Sydney confirmed in a 2021 systematic review that blood and oral-fluid THC concentrations are "relatively poor or inconsistent indicators of cannabis-induced impairment." A 2026 review by Metrik, Bush, Gunn, and McCarthy in *Current Addiction Reports* reached the same conclusion: "More research focused on sensitive biomarkers combined with technologically-advanced behavioral methods is needed to improve the precision and accuracy in determining cannabis-induced driving impairment."

The legal consequence is stark: Australia's drug-driving system convicts people based on a biomarker that its own scientific establishment has conceded does not reliably measure impairment. And the technology that would allow a different approach does not yet exist in deployable form.

---

## Key Findings

### 1. The Biomarker Problem Is Not a Minor Research Gap — It Is a Fundamental Scientific Barrier

The difficulty of developing a cannabis impairment test reflects genuine pharmacological complexity, not merely regulatory caution or vendor delay.

THC (delta-9-tetrahydrocannabinol) is highly fat-soluble. Unlike alcohol, which is water-soluble and distributes relatively predictably across biological fluids, THC deposits in fat tissue and is released slowly over time. A regular user who last consumed cannabis 36 hours ago may still produce a positive oral-fluid or blood test while being completely unimpaired. Conversely, a naive user who consumed cannabis two hours ago may have a falling THC concentration and still be substantially impaired.

This pharmacokinetic variability means:
- No single concentration threshold can simultaneously protect against impaired naive users and avoid penalising unimpaired regular users
- The relationship between THC concentration and impairment is modified by body mass, frequency of use, method of consumption, tolerance development, and individual genetic variation in cannabinoid receptors
- Published studies consistently find the correlation between oral-fluid THC and driving performance to be "weak" or "inconsistent"

NHTSA's Dr. Jeffrey Michael stated the federal US agency's position directly: "The available evidence does not support the development of an impairment threshold for THC in blood." The US has no federally endorsed per se standard for cannabis driving. The states that have enacted 2 or 5 ng/mL per se laws did so without scientific validation equivalent to BAC law; research has documented that regular users routinely exceed those thresholds days after last use despite showing no impairment.

### 2. The Breath-Test Pathway: Research Prototypes, Not Deployable Products

The most actively pursued technological pathway for cannabis impairment detection is breath analysis — analogous to the alcohol breathalyzer model. As of October 2026, multiple teams are developing prototypes, but none has been approved for law enforcement use.

**Cannabix Technologies / University of Florida:** This Canadian company has partnered with University of Florida scientists to develop a handheld device detecting THC in exhaled breath. The device measures THC at extremely low concentrations — exhaled breath carries far less THC than oral fluid or blood. The goal was a first prototype by 2025, with development continuing as of 2026.

**University of South Wales (UK, June 2026):** A University of South Wales researcher announced progress on a different approach: 3D-printed test cartridges embedded with "Fast Blue" colour-reactive chemical dyes that undergo distinct colour changes when exposed to cannabinoids in exhaled breath. The approach is rapid and potentially inexpensive, but has not been tested in road-side conditions or validated against impairment.

**Virginia Commonwealth University (VCU):** A separate academic team has developed ion mobility spectrometry approaches to THC breath detection. The work has produced proof-of-concept findings but has not progressed to prototype validation.

The core challenge for all breath-based approaches is that breath THC concentrations are measured in picograms per litre — orders of magnitude lower than oral-fluid concentrations — requiring extremely sensitive detection chemistry and carefully controlled sample collection to prevent contamination.

Critically, even if breath-based THC detection becomes technically feasible, it would still only detect *presence*, not *impairment*, unless a validated impairment threshold could be established for breath THC — the same scientific problem that invalidates oral-fluid per se laws.

### 3. Eye-Tracking and Ocular Impairment Technology: The Most Promising Near-Term Approach

The most scientifically defensible pathway to impairment testing may bypass THC biomarkers entirely and directly measure neurological function — specifically ocular motor function, which cannabis disrupts in measurable ways.

**OcuPro (Oculogica, USA):** The OcuPro device conducts a sub-60-second non-invasive test measuring pupil size, position, and dynamics in response to standardised visual stimuli. Oculogica reports it has been clinically validated to correlate with cannabis usage and impairment. The device has been tested in research settings but has not been adopted by any law enforcement agency.

**Gaize (USA):** Gaize has developed a virtual reality headset that automates the Drug Recognition Expert (DRE) protocol — a multi-step clinical assessment of impairment developed in the 1980s that is still used by specially trained police officers in the United States. The DRE protocol already includes ocular tests (nystagmus, pupil size response) and Gaize automates these, removing inter-officer variability. The device detects impairment from cannabis, alcohol, and other substances. It has been trialled in research contexts but has not been certified for use as legal evidence in any jurisdiction.

**The ocular advantage:** The scientific rationale for ocular-based testing is stronger than for biomarker testing. Cannabis disrupts cannabinoid receptors in the oculomotor system, producing measurable changes in pupil response, smooth pursuit eye movements, and saccadic accuracy. These effects correlate more closely with current impairment than THC concentration in oral fluid. The limitation is that ocular tests can be affected by lighting conditions, individual variation in baseline ocular function, and other pharmacological agents.

### 4. Behavioral and Cognitive App Technology: DRUID's February 2026 Validation Milestone

The DRUID app (Druid, Inc., USA) takes a different approach entirely: measuring impairment through a four-task battery of behavioral tests assessing reaction time, decision-making accuracy, hand-eye coordination, time estimation, balance, and divided attention. The app integrates hundreds of measurements to produce a 0–100 impairment score.

DRUID has more peer-reviewed validation than any other cannabis impairment tool:
- A Johns Hopkins School of Medicine study found it was "the most sensitive measure of impairment" available, capable of distinguishing different levels of cannabis-induced impairment from different THC doses across controlled cannabis administration sessions
- Two further published peer-reviewed studies have validated its accuracy

In **February 2026**, new research results were published demonstrating that DRUID's algorithm can reliably distinguish between alcohol-induced and cannabis-induced impairment, analysing data from nearly 600 supervised test sessions. This is technically significant: previous impairment tools could assess *whether* impairment was present but not its likely cause, limiting their usefulness in a legal context where the substance must be identified.

DRUID's limitation for law enforcement use is practical rather than scientific: it requires a cooperative, consenting subject who actively performs the tasks — unlike a breath test or oral swab, which can be conducted with a less cooperative subject. The app is primarily positioned as a self-assessment tool that users can run before deciding whether to drive.

### 5. Victoria's $4.9 Million Trial: A Technology Evaluation That Was Never Actually Conducted

Victoria's Swinburne University driving trial, funded at $4.9 million and commenced August 2024, was promoted as the world's first trial assessing medicinal cannabis patients' driving performance on a closed circuit. As of October 2026, it is a significant missed opportunity.

The trial's original scope included evaluation of impairment-testing technologies — the component most directly relevant to policy. This was removed due to budget constraints before the trial began. The trial assesses driving performance (steering, braking, speed control, distraction handling) but does not evaluate whether any specific technology could have detected the impairment it measures.

The trial is also delayed: the 18-month timeline would have produced findings by early 2026, but the report is not expected until 2027. State Greens politician Rachel Payne raised the absence of results in the Victorian Legislative Council in June 2026, describing the government as "kicking the research can down the road."

The practical implication: Victoria will have, by 2027, evidence about whether medicinal cannabis patients drive differently than controls — but will have no corresponding evidence about what technology could have identified those differences at the roadside. The policy gap remains unbridged.

### 6. Australia's Second-Generation Framework: Eight Years of Unresolved Ambition

In 2017, the Australian Government commissioned a national scoping study on roadside drug testing. The National Drug Driving Working Group (NDDWG) produced its "Second Generational Approach to Roadside Drug Testing" report in 2018, which was endorsed by the Transport and Infrastructure Senior Officials' Committee. The report's aspirations were clear: move from presence-based testing to an evidentiary roadside test with no further laboratory testing required — analogous to the breathalyzer's role in alcohol enforcement.

The NDDWG meets biannually and continues to operate. Its ambitions are unchanged. The technology it was hoping to certify has not appeared.

Australia's position as the global leader in presence-based drug testing volume does not translate into leadership on impairment-based testing. The country's policy infrastructure — the NDDWG, the Australian Road Research Board, state forensic science agencies — is oriented toward improving the accuracy, speed, and deterrence value of presence-based testing, not toward the more difficult and more expensive task of developing and legally certifying impairment tests.

### 7. What Certification Would Actually Require

Even if a technology were scientifically validated, deploying it for law enforcement in Australia would require:

1. **Analytical performance standards**: Agreed limits of detection, false-positive and false-negative rates, and matrix effects for the specific device
2. **Legislative amendment**: All Australian state and territory road transport acts would need to be amended to recognise impairment evidence from the device as legally admissible
3. **Chain of custody and evidentiary standards**: Police procedures for device operation, sample handling, calibration records, and output interpretation would need to be codified
4. **Judicial acceptance**: Prosecution and defence testing in courts before a consistent evidentiary baseline is established — a process that has taken decades for alcohol testing and has generated significant litigation
5. **Training infrastructure**: Police trained not merely in device operation but in the scientific basis of its findings and their limitations — essential for cross-examination survival

This pipeline means that even if a device achieved scientific validation in 2026 or 2027, deployment at Australian roadsides would likely not occur before 2030 at the earliest, assuming accelerated regulatory pathway.

The ACT Government's March 2026 decision to maintain zero tolerance — explicitly noting that "detecting THC is not the same as proving a driver is impaired" but that no validated tool exists — is the most direct policy statement of where this leaves the law: presence-based enforcement continues not because it is defensible but because the alternative does not yet exist.

---

## Tensions and Open Questions

**1. Is breath detection actually more useful than oral-fluid detection?**
Even if THC breath detection becomes technically feasible, it measures presence not impairment. The core scientific problem — that no THC concentration reliably predicts impairment — applies to breath as much as to oral fluid. A breath test would reduce the window of detection (THC clears breath faster than oral fluid), but would not resolve the impairment question.

**2. Can behavioral testing become legally defensible?**
DRUID's validation evidence is stronger than any biomarker approach, but it depends on subject cooperation and produces a continuous score rather than a binary pass/fail. Courts have been slow to accept novel impairment evidence. The path from a scientifically validated behavioral score to a legislative per se standard is not straightforward.

**3. Is Victoria's trial actually evaluating the right question?**
The Swinburne trial tests whether medicinal cannabis patients drive differently — but the policy question is whether a law enforcement tool can detect when they are driving differently. Without technology evaluation, the trial can inform clinical guidance but not enforcement reform.

**4. Is Australia's NDDWG framework still fit for purpose?**
The NDDWG was established to develop a "second generation" testing framework. Eight years later, it has not produced one. The question is whether the framework lacks resources, legal mandate, or technology — or whether the underlying science simply hasn't delivered.

**5. Does any jurisdiction's experience offer a model?**
The Netherlands introduced tolerance levels for prescribed drugs (including cannabis) based on impairment evidence and clinical pharmacology, not detection thresholds, in its drug-driving law. This approach relies on expert clinical evidence rather than automated roadside technology — a different pathway that does not require a validated device, but does require extensive forensic toxicology infrastructure.

---

## Threads to Branch Into Next

1. **The Netherlands drug-driving model**: The only jurisdiction that has implemented a drug-driving framework explicitly based on impairment probability rather than detection thresholds, recognising that some patients cannot be prosecuted for driving impaired because their prescribed medicine's effect cannot be separated from therapeutic use at the roadside. Its architecture may offer Australia a feasible pathway without requiring a validated impairment device.

2. **Commercial driver health standards and centrally acting medicines**: Heavy vehicle operators face a tripartite compliance burden — NHVR heavy vehicle standards, state drug-driving law, and workplace WHS requirements — with no cohesive framework for how prescribed cannabis, opioids, or benzodiazepines interact with each. The absence of impairment technology is acutely felt here.

3. **SA, WA, and NT's policy positions on drug-driving reform**: Three jurisdictions with significant rural and First Nations populations have not publicly committed to any drug-driving reform pathway. Their political calculus — particularly in WA, where the mining and transport industries create both commercial driver exposure and employer interest in drug testing — warrants separate examination.

4. **The Drug Recognition Expert (DRE) protocol in Australia**: The US-developed DRE protocol offers an impairment-based assessment framework already used by police in the US and UK without requiring automated technology. Some Australian jurisdictions have explored it. Its deployment and limitations in an Australian context — including training costs and cross-examination vulnerability — deserve examination.

5. **Cannabis and road crash data — the Australian evidence gap**: Australia has extensive drug-driving detection data but limited data linking cannabis detection to crash causation. The road safety case for zero-tolerance laws rests partly on this gap. What research does exist — including the Crash Risk Assessment (CRAA) studies — and what would it take to generate a definitive evidence base?

---

## Sources

- Lambert Initiative for Cannabinoid Therapeutics, University of Sydney: [THC in blood and saliva are poor measures of cannabis impairment, December 2021](https://sydney.edu.au/news-opinion/news/2021/12/02/thc-blood-saliva-poor-measures-cannabis-impairment-lambert-study.html)
- Metrik et al., *Current Addiction Reports*, 2026: recent advances in cannabis-impaired driving science — referenced in PubMed: [PMC article](https://pmc.ncbi.nlm.nih.gov/articles/PMC12670588)
- Sydney Criminal Lawyers: [Roadside Drug Testing Devices Are Unreliable, Study Reveals](https://www.sydneycriminallawyers.com.au/blog/roadside-drug-testing-devices-are-unreliable-study-reveals/)
- University of South Wales, June 2026: [USW researcher working on developing fast-working cannabis breathalyser](https://www.southwales.ac.uk/news/2026/june/usw-researcher-working-on-developing-fast-working-cannabis-breathalyser-/)
- Cannabis Business Times: [Alcohol Countermeasure Systems Announces Development of Breath Test for Cannabis](https://www.cannabisbusinesstimes.com/industry-headlines/news/15696564/alcohol-countermeasure-systems-announces-development-of-breath-test-for-cannabis)
- OHS Online, September 2025: [Eye Tracking Tech Offers Alternative Approach to Impairment Screening](https://ohsonline.com/Articles/2025/09/19/Eye-Tracking-Tech-Offers-Alternative-Approach-to-Impairment-Screening.aspx)
- PatSnap Synapse: [Oculogica uses eye-tracking tech for new OcuPro roadside cannabis test](https://synapse.patsnap.com/news-detail/0c43a9ee-d2ef-3102-aa7d-fedafc4831e0-oculogica-uses-eye-tracking-tech-for-new-ocupro-roadside-cannabis-test)
- DRUID App / Impairment Science Inc: [Research White Paper](https://cdn.document360.io/777484ac-1e29-4520-a9ea-e12737fa1943/Images/Documentation/Research-Druid-WP.pdf)
- Cannabis Tech: [DRUID Cannabis Impairment Assessment](https://cannabistech.com/articles/cannabis-impairment-assessment/)
- Center for Technology and Behavioral Health (C4TBH): [A Paradigm Shift in Impairment Testing for Cannabis: The DRUID App](https://www.c4tbh.org/a-paradigm-shift-in-impairment-testing-for-cannabis-the-druid-app/)
- Inside State Government, 21 January 2026: [Medicinal cannabis driving trial on track — Victoria/Swinburne](https://www.insidestategovernment.com.au/medicinal-cannabis-driving-trial-on-track/)
- Rachel Payne MLC: [Medicinal Cannabis Driving Trial: Where's the Update?](https://rachelpayne.com.au/medicinal-cannabis-driving-trial-wheres-the-update/)
- High Times: [Study to Determine Impact of Cannabis on Driving Ability Delayed](https://hightimes.com/news/study-to-determine-impact-of-cannabis-on-driving-ability-delayed/)
- Australian Infrastructure Department: [Roadside Drug Testing Scoping Study](https://www.infrastructure.gov.au/department/media/publications/roadside-drug-testing-scoping-study)
- Australian Infrastructure Department: [Australia's Second Generational Approach to Roadside Drug Testing, 2018](https://www.infrastructure.gov.au/infrastructure-transport-vehicles/road-transport-infrastructure/safety/publications/2018/second-gen-roadside-drug-testing)
- National Roads Safety Partnership Program: [Roadside Drug Testing](https://www.roadsafety.gov.au/sites/default/files/2019-11/roadside-drug-testing.pdf)
- Northern Territory Parliament: [Tabled Paper 19 — Australia's Second Generational Approach to Roadside Drug Testing](https://parliament.nt.gov.au/committees/previous/RAB/tabled-papers/Tabled-Paper-19-Australias-second-generational-approach-to-roadside-drug-testing.pdf)
- AFPA Discussion Paper, August 2025: [Opposition to Proposed ACT Drug Driving Law Reform for Medicinal Cannabis Patients](https://afpa.org.au/wp-content/uploads/2025/08/AFPA-Discussion-Paper_-Opposition-to-Proposed-ACT-Drug-Driving-Law-Reform-for-Medicinal-Cannabis-Patients.pdf)
- Region.com.au: [Medicinal cannabis driving reform hits roadblock as government says technology isn't ready (ACT)](https://region.com.au/medicinal-cannabis-driving-reform-hits-roadblock-as-government-says-technology-isnt-ready/1004079/)
- PubMed: [The failings of per se limits to detect cannabis-induced driving impairment: Results from a simulated driving study](https://pubmed.ncbi.nlm.nih.gov/33544004/)
- VCU/WVTF: [VCU team creating roadside breathalyzer for marijuana](https://www.wvtf.org/news/2023-09-21/vcu-team-creating-roadside-breathalyzer-for-marijuana)
