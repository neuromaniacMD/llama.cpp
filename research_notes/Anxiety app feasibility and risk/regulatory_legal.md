# Regulatory, Legal, Privacy and Safety Risks for an Evidence-Based Anxiety App (as of November 2026)

Notes compiled 2026-11-10. Several primary sites (orrick.com, bfarm.de) were unreachable from the research environment. Some figures therefore come from search-engine summaries of those pages or from secondary sources, and they are flagged as such. Items marked "(not re-fetched this session)" cite primary documents known to exist whose text was not re-verified in this session.

---

## 1. US FDA: general wellness vs. SaMD, enforcement discretion, cleared anxiety/depression devices, the Nov 2025 DHAC meeting and 2026 guidance, CMS DMHT codes

### Takeaway
An anxiety app can stay outside FDA regulation if it makes only general wellness claims ("manage stress", "relax") or acts as a low-risk self-management tool under FDA enforcement discretion. Once it claims to treat a diagnosed disorder such as GAD or panic disorder, it is a Class II device. The established route is a 510(k) under 21 CFR 882.5801, with reSET (De Novo, 2017) as the root predicate. Rejoyn and Daylight were both cleared this way. FDA has authorized no generative-AI mental health device. The Nov 6, 2025 Digital Health Advisory Committee (DHAC) meeting produced non-binding advice, and I found no generative-AI mental health guidance from FDA in 2026. Medicare DMHT codes (G0552–G0554) exist from 2025 and were extended to ADHD for 2026, but CMS itself says claims volume is low.

### Cited Findings
**General wellness and CDS guidance (Jan 6, 2026)**
- On January 6, 2026 FDA issued revised final General Wellness and Clinical Decision Support guidances without a comment period, superseding the 2019/2022 versions. The two-factor wellness test (low risk, and an intended use limited to general wellness) is unchanged. The main addition covers non-invasive sensors estimating physiological parameters such as HRV, blood pressure, SpO2 and glucose — [Covington](https://www.cov.com/en/news-and-insights/insights/2026/01/fda-issues-revised-guidance-on-general-wellness-products); [Jones Day](https://www.jonesday.com/en/insights/2026/01/a-relaxing-2026-fda-updates-general-wellness-and-clinical-decision-support-software-guidance); [King & Spalding](https://www.kslaw.com/news-and-insights/fda-updates-general-wellness-and-clinical-decision-support-guidance-documents)
- FDA expects general wellness product labeling to be "consistent with, and not exceeding" the wellness intended use. Some commentators read the revision as giving more leeway to qualify as unregulated wellness — [JD Supra summary](https://www.jdsupra.com/legalnews/fda-updates-general-wellness-and-7357589/); [FDA Law Blog, Jan 2026](https://www.thefdalawblog.com/2026/01/a-busy-day-in-the-cdrh-neighborhood-updates-to-the-cds-and-general-wellness-guidance-documents/)
- In the revised CDS guidance, time-criticality and level of automation now sit under Criterion 4 rather than Criterion 3 — [King & Spalding](https://www.kslaw.com/news-and-insights/fda-updates-general-wellness-and-clinical-decision-support-guidance-documents)
- None of the January 2026 commentary addresses mental health apps specifically. FDA's longstanding "Policy for Device Software Functions and Mobile Medical Applications" gives examples of enforcement discretion for software that helps patients with diagnosed psychiatric conditions maintain behavioral coping skills (not re-fetched this session) — [FDA guidance page](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/policy-device-software-functions-and-mobile-medical-applications)

**Cleared pathway for CBT-type therapy devices**
- 21 CFR 882.5801, "computerized behavioral therapy device for psychiatric disorders", is a Class II, prescription-only device delivering condition-specific behavioral therapy as an adjunct to clinician-supervised outpatient treatment. Its special controls require clinical data validating the therapy model, software documentation, and labeling that warns it is not a standalone therapy and does not replace medication — [21 CFR 882.5801 (Cornell LII)](https://www.law.cornell.edu/cfr/text/21/882.5801); [Federal Register classification, Dec 27, 2017](https://www.federalregister.gov/documents/2017/12/27/2017-27843/medical-devices-neurological-devices-classification-of-the-computerized-behavioral-therapy-device)
- The regulation was created by the De Novo grant for reSET (DEN160018) — [FDA DEN160018](https://www.accessdata.fda.gov/cdrh_docs/pdf16/DEN160018.pdf)
- Rejoyn (Otsuka/Click, MDD adjunct) was cleared by 510(k) K231209 with reSET as predicate, under 882.5801 — [FDA K231209 letter](https://www.accessdata.fda.gov/cdrh_docs/pdf23/K231209.pdf)
- Daylight (Big Health) was cleared by 510(k) K233872 on 08/30/2024 under 882.5801, product code SCP ("Computerized Behavioral Therapy Device For Anxiety Disorders") — [FDA 510(k) database K233872](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfpmn/pmn.cfm?ID=K233872)
- Big Health announced DaylightRx clearance (Sept 2024) as the first FDA-cleared digital treatment for GAD: adults 22+, prescription, 90-day CBT program, adjunct to usual care. The company reports over 70% remission in RCTs (company claim) — [Big Health](https://www.bighealth.com/news/us-fda-grants-clearance-for-daylightrx); [Psychiatric Times](https://www.psychiatrictimes.com/view/first-digital-treatment-for-generalized-anxiety-disorder-cleared-by-the-fda)
- Note on dates: the FDA database gives the decision date as Aug 30, 2024, while press coverage dates the clearance announcement to early Sept 2024 — [FDA K233872](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfpmn/pmn.cfm?ID=K233872); [Drug Topics](https://www.drugtopics.com/view/fda-clears-first-digital-therapeutic-for-treatment-of-generalized-anxiety-disorder)

**DHAC meeting on generative AI mental health devices (Nov 6, 2025)**
- On Nov 6, 2025 the DHAC met on "generative AI-enabled digital mental health medical devices". The case study was a hypothetical prescription LLM therapy chatbot for adult MDD. It was the committee's second meeting, after a 2024 meeting on generative AI generally — [Orrick](https://www.orrick.com/en/Insights/2025/11/FDAs-Digital-Health-Advisory-Committee-Considers-Generative-AI-Therapy-Chatbots-for-Depression); [Sidley](https://www.sidley.com/en/insights/newsupdates/2025/11/us-fda-and-cms-actions-on-generative-ai-enabled-mental-health-devices-yield-insights-across-ai)
- FDA said oversight would depend on intended use, level of autonomy and risk profile. Panelists discussed predetermined change control plans (PCCPs) for adaptive features, trial design (control arms, blinding), physician oversight and post-market monitoring. Recommendations are non-binding — [Hogan Lovells (hlc.com)](https://www.hlc.com/en/publications/fdas-digital-health-advisory-committee-weighs-guardrails-for-generative-ai-in-mental-health-devices); [FDA meeting brief summary](https://www.fda.gov/media/190450/download); [FDA 24-hour summary](https://www.fda.gov/media/189618/download); [FDA perspective slides](https://www.fda.gov/media/189835/download)
- At the time of the meeting FDA had authorized no AI-enabled devices for mental health, against more than 1,200 AI-enabled devices in other areas — [Becker's Behavioral Health](https://www.beckersbehavioralhealth.com/behavioral-health-government-policies/fda-panel-reviews-ai-tools-for-mental-health-use-9-notes/)
- A low-tier secondary site says the count was still zero in late 2026 and that no follow-up DHAC meeting on the topic had been scheduled. This is unverified against FDA listings — [Veisund](https://www.veisund.com/topics/fda-ai-mental-health-status)

**CMS DMHT codes**
- The CY2025 PFS created G0552 (supply of the device plus onboarding; contractor-priced) and G0553/G0554 (monthly treatment management, first 20 min and each additional 20 min) for FDA-cleared devices under 882.5801. They are billed incident to a practitioner's behavioral health treatment under a plan of care — [AAPC](https://www.aapc.com/blog/93026-medicare-implements-digital-mental-health-treatment-codes/); [CMS MLN909432 Behavioral Health Integration, Jan 2026](https://www.cms.gov/files/document/mln909432-behavioral-health-integration-services.pdf)
- The CY2026 PFS final rule (Federal Register Nov 5, 2025) extended G0552–G0554 to ADHD devices under 21 CFR 882.5803 — [Federal Register CY2026 PFS](https://www.federalregister.gov/documents/2025/11/05/2025-19787/medicare-and-medicaid-programs-cy-2026-payment-policies-under-the-physician-fee-schedule-and-other); [CMS MM14315 summary](https://www.cms.gov/files/document/mm14315-medicare-physician-fee-schedule-final-rule-summary-cy-2026.pdf); [DLA Piper on the proposed rule](https://www.dlapiper.com/en/insights/publications/2025/07/proposed-cy-2026-mpfs-rule-signals-support-for-digital-health-advancement)
- CMS stated in rulemaking that Medicare FFS claims for G0552–G0554 "have remained low in volume" since the codes were created — [Federal Register CY2026 PFS](https://www.federalregister.gov/documents/2025/11/05/2025-19787/medicare-and-medicaid-programs-cy-2026-payment-policies-under-the-physician-fee-schedule-and-other)
- G0553/G0554 may be billed only while the patient is actively using the device — [CureAdvantage (billing vendor)](https://cureadvantage.com/billing-g0552-dmht-devices-the-2025-compliance-playbook/)
- Per-patient revenue estimates of about $1,400–2,200/yr come from a billing-vendor blog and are not authoritative — [MD Revenue Group](https://mdrevenuegroup.com/blog/digital-mental-health-billing-cms-2026)

### Inferences
- **Positioning determines the regime:**
  - *Wellness:* "reduce everyday stress/worry" claims with no disorder named are unregulated.
  - *Non-device or enforcement discretion:* coping-skills support for people already diagnosed, with no treatment claim. FDA generally does not enforce here, but the boundary is policy, not statute.
  - *Device:* "treats GAD/panic disorder" is a Class II device. A 510(k) citing Daylight (K233872) or reSET/Rejoyn as predicate is the cheapest credible route. De Novo is needed only for a novel intended use or technology, such as a generative-AI therapist.
- DMHT codes pay only for devices cleared under 882.5801 or 882.5803. A wellness or enforcement-discretion app is ineligible, so FDA clearance is the price of Medicare reimbursement. Given low code uptake, that revenue is not proven.
- An LLM-driven anxiety "therapist" would face an unprecedented De Novo with likely RCT and PCCP expectations. No product has a precedent, so timeline risk is high.

### Gaps
- Freespira's exact pathway and 510(k) number were not confirmed in this session. From prior knowledge it was cleared by 510(k) for panic disorder (2013, as the Canary Breathing System) and later extended to PTSD, but this is unverified.
- No FDA draft or final guidance on generative-AI mental health devices dated 2026 was found.
- No 2026 G0552–G0554 utilization figures, and no CY2027 PFS changes to DMHT codes, were found.

---

## 2. US state AI-in-mental-health and companion-chatbot laws (2025–2026)

### Takeaway
Three types of state law now apply.
- **Therapy bans:** Illinois and Nevada (2025) bar AI from providing therapy or presenting as a mental health provider. Trackers report more 2026 additions, with conflicting lists.
- **Disclosure rules:** Utah HB 452 (2025) sets disclosure, data and advertising rules for mental health chatbots.
- **Companion-chatbot safety laws:** California SB 243 (effective Jan 1, 2026, with a private right of action) and New York (in force Nov 2025) require AI disclosure, suicide/self-harm detection and crisis referral, and protections for minors.

Any conversational AI feature therefore needs state-by-state gating and crisis protocols.

### Cited Findings
- Illinois (HB 1806, Wellness and Oversight for Psychological Resources Act, 2025) and Nevada prohibit AI from independently providing therapy or making therapeutic decisions. Nevada bars interactive AI from representing itself as a mental health provider — [Acuity multistate guide](https://acuity.news/regulation/state-ai-mental-health-laws-compliance-2026/); [psychology.com state map](https://psychology.com/ai-therapy/state-bans); [Illinois Lawyers blog](https://www.illinoislawyers.com/blog/openai-facing-8th-wrongful-death-lawsuit/)
- Utah HB 452 allows mental health chatbots subject to disclosure (stating clearly that the user is talking to AI, before use and when asked), limits on data sharing, and advertising rules — [Acuity](https://acuity.news/regulation/state-ai-mental-health-laws-compliance-2026/); [aimocs tracker](https://aimocs.com/guides/us-state-laws-on-ai-mental-health-chatbots-tracker)
- California SB 243 (companion chatbots) took effect Jan 1, 2026. It requires AI disclosure, suicide/self-harm detection and crisis referral protocols, and protections for minors, and it creates a private right of action. New York's AI companion law has been in force since Nov 2025 with similar crisis-detection and disclosure duties — [Acuity](https://acuity.news/regulation/state-ai-mental-health-laws-compliance-2026/); [Orrick, Apr 2026 (search summary; page unreachable)](https://www.orrick.com/en/Insights/2026/04/2026-State-Chatbot-Laws-Key-Provisions-and-Regulatory-Trends)
- California SB 1119 ("Adam's Law") was reportedly signed Sept 10, 2026. It builds on SB 243 with child-safety assessments and audits, with most duties from July 1, 2027. Single tracker, unverified — [psychology.com register, Sept 2026](https://psychology.com/ce/guides/ai-therapy-laws-by-state/)
- New York S9051B reportedly passed both chambers in June 2026 but was unsigned at the tracker's last update — [psychology.com register](https://psychology.com/ce/guides/ai-therapy-laws-by-state/)
- Trackers disagree on 2026 additions. Some list Rhode Island and Maine, and a 2026 wave in Colorado, Tennessee and Vermont, as bans or restrictions. Others classify them differently — [psychology.com map](https://psychology.com/ai-therapy/state-bans); [toolswitchhub tracker](https://toolswitchhub.com/articles/ai-chatbot-regulation-tracker-by-state); [onehundrednights](https://onehundrednights.com/article/ai-mental-health-laws-nonprofits/)
- Trackers mention a federal executive order aimed at preempting state AI laws with a carve-out for child-safety laws. Its effect on mental health chatbot laws is unclear — [psychology.com register](https://psychology.com/ce/guides/ai-therapy-laws-by-state/); [Lono Collective tracker](https://lonocollective.ai/regulations/)
- A separate Illinois bill would make tech companies liable for physical or monetary damages caused by chatbots (pending) — [Central Illinois Proud](https://www.centralillinoisproud.com/news/local-news/ai-safety-regulations-illinois/)

### Inferences
- A structured, non-generative CBT app (scripted content, no free-text "therapist") probably falls outside the Illinois and Nevada bans, which target AI delivering therapy. An LLM coach marketed as therapy would likely be barred in those states, or need licensed-clinician oversight.
- California SB 243 and New York's law apply to "companion" chatbots that sustain relationships. An anxiety app with an empathetic conversational agent could be caught by them. Crisis-detection, referral to 988 and AI-disclosure features should be built in regardless of positioning.
- The California private right of action is a direct litigation vector beyond AG enforcement.

### Gaps
- Exact penalty amounts were not verified this session. From prior knowledge, Illinois HB 1806 carries civil penalties of up to $10,000 per violation enforced by IDFPR and was signed Aug 2025, and Nevada AB 406 takes effect July 1, 2025. Both are unverified here.
- Primary statute text for the 2026 additions (CO, TN, VT, RI, ME) was not retrieved.
- The legal status and scope of the federal preemption executive order were not confirmed from a primary source.

---

## 3. FTC privacy enforcement, HIPAA applicability, and consumer health data laws (Washington MHMDA and others)

### Takeaway
Most direct-to-consumer anxiety apps are not HIPAA-regulated, but the FTC treats sharing mental health data with ad platforms as unfair or deceptive. BetterHelp ($7.8M, 2023), Cerebral (more than $7M, 2024) and GoodRx ($1.5M HBNR penalty, 2023) are the benchmarks. On Sept 9, 2026 the FTC rescinded its 2021 policy statement extending the Health Breach Notification Rule (HBNR) to health apps. The 2024 amended rule and Section 5 still apply. Washington's My Health My Data Act, with its private right of action, is the sharpest state-level exposure, and class actions began in 2025–2026.

### Cited Findings
- **BetterHelp:** the FTC finalized an order in July 2023 (proposed March 2023) banning it from sharing health data for advertising and requiring $7.8M for consumer refunds, after it disclosed sensitive mental health data to Facebook, Snapchat and others — [FTC final approval, July 2023](https://www.ftc.gov/news-events/news/press-releases/2023/07/ftc-gives-final-approval-order-banning-betterhelp-sharing-sensitive-health-data-advertising); [FTC March 2023 release](https://www.ftc.gov/news-events/news/press-releases/2023/03/ftc-ban-betterhelp-revealing-consumers-data-including-sensitive-mental-health-information-facebook); [case page](https://www.ftc.gov/legal-library/browse/cases-proceedings/2023169-betterhelp-inc-matter)
- **Cerebral:** a proposed order in April 2024 barred use or disclosure of sensitive data for advertising and required more than $7M: about $5.1M in refunds for deceptive cancellation, plus a $10M civil penalty suspended after a $2M payment — [FTC, Apr 2024](https://www.ftc.gov/news-events/news/press-releases/2024/04/proposed-ftc-order-will-prohibit-telehealth-firm-cerebral-using-or-disclosing-sensitive-data)
- **GoodRx:** in Feb 2023 the FTC imposed a $1.5M civil penalty, its first enforcement under the HBNR, for undisclosed sharing of health data with Facebook, Google, Criteo and others — [FTC, Feb 2023](https://www.ftc.gov/news-events/news/press-releases/2023/02/ftc-enforcement-action-bar-goodrx-sharing-consumers-sensitive-health-info-advertising)
- **HBNR:** the rule was amended in April 2024 to confirm that it covers health apps and that unauthorized disclosure counts as a breach — [FTC 2023 Privacy & Data Security Update](https://www.ftc.gov/news-events/news/press-releases/2024/03/ftc-releases-2023-privacy-data-security-update); [FTC Mobile Health App Interactive Tool](https://www.ftc.gov/business-guidance/resources/mobile-health-apps-interactive-tool)
- **Rescission:** on Sept 9, 2026 the FTC rescinded its 2021 Policy Statement on health app breaches. Commentators say this narrows the HBNR's perceived reach, but the 2024 amended rule remains and Section 5 authority is unaffected — [National Law Review](https://natlawreview.com/article/ftc-reverses-course-health-app-privacy); [Hunton](https://www.hunton.com/privacy-and-cybersecurity-law-blog/ftc-rescinds-2021-policy-statement-on-health-app-data-breaches); [Epstein Becker Green](https://www.ebglaw.com/health-law-advisor/ftc-reverses-course-on-health-app-privacy); [HIPAA Journal](https://www.hipaajournal.com/ftc-rescinds-policy-statement-health-app-data-breaches/)
- **Recent FTC trend:** Hims & Hers is cited as a recent FTC enforcement trend alongside MHMDA actions — [Benesch](https://www.beneschlaw.com/insight/emerging-enforcement-trends-in-digital-health-data-privacy-lessons-from-washingtons-my-health-my-data-ftc-vs-hims-hers-and-uchealth-enforcement-actions/)
- **MHMDA class actions:** the first was filed Feb 10, 2025 against Amazon over SDK location data, in W.D. Wash. Some sources give 2026, so the date conflicts. A suit against cannabis retailer Uncle Ike's was pending as of May 2026. As of Oct 2026 no published court decision interprets the Act's key terms — [JD Supra](https://www.jdsupra.com/legalnews/first-washington-my-health-my-data-act-7112832/); [National Law Review](https://natlawreview.com/article/first-class-action-filed-under-washingtons-my-health-my-data-act-draws-parallels); [NatLawReview on Amazon](https://natlawreview.com/article/my-health-my-dollar-amazons-health-data-troubles-washington); [Wyrick](https://practicalprivacy.wyrick.com/blog/first-lawsuit-filed-under-washingtons-my-health-my-data-act)
- **MHMDA remedies:** private enforcement runs through the WA Consumer Protection Act (treble damages up to $25,000), and the AG can seek civil penalties of up to $7,500 per violation. This is a single secondary source — [privacyterms.io](https://privacyterms.io/washington-my-health-my-data-key-figures-2026); [Enzuzo guide](https://www.enzuzo.com/blog/washington-mhmda)
- **Other states:** Washington, Nevada and Connecticut have privacy laws written specifically for consumer health data as of 2026 — [recordinglaw.com](https://www.recordinglaw.com/us-laws/data-privacy-laws/washington-data-privacy-laws/)

### Inferences
- HIPAA applies only if the app is offered by or on behalf of a covered entity (provider or health plan) as a business associate. A prescription DTx distributed through providers, or a B2B deal with health systems, can bring it into scope. A pure DTC wellness app usually is not covered, but then FTC Section 5, the HBNR and state law apply instead.
- The practical control set is: no ad-tech pixels or SDKs that transmit health-related events, opt-in consent for any health-data sharing, and MHMDA-style separate consent plus a consumer health data privacy policy. Washington's private right of action makes SDK leakage the main class-action risk.
- The Sept 2026 HBNR rescission lowers, but does not remove, breach-notification exposure. Plaintiffs and state AGs remain active.

### Gaps
- Details of the Nevada (SB 370) and Connecticut consumer health data provisions, and the status of New York's Health Information Privacy Act (passed Jan 2025; status of signature or veto unknown), were not retrieved.
- No 2025–2026 FTC enforcement action against a mental health app specifically was found.

---

## 4. Litigation and safety risk: AI chatbot suicide/self-harm lawsuits, duty of care, crisis-handling requirements

### Takeaway
Courts are allowing product-liability and negligence claims against chatbot makers to proceed. Garcia v. Character Technologies survived a motion to dismiss in May 2025 and settled on Jan 7, 2026, together with related family suits. OpenAI faces Raine (Aug 2025), seven California state-court suits (Nov 2025), and at least eight federal suits as of May 2026. Plaintiffs frame chatbot outputs as a defective product, and courts have not accepted blanket First Amendment or Section 230 defences at the pleading stage.

### Cited Findings
- **Garcia, ruling:** in May 2025 the M.D. Fla. court largely denied Character.AI and Google's motion to dismiss, letting product-liability and wrongful-death claims proceed — [CourtDocket](https://courtdocket.org/garcia-v-character-ai-settlement-may-2025-ruling-and-fallout/); [aiwiki summary](https://aiwiki.ai/wiki/garcia_v_character_ai)
- **Garcia, settlement:** a mediated settlement on Jan 7, 2026 also covered related suits in Colorado, Texas and New York. Terms are confidential, with reported new safety features for under-18 users — [CourtDocket](https://courtdocket.org/garcia-v-character-technologies-ruling-and-settlement/); [Yahoo News](https://www.yahoo.com/news/articles/openai-flying-high-huge-legal-120000038.html)
- **Raine v. OpenAI:** filed Aug 2025 in San Francisco Superior Court over a teen suicide. It is reportedly still active, with no settlement found — [Fortune](https://dc.fortune.com/2025/08/27/adam-raine-openai-chatgpt-wrongful-death-lawsuit-lawyers); [ailawsuittracker](https://ailawsuittracker.com/ai-chatbot-harm-lawsuits/)
- **Seven California suits:** these allege wrongful death, assisted suicide, involuntary manslaughter and negligence, including in users with no prior mental illness — [Gulf News (AP)](https://gulfnews.com/world/americas/openai-faces-7-lawsuits-claiming-chatgpt-drove-people-to-suicide-delusions-1.500337099)
- **Federal murder-suicide case:** a federal judge refused to dismiss federal claims against OpenAI in a ChatGPT-linked murder-suicide case — [Courthouse News](https://www.courthousenews.com/openai-cant-duck-federal-claims-over-murder-suicide-tied-to-chatgpt/)
- **Count of suits:** as of May 2026 OpenAI was defending at least eight federal lawsuits over psychological harm and wrongful death, and was lobbying for liability thresholds — [Forbes, May 24, 2026](https://www.forbes.com/sites/jasonsnyder/2026/05/24/teens-are-dying-by-suicide-openai-lobbies-for-liability-at-100-dead/); [eMarketer](https://www.emarketer.com/content/openai-defends-chatgpt-amid-lawsuits-over-mental-health-harms)
- **Volume:** trackers count around 16 AI product-liability cases in 2026 — [ailawsuittracker product liability](https://ailawsuittracker.com/issues/product-liability/)
- **Statutory crisis protocols:** California SB 243 and New York's companion law require suicide/self-harm detection and crisis referral — [Acuity](https://acuity.news/regulation/state-ai-mental-health-laws-compliance-2026/)

### Inferences
- An anxiety app is likely to attract users at elevated suicide risk. Even a non-AI app faces negligence exposure if it fails to screen, escalate or signpost to 988 or emergency services. Generative features greatly increase that exposure, because outputs are unscripted and the product-defect theory is now judicially plausible.
- **Mitigations:**
  - Validated risk screening (e.g., PHQ-9 item 9 or C-SSRS) with hard-coded escalation.
  - No LLM free-text for crisis states.
  - Age gating.
  - Logging and audit trails.
  - Clinical safety governance (a hazard log in the style of UK DCB0129).
  - Product-liability insurance.
- Labeling as "wellness" does not protect against tort claims if the app in fact engages vulnerable users on mental health.

### Gaps
- No court decision on the merits establishing a duty of care for a mental health app was found. All key rulings are at the pleading stage.
- The current docket status of Raine and of the seven Nov 2025 suits was not verified from court records.

---

## 5. EU: MDR Rule 11, EU AI Act (incl. 2026 Digital Omnibus delay), GDPR; Germany DiGA; France PECAN; Belgium mHealth

### Takeaway
In the EU, a therapeutic anxiety app is almost always a medical device in Class IIa or higher under MDR Rule 11. That requires a notified body, roughly €60k–200k and 12–24 months. If it uses AI, it is also high-risk under the AI Act via Annex I. The 2026 Digital Omnibus pushed high-risk obligations to Dec 2, 2027 for Annex III and reportedly Aug 2, 2028 for Annex I products, though the dates still need checking against the Official Journal. Mental health data is GDPR Article 9 special-category data.

Germany's DiGA is the most mature reimbursement route, but it is selective:
- As of Sept 2026: 254 applications, 62 positive decisions, 131 withdrawn, 18 delisted.
- Average negotiated price is about €227 against about €544 manufacturer price in 2025.
- At least 20% of the price is outcome-linked from 2026.

France's PECAN gave its first therapeutic-DMD coverage only in July 2026.

### Cited Findings
**MDR**
- MDR Annex VIII Rule 11: software intended to provide information used for diagnostic or therapeutic decisions is Class IIa. It is IIb if such decisions could cause serious deterioration, and III if they could cause death or irreversible deterioration. Other software is Class I (not re-fetched this session) — [MDR 2017/745 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2017/745/oj); [Venitara on Rule 11](https://venitara.com/resources/articles/is-my-software-a-medical-device); [MedQara](https://veillemedqara.fr/en/blog/logiciel-dispositif-medical-regle-11)
- A pending EU MDR/IVDR simplification proposal would default clinical-benefit software to Class I, escalating only in serious situations. It is not adopted — [MedDeviceGuide](https://meddeviceguide.com/blog/eu-mdr-ivdr-simplification-proposal-2026-guide)
- **Class IIa cost and time:**
  - Notified body initial assessment €15k–40k. Total notified body fees are given elsewhere as €50k–200k.
  - Total initial compliance €60k–150k over 12–20 months.
  - Class IIa adds 12–24 months, or "more than a year", compared with self-certified Class I.
  - These are vendor estimates — [Megacert](https://www.megacert.net/blog/mdr-compliance-cost); [Quickbird Medical](https://quickbirdmedical.com/en/medical-device-mdr-risk-class-1-2a/); [SimplerQMS](https://simplerqms.com/eu-mdr/)

**EU AI Act and the Digital Omnibus**
- The provisional agreement on the Digital Omnibus on AI was reached May 7, 2026. It was reportedly adopted by Parliament (June 16) and Council (June 29), entered into force July 27, 2026, and published as Regulation (EU) 2026/1744. Sources differ by a few days on publication — [Sidley Data Matters, June 22, 2026](https://datamatters.sidley.com/2026/06/22/eu-lawmakers-reach-provisional-agreement-to-delay-key-eu-ai-act-obligations/); [Hogan Lovells](https://www.hlc.com/en/publications/eu-legislators-agree-to-delay-for-highrisk-ai-rules); [Usercentrics](https://usercentrics.com/knowledge-hub/eu-ai-act-high-risk-delay-article-50-transparency-consent/)
- **Deadlines:**
  - Annex III high-risk moves from Aug 2, 2026 to Dec 2, 2027.
  - Annex I (product-embedded, e.g., MDR devices) is reportedly moved to Aug 2, 2028.
  - Article 50 transparency stays on schedule (Aug 2026), with a watermarking reprieve for systems already on the market to Dec 2, 2026.
  - The "safety component" definition was narrowed.
  - Sources: [CSA Research Note](https://labs.cloudsecurityalliance.org/research/csa-research-note-eu-ai-act-omnibus-vii-deadline-delay-20260/); [Winston Taylor](https://www.winstontaylor.com/insights/ai-act-rules-on-high-risk-ai-delayed-as-ai-digital-omnibus-agreed); [DLA Piper](https://knowledge.dlapiper.com/dlapiperknowledge/globalemploymentlatestdevelopments/2026/The-Digital-AI-Omnibus-Proposed-deferral-of-high-risk-AI-obligations-under-the-AI-Act); [AI Policy Desk](https://www.aipolicydesk.com/blog/eu-ai-act-august-2026-whats-delayed-vs-what-applies)
- **AI Act structure (not re-fetched this session):**
  - Art. 6(1) makes an AI system high-risk where it is, or is a safety component of, a product under Annex I legislation (including MDR) that requires third-party conformity assessment.
  - Art. 5 prohibitions, applicable since Feb 2, 2025, include manipulative techniques and exploiting vulnerabilities, and emotion recognition in workplaces and education except for medical or safety reasons.
  - Art. 50 requires telling users they are interacting with AI.
  - Source: [AI Act, Reg. 2024/1689 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2024/1689/oj)
- **GDPR:** Art. 9 makes health data special-category data, processable only on specific grounds such as explicit consent (not re-fetched this session) — [GDPR (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2016/679/oj)

**Germany DiGA**
- **BfArM statistics as of Sept 9, 2026** (from a search summary of the BfArM page, which was unreachable directly):
  - 254 applications: 196 for provisional (fast-track) listing and 58 for permanent listing.
  - 62 positive decisions, 29 negative, 131 withdrawn, 14 in process.
  - 18 deleted from the directory.
  - Source: [BfArM DiGA "Interesting facts"](https://www.bfarm.de/EN/Medical-devices/Tasks/DiGA-and-DiPA/Digital-Health-Applications/Interesting-facts/_artikel.html)
- **GKV figures to Dec 31, 2025** (secondary sources): 74 DiGAs ever listed, 58 still listed (48 permanent, 10 provisional), 16 delisted. The average 2025 manufacturer price was €544 against an average negotiated price of €227 (factor 2.4). 2025 spend was about €170–171M (+61%), with about €400M cumulative — [DUX Healthcare market report 2026](https://dux-healthcare.com/en/knowledge/business-strategy/diga-market-report-2026/); [MTR Consult](https://mtrconsult.com/news/gkv-report-utilization-and-development-digital-health-application-diga-care-germany)
- **Recent listings:** 10 new DiGAs were added in the last 12 months, the latest on Sept 23, 2026 — [DiGA-Verzeichnis new DiGAs](https://www.diga-verzeichnis.de/en/new-digas)
- **Fast-track process:**
  - BfArM decides within 3 months of a complete application, extendable by 3 months.
  - Class I and IIa apps get 12 months (up to 24) of provisional listing to prove a positive care effect.
  - The manufacturer's free price applies in year 1. From month 13 the GKV-SV negotiated price applies, with arbitration if there is no agreement.
  - From 2026, at least 20% of the price must be success-dependent (outcome-linked).
  - Class IIb has been permitted since the DigiG reform.
  - Sources: [Quickbird DiGA pricing](https://quickbirdmedical.com/en/diga-price-negotiation-gkv/); [Gawel on outcome-based pricing and IIb](https://gawel.ch/insights/50-diga-outcome-based-pricing-digital-therapeutics/); [Medium: 4 years of fast-track](https://medium.com/digital-health-brief/the-fast-track-process-for-digital-health-applications-diga-4-years-of-experience-f53181c7a2b5)
- **Earlier price data (2020–mid-2024):** median initial price €514 per 3-month prescription, falling to a median of €221 after negotiation, and about 50% of listings were provisional — [JMIR/PMC 2024 analysis](https://pmc.ncbi.nlm.nih.gov/articles/PMC11393499/)

**France PECAN**
- **First therapeutic coverage:** in July 2026 the French Ministry of Health granted the first PECAN early coverage for a therapeutic DMD (Poppins Clinical, for dyslexia rehabilitation), capped at €780 per patient per year. Coverage lasts up to 12 months — [MTR Consult](https://mtrconsult.com/news/first-pecan-coverage-granted-therapeutic-digital-medical-device-france); [Odelle Technology](https://odelletechnology.com/france-opens-pecan-to-therapeutic-digital-medicine/)
- **Track record:** HAS issued 13 PECAN opinions from July 2023 to June 2026, and only telemonitoring had received favourable opinions before Poppins — [Odelle Technology 2026](https://odelletechnology.com/france-2026-why-reimbursement-route-selection-is-now-the-strategic-risk-for-medtech-ivd-digital-health-and-ai-companies/)
- **Cost sharing:** a decree of Aug 21, 2026, effective Jan 1, 2027, shifts DMD cost-sharing toward supplementary private insurers. Sources conflict on the 60/40 split — [Quickbird, France reimbursement change](https://quickbirdmedical.com/en/news/france-reimbursement-digital-therapies-supplemental-insurance/); [Quickbird PECAN](https://quickbirdmedical.com/en/pecan-france-diga-dmd/)

**Belgium**
- Belgium reimburses only at the top level of the mHealthBelgium pyramid. No further detail was found — [Ubiq Events](https://ubiqevents.com/insights/europe-digital-therapeutics-reimbursement-2026)

### Inferences
- **EU positioning:**
  - *Wellness:* stress or relaxation with no disorder claim, outside the MDR. GDPR Art. 9 still applies if mental health data is processed, and AI Act Art. 50 transparency applies to chatbots.
  - *Class I:* possible only if the software does not inform therapeutic decisions. Rule 11 makes this hard for a "treatment" claim, and the pending simplification could change that.
  - *Class IIa:* standard for DiGA-type anxiety DTx.
- An AI-driven Class IIa device would become AI Act high-risk via Annex I. The Omnibus gives roughly until Aug 2028 to comply with quality management, data governance, human-oversight and logging duties. Art. 5 prohibitions already apply, and persuasive or engagement-maximizing designs aimed at anxious users risk the "exploiting vulnerabilities" ban.
- **DiGA economics:** only about 25% of fast-track applications end in a positive decision (62 of 254, with 131 withdrawn). Realistic net reimbursement is about €200–250 per 90-day prescription after year 1, with 20% at risk on outcomes. Psychiatric indications historically make up the largest DiGA category (not quantified this session).

### Gaps
- DiGA application cost (BfArM fees, the evidence study, and Class IIa CE marking as a prerequisite) and specific anxiety DiGA prices (e.g., Velibra, Invirto, Mindable) were not found.
- The share of mental health DiGAs among those listed and delisted was not retrieved.
- Belgium mHealth pyramid level criteria and the current number of Level 3 apps were not found.
- The exact Official Journal reference and dates for the AI Omnibus were not verified (Reg. 2026/1744 per one secondary source).

---

## 6. UK: MHRA software/AI as a medical device, NICE Evidence Standards Framework, DTAC, NHS procurement

### Takeaway
The UK combines MHRA device regulation, NICE evaluation and NHS assurance (DTAC). Key 2026 developments:
- MHRA is moving to lifecycle monitoring of AI devices.
- The government accepted all 44 recommendations of the National Commission on AI regulation in healthcare (Oct 6, 2026).
- Draft guidance on AI device changes and PCCPs is expected by Dec 2026.

NICE has assessed digitally enabled therapies for anxiety (early value assessment HTE9, 2023) and NHS Talking Therapies digital front doors (HTE30, 2025). The ESF places anxiety CBT in its higher "treat a diagnosed condition" tier.

### Cited Findings
- **National Commission:** its report was published Sept 10, 2026, after input from more than 12,000 people. The government accepted all 44 recommendations on Oct 6, 2026. A draft implementation plan is due by the end of 2026 and a full plan by spring 2027. Draft guidance on managing changes to AI-enabled devices is due by Dec 2026 — [Fierce Biotech](https://www.fiercebiotech.com/medtech/uk-unveils-new-policy-constantly-monitor-ai-based-medical-devices); [Technology.org, Oct 6, 2026](https://www.technology.org/2026/10/06/uk-mhra-ai-medical-devices-continuous-monitoring/); [IZHC field notes](https://www.zhcinstitute.com/research/uk-health-ai-lifecycle-monitoring-field-notes/)
- **Lifecycle monitoring:** MHRA CEO Lawrence Tallon said AI medical devices will face continuous post-approval monitoring rather than a single pre-market check — [Fierce Biotech](https://www.fiercebiotech.com/medtech/uk-unveils-new-policy-constantly-monitor-ai-based-medical-devices)
- **AI Airlock:** the sandbox's Phase 3 focuses on post-market surveillance and lifecycle monitoring — [MHRA MedRegs blog, Oct 19, 2026](https://medregs.blog.gov.uk/2026/10/19/why-post-market-surveillance-is-a-priority-for-the-mhra-ai-airlock-programme/)
- **Pending legislation:** some reforms (direct device assessment powers, statutory sandboxes, mandatory UDIs) still need Parliament. A secondary source mentions draft Medical Devices (Amendment) Regulations 2026 covering PCCPs (unverified) — [techUK on MHRA Strategy 2030](https://www.techuk.org/insights/news/techuk-analysis-of-the-mhra-strategy-2030); [PatientGuard](https://patientguard.com/the-mhra-2026-regulatory-roadmap-explained/)
- **NICE ESF:** treatment tools (e.g., CBT for anxiety) sit in the highest-evidence tier, Tier C — [NICE ESF (corporate ecd7)](https://www.nice.org.uk/corporate/ecd7/resources/evidence-standards-framework-for-digital-health-technologies-pdf-1124017457605); [NICE ESF 2019 PDF](https://www.nice.org.uk/Media/Default/About/what-we-do/our-programmes/evidence-standards-framework/digital-evidence-standards-framework.pdf); [PMC paper on ESF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8236783/)
- **NICE anxiety evaluations:** NICE HTE9 (May 2023) is an early value assessment of digitally enabled therapies for adults with anxiety disorders. HTE30 (July 2025) covers digital front doors for NHS Talking Therapies. A 2026 JMIR Mental Health study of nine NICE digital mental health evaluations examined the strength of evidence — [JMIR Mental Health 2026](https://mental.jmir.org/2026/1/e85635); [PMC version](https://pmc.ncbi.nlm.nih.gov/articles/PMC13056029/)
- **Social care ESF:** NICE consulted on an adult social care version of the ESF until Sept 25, 2026 — [NICE blog](https://www.nice.org.uk/news/blogs/our-evidence-standards-framework-for-digital-care-technologies); [Digital Care Hub](https://www.digitalcarehub.co.uk/help-shape-evidence-standards-for-digital-care-technologies/)
- **DTAC:** the NHS DTAC sets standards (clinical safety, data protection, technical security, interoperability, usability) that adopters use before buying — [NHS AI & Digital Regulations Service adopter guidance](https://www.digitalregulations.innovation.nhs.uk/regulations-and-guidance-for-adopters/all-adopters-guidance/understanding-the-evidence-for-a-technology-before-adopting-it/pdf/)

### Inferences
- The UK route for an anxiety DTx usually runs through UKCA or a recognized CE mark, DTAC compliance, DCB0129 clinical safety documentation, and a NICE early value assessment or ESF Tier C evidence. NHS Talking Therapies is the main commissioning channel.
- Lifecycle monitoring and PCCP guidance will raise post-market obligations for any AI component from 2027.

### Gaps
- UK classification specifics were not verified this session: most standalone software is Class I under current UK MDR 2002, upclassification is proposed, and post-market surveillance regulations took effect June 2025 (from prior knowledge).
- No 2026 DTAC revision, and no NICE recommendations for specific anxiety products, were confirmed.
- No NHS procurement framework detail (e.g., pricing per Talking Therapies episode) was found.

---

## 7. Approximate compliance costs and timelines by pathway

### Takeaway
Order-of-magnitude figures:
- **US general wellness:** no FDA cost, but privacy (FTC and state law) and safety engineering costs remain.
- **US 510(k) under 882.5801:** FY2026 FDA fee $26,067 ($6,517 small business), plus the cost of a clinical study.
- **US De Novo:** FY2026 fee $173,782 ($43,446 small business), rising to about $191k in FY2027.
- **EU CE Class IIa:** about €60k–200k and 12–24 months.
- **DiGA:** BfArM review in 3–6 months after CE marking, then a 12–24 month provisional trial. Realistic negotiated price is about €220–230 per prescription.

The dominant cost in every regulated pathway is the pivotal RCT, which I could not quantify from sources.

### Cited Findings
- **FDA FY2026 fees** (Federal Register July 30, 2025, 90 FR 35895): De Novo $173,782 standard / $43,446 small business; 510(k) $26,067 / $6,517 — [Federal Register notice (govinfo)](https://www.govinfo.gov/content/pkg/FR-2025-07-30/html/2025-14412.htm); [FDA MDUFA fees page](https://www.fda.gov/medical-device-user-fee-amendments-mdufa); [RAPS](https://www.raps.org/resource/fda-unveils-fy-2026-user-fee-rates.html)
- **FDA FY2027 fees** (published July 30, 2026, per secondary source): De Novo $191,020 / $47,755 small business; 510(k) $28,653 / $7,163 — [Pure Global](https://www.pureglobal.com/news/fda-fy-2027-medical-device-user-fees); [MedDeviceGuide FY2027](https://meddeviceguide.com/blog/fda-medical-device-user-fees-fy-2027-mdufa-rate-table-guide)
- **MDUFA VI:** reauthorization for FY2028–2032 is under negotiation, with draft commitments discussed in Aug 2026 — [Exponent, Aug 14, 2026](https://www.exponent.com/article/fda-draft-mdufa-vi-could-signal-changes-medical-devices)
- **EU Class IIa:** €60k–150k over 12–20 months (Megacert), with notified body fees of €15k–40k, or €50k–200k in total — [Megacert](https://www.megacert.net/blog/mdr-compliance-cost); [Quickbird](https://quickbirdmedical.com/en/medical-device-mdr-risk-class-1-2a/)
- **DiGA timeline and price:** a 3-month BfArM review (+3), a 12–24 month provisional trial, and price negotiation of about 5 months. The 2025 average negotiated price was €227 — [Quickbird](https://quickbirdmedical.com/en/diga-price-negotiation-gkv/); [DUX](https://dux-healthcare.com/en/knowledge/business-strategy/diga-market-report-2026/)
- **DiGA investment case:** commentary questions whether DiGA development pays off given the price compression — [Rama on Healthcare](https://ramaonhealthcare.com/developing-a-diga-is-it-worth-the-investment/)
- **PECAN:** reimbursement for up to 12 months, with a €780/patient/yr cap in the first therapeutic case — [MTR Consult](https://mtrconsult.com/news/first-pecan-coverage-granted-therapeutic-digital-medical-device-france)

### Inferences
- **Rough planning ranges** (inference, combining fees with typical study scale):
  - *Wellness launch (US/EU/UK):* privacy and security program plus a clinical safety process, roughly low hundreds of thousands of dollars per year, with no regulatory submission.
  - *US 510(k) DTx:* typically 12–24 months including a clinical study. The FDA fee is minor next to an RCT of 200–400 participants, which is commonly a multi-million-dollar budget (unsourced estimate).
  - *EU Class IIa plus DiGA:* about 18–36 months from QMS build-out to permanent listing.
- Using the 882.5801 predicate chain (reSET, Rejoyn, Daylight) avoids the De Novo fee and the uncertainty of a novel classification. A generative-AI feature would likely forfeit that path.

### Gaps
- No sourced figures were found for total cost to bring a digital therapeutic to market, De Novo review timelines (MDUFA goal: 150 FDA days), DiGA application fees, NICE EVA cost, or UK conformity assessment costs.
- No source for typical pivotal RCT costs for mental health DTx.
