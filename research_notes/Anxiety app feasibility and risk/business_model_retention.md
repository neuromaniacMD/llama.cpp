# Business Model, Unit Economics, Distribution Channels, and Retention for Mental Health / Anxiety Apps (as of Nov 2026)

Method note: Research was done via web search (Nov 10, 2026). Direct page fetches of revenuecat.com and statnews.com were blocked by this session's network policy, so figures from those sites come from search-result summaries, RevenueCat's own summary pages as indexed, and third-party write-ups. Treat RevenueCat category figures as "verify against the primary report before publication." Many pricing/sales-cycle figures for the B2B channel come from vendor blogs and are flagged as low-confidence.

## 1. Retention and engagement benchmarks

### Takeaway
Real-world retention for unguided mental health apps is extremely low (median ~3.3% at day 30 in the most-cited panel study, 2019), and no newer large-scale independent study has replaced that benchmark; paid subscribers in Health & Fitness, by contrast, retain relatively well once converted, so the commercial problem is concentrated in the install-to-engaged/paid funnel, not in post-purchase churn.

### Cited Findings
- Baumel et al. (JMIR, 2019): panel-based usage analysis of 93 unguided, frequently installed mental health apps; median 15-day retention 3.9% (IQR 10.3%) and 30-day retention 3.3% (IQR 6.2%) — [JMIR / Baumel et al. 2019](https://doi.org/10.2196/14567); [PubMed](https://pubmed.ncbi.nlm.nih.gov/31573916/)
- Same study: day-30 retention was significantly higher for peer support (median 8.9%, n=2), mindfulness/meditation (median 4.7%) and tracker apps (median 6.1%) than breathing-exercise apps (median 0.0%) — [JMIR / Baumel et al. 2019](https://doi.org/10.2196/14567)
- A 2025 RCT on incentivising participation states that real-world mental health app retention often drops below 5% after 30 days — [PMC12089817 (2025)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12089817/)
- A 2025 review of digital mental health notes poor engagement is an even greater problem in real-world settings than in trials — [PMC12079407 (2025)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12079407/)
- Clinician-linked deployment changes the picture: a 2025 Frontiers study of a clinic-based app (Recovery Connect) reported 30-day (treatment) retention of 76.2% in Arizona clinics vs 65.8% for patients without app access (historical, non-randomized comparison; measures retention in care, not app use per se) — [Frontiers in Psychiatry 2025](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2025.1581298/full)
- Attrition is the "Achilles heel" of mental health digital therapeutics (review) — [PMC9380224](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9380224/)
- Pear's reSET-O feasibility study saw 91% dropout among patients completing 12 weeks — [PMC12314708](https://pmc.ncbi.nlm.nih.gov/articles/PMC12314708/)
- RevenueCat State of Subscription Apps 2026 (as summarized): Health & Fitness leads yearly subscriber retention (86.4% on the metric reported; note this is a yearly-subscriber metric, not a user retention metric) — [RevenueCat SOSA 2026](https://www.revenuecat.com/state-of-subscription-apps); [RevenueCat 2026 trends blog](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026). (The 86.4% figure was surfaced via search summary; the definition of the metric should be checked in the primary report.)
- Secondary analysis of RevenueCat 2026: ~73% of first-60-day revenue per install arrives in the first 14 days; Health & Fitness earns more per install in the first two weeks than any other category — [Singular summary of RevenueCat report](https://www.singular.net/blog/subscription-apps/) (secondary)
- Usage concentration: Calm and Headspace were the top wellness apps by revenue in 2024 (followed by Pokémon Sleep); Appfigures estimated 2023 US App Store/Play revenue of ~$77M (Calm) and ~$49M (Headspace) with two weeks of December remaining — [Appfigures, "Demand for Mental Health Apps is Almost Gone" (Dec 2023)](https://appfigures.com/resources/insights/20231215?f=4); [Appfigures (May 2024)](https://appfigures.com/resources/insights/20240510?f=3)
- Appfigures: mental health app downloads have declined since the 2020 peak (Calm ~-20%, Headspace ~-10% by 2021; ~-40% in 2022) while revenue rose (Calm +57%, Headspace +59% in 2022), i.e., leaders traded downloads for monetization — [Appfigures (Jan 2023)](https://appfigures.com/resources/insights/20230106?f=4); category demand described as "at an all-time low" in May 2024 — [Appfigures (May 2024)](https://appfigures.com/resources/insights/20240510?f=3)

### Inferences
- For planning, a new unguided anxiety app should assume single-digit day-30 active retention (3-5%) absent a clinical or human-support wrapper; clinician- or program-embedded delivery is the main lever shown to lift engagement.
- Category demand is mature and concentrated: incumbents (Calm, Headspace) dominate revenue, and organic category download volume is flat-to-declining, so a newcomer competes for a shrinking organic pool.
- Because most subscription revenue arrives in the first 14 days, the paywall/onboarding experience in days 0-7 determines most economics.

### Gaps
- No 2024-2026 independent, large-scale (panel-based) day-1/day-7/day-30 retention study for mental health apps was found; Baumel 2019 remains the reference.
- Could not access Adjust/AppsFlyer/Sensor Tower category-specific day-1/7/30 retention for Health & Fitness (2025-2026); the commonly cited generic figures (roughly D1 ~20-25%, D30 ~3-4% for health apps) could not be verified with a primary source in this session.
- No 2025-2026 Sensor Tower data on Calm/Headspace market share or download concentration found.

## 2. Consumer subscription economics (pricing, conversion, churn, CPI, LTV/CAC, ASO)

### Takeaway
Health & Fitness is among the best-converting subscription categories (median trial-to-paid ~38-40%) and is annual-plan dominated, but paid acquisition is expensive (Meta CPI for wellness ~$6-10 in the US, iOS CPIs rising), and with low organic demand the binding constraint is install-to-trial volume and CAC, not conversion once a trial starts.

### Cited Findings
- RevenueCat 2026 (via RevenueCat summary pages/search): median Health & Fitness trial-to-paid conversion 37.7%, top quartile >51.4%; RevenueCat 2025 reported median 39.9% and top decile 68.3% (the editions differ) — [RevenueCat SOSA 2026](https://www.revenuecat.com/state-of-subscription-apps); [RevenueCat SOSA 2025](https://www.revenuecat.com/state-of-subscription-apps-2025)
- Trial length (RevenueCat, 17,000+ apps): across categories, 17-32 day trials convert at a median 42.5% vs 25.5% for trials under 4 days; within Health & Fitness, 5-9 day trials convert at 46.8% vs 40.4% for 10-16 days — [RevenueCat: free trial length](https://www.revenuecat.com/blog/growth/free-trial-length)
- Health & Fitness is the category where annual plans dominate, with 60.6% of revenue — [RevenueCat 2026 trends blog](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026) (as summarized)
- Health & Fitness first-month monetization benchmarks for 2026 (secondary compilation) — [Sahha: Health and Fitness App Conversion Benchmarks 2026](https://sahha.ai/blog/health-app-monetization-first-month/)
- CPI: Meta-only median CPI for "Wellness & Holistic Health" averaged $10.25 across countries in 2025; US averaged $10.10 with a median month of $6.18 — [Superads: wellness CPI US](https://www.superads.ai/facebook-ads-costs/cost-per-app-install/wellness-holistic-health/united-states); [Superads: wellness CPI global](https://www.superads.ai/facebook-ads-costs/cost-per-app-install/wellness-holistic-health)
- iOS CPIs rose ~12% on average globally, with health & fitness up ~15% (one of the sharpest increases) — [RocketShip HQ](https://www.rocketshiphq.com/?p=5401) (secondary; category table not visible)
- Singular Q1 2026: cross-genre Android CPI rose from $0.57 to $0.66 (~16% QoQ); advertisers pay an iOS premium where user value justifies it — [Singular Quarterly Report Q1 2026](https://www.singular.net/quarterly-report-2026-q1/)
- Generic CPI ranges: iOS ~$2-5+, Android ~$1-3 (not health-specific) — [Superads](https://www.superads.ai/facebook-ads-costs/cost-per-app-install/fitness-training-centers/united-states); a conflicting source gives Android average $3.70 — [Mapendo CPI 2025](https://mapendo.co/blog/cost-per-install-2025-the-ultimate-report-to-grow-your-app-worldwide)
- Calm and Headspace have moved from download growth to revenue maximization (pricing/monetization), indicating mature category economics — [Appfigures (Jan 2023)](https://app.appfigures.com/resources/insights/20230106?f=4)
- Talkspace's direct-to-consumer business shrank: FY2025 consumer revenue fell 29.5% to $17.5M on a 30.0% decline in consumer active members, attributed to an intentional shift of marketing to payor members; management expects consumer revenue to keep declining in 2026 — [Talkspace FY2025 10-K](https://www.sec.gov/Archives/edgar/data/1803901/000119312526105146/talk-20251231.htm); [Talkspace Q4 2025 earnings call](https://www.fool.com/earnings/call-transcripts/2026/02/19/talkspace-talk-q4-2025-earnings-call-transcript/?.tsrc=rss)
- Calm laid off ~20% of staff including ~a dozen consumer marketing roles (per WSJ-reported memo) — [eMarketer](https://www.emarketer.com/content/calm-laid-off-20-of-its-staff-here-s-what-signals-about-digital-health-marketing-amid-economic-uncertainty) (date not confirmed in search)

### Inferences
- Illustrative funnel (inference, not sourced as a single dataset): if US paid installs cost ~$6-10 on Meta, install-to-trial is in the low single digits to ~10%, and trial-to-paid ~38%, CAC per paying subscriber could plausibly land in the ~$150-400+ range; against typical annual prices for mental wellness apps (Calm/Headspace historically ~$70/yr list) this is hard to recover in year 1 unless renewal rates are high. This is a modeling estimate that should be calibrated with the primary RevenueCat install-to-paid figures.
- Talkspace's deliberate retreat from DTC, and Calm's consumer marketing cuts, are strong market signals that DTC paid acquisition in mental health is not profitable at scale for even well-known brands.
- ASO for "anxiety" terms is likely dominated by incumbents with high download velocity and ratings; a new app should not assume meaningful organic App Store discovery.

### Gaps
- Could not verify RevenueCat's install-to-paid conversion, median price points, refund rates, or category LTV for Health & Fitness (site blocked; only summaries available).
- No primary source found for "anxiety" keyword difficulty/ASO competitiveness or cost-per-trial benchmarks for health apps.
- No current (2025-2026) verified list prices for Calm/Headspace or median monthly/annual price for mental health apps.
- No published LTV/CAC for any mental health consumer app.

## 3. B2B / employer channel

### Takeaway
The employer channel is large but consolidating around a few scaled platforms (Lyra, Spring Health, Modern Health, Headspace) while employer spend per head fell ~7% in 2025; pricing is opaque and low-PEPM (~$1-12, typically $3-9), sales cycles are long (indicatively 4-18 months), and buyers demand outcomes data — making it difficult for a single-condition point solution to sell directly rather than as a partner/content provider to a platform.

### Cited Findings
- NFP report (Aug 2026): employers report higher mental health utilization, but average employer spend on mental health resources fell ~7% in 2025; brokers increasingly must justify the benefit at renewal — [Insurance Business (Aug 2026)](https://www.insurancebusinessmag.com/us/news/benefits/mental-health-utilization-is-up--but-employer-spending-fell-7-in-2025-587992.aspx)
- Spring Health completed a combination with Alma in May 2026 (reported to cover >170M lives); Lyra raised $75M in May 2026 (reported in secondary/market sources; primary announcements not verified) — [ValueAdd VC: where the market is consolidating](https://valueaddvc.com/blog/mental-health-tech-in-2026-where-the-5b-market-is-consolidating); [MedCity News (May 2026)](https://medcitynews.com/2026/05/top-7-modern-ai-powered-eap-providers-for-global-workforces-in-2026/)
- Lyra, Spring Health and Modern Health have replaced or supplemented traditional EAPs at many mid-market and enterprise employers, driven by outcomes reporting — [hrtechsaas comparison](https://hrtechsaas.com/blog/lyra-vs-spring-health-vs-modern-health/) (vendor-comparison blog)
- Commentary on the sector's "weird fixation with employers" as a channel (HLTH, Aug 2026) — [HLTH](https://hlth.com/insights/articles/mental-health-and-the-weird-fixation-with-employers)
- Pricing models: PEPM, utilization/per-session, or hybrid (low flat PEPM + per-appointment fees where costs accrue) — [Headspace for Organizations blog](https://organizations.headspace.com/blog/evaluating-mental-health-solution-pricing-models); [Spring Health blog](https://www.springhealth.com/blog/outcomes-based-eap-pricing-model-solution-incentives)
- General mental health benefit costs ~$3-9 PEPM — [JD Supra](https://jdsupra.com/legalnews/what-to-consider-when-choosing-a-mental-2436167); [Woodruff Sawyer](https://woodruffsawyer.com/node/7811)
- Headspace typically quoted at $3-12 PEPM depending on utilization assumptions, company size and clinical services — [Vendr: Headspace](https://www.vendr.com/marketplace/headspace)
- Low-confidence (sales-ops site): enterprise $3-6 PEPM for 10,000+ employee firms; health plan partnerships $0.85-2.50 PMPM; sales cycles 4-9 months mid-market, 9-18 months enterprise — [PulseRevOps](https://pulserevops.com/knowledge/ik0105)
- Public procurement examples: one EAP at $7.65 PEPM (~$55,080/yr for that county); another at $1.54 PEPM max — [Sauk County EAP comparison](https://www.co.sauk.wi.us/sites/default/files/fileattachments/ordinance/129380/eap_comparison.docx); [NDPERS EAP selection matrix](https://www.ndpers.nd.gov/sites/www/files/documents/employer-additional-information/eap-provider-selection/eap-selection-bree-health-matrix.pdf)
- Traditional EAP cost guide — [Nivati](https://nivati.com/how-much-do-eap-programs-cost)
- Calm replaced Calm for Business by acquiring Ripple Health Group and rebranding as Calm Health (B2B/clinical push) — [eMarketer](https://www.emarketer.com/content/headspace-health-acquires-new-wellness-app-while-calm-lays-off-some-of-its-workforce)
- Headspace cut 13% of workforce and moved staff therapists to contract/part-time "flex network" effective Mar 15, 2025 — [eMarketer](https://www.emarketer.com/content/headspace-cuts-13--of-its-workforce--transitions-staff-therapists-contract-part-time-roles); an earlier round cut 181 employees (~15%), mostly meditation app content staff — [Becker's](https://www.beckershospitalreview.com/digital-health/headspace-lays-off-181-employees-in-2nd-round-of-job-cuts.html)
- Unverified: an LLM-generated company profile claims Headspace's Cigna deal reached 7M members on Jan 1, 2026 — [Built In](https://builtin.com/company/headspace/faq/stability-growth) (do not rely on without confirmation); an aggregator reports Sword Health agreed to acquire Headspace (unconfirmed) — [InterviewPal](https://interviewpal.com/layoffs/headspace)

### Inferences
- Employer buyers are consolidating vendors into one "front door" platform; a standalone anxiety app selling directly to employers faces buyer fatigue and long cycles. The more realistic employer route is as an embedded content/program partner inside Lyra/Spring/Modern Health/Headspace or EAP carriers, likely at sub-$1 PMPM or per-engaged-user rates (inference; no direct figures found for partner rates).
- Falling employer spend (-7% in 2025) despite rising utilization implies price pressure and preference for utilization/outcomes-based pricing — risk shifts to the vendor.

### Gaps
- No primary data on Lyra/Spring/Modern Health actual PEPM rates (all quote per contract).
- No verified sales-cycle data from an independent source (only the low-confidence PulseRevOps page).
- No data on rates paid to third-party content/point-solution partners by platforms.
- Ginger/Headspace 2021 merger details were not re-verified in this session.

## 4. Payer / clinical channel (CMS DMHT, DiGA, NHS, health systems, Pear, Big Health)

### Takeaway
Reimbursement pathways now exist in all three regions (US Medicare DMHT G-codes since 2025, Germany's DiGA, NICE early value assessments in England), but each delivers modest volume and price: Medicare DMHT claims remain low and contractor-priced; DiGA has ~1.6M cumulative prescriptions and negotiated prices averaging ~€227 (vs €544 manufacturer); and Pear's collapse shows FDA clearance without payer coverage is fatal. Talkspace's payer pivot is the clearest commercial success signal for clinical (human-delivered) care.

### Cited Findings
**US — CMS DMHT codes**
- CY2026 PFS final rule extended DMHT payment (G0552, G0553, G0554) to ADHD devices (21 CFR 882.5803), in addition to the original 21 CFR 882.5801 computerized behavioral therapy devices — [Federal Register, CY2026 PFS final rule](https://www.federalregister.gov/documents/2025/11/05/2025-19787/medicare-and-medicaid-programs-cy-2026-payment-policies-under-the-physician-fee-schedule-and-other); [OPEN MINDS](https://openminds.com/market-intelligence/news/medicare-expands-coverage-of-digital-mental-health-treatment-devices-for-adhd-amid-feedback-on-additional-services/); [CMS MLN summary MM14315](https://www.cms.gov/files/document/mm14315-medicare-physician-fee-schedule-final-rule-summary-cy-2026.pdf)
- G0552 = device supply and onboarding (contractor-priced by MACs); G0553 = first 20 min/month treatment management; G0554 = each additional 20 min; device must be furnished incident to a billing practitioner's services under a behavioral health plan of care — [AAPC](https://www.aapc.com/blog/93550-cms-issues-final-rule-for-2026-medicare-part-b-payment-policies/); [Federal Register](https://www.federalregister.gov/documents/2025/11/05/2025-19787/medicare-and-medicaid-programs-cy-2026-payment-policies-under-the-physician-fee-schedule-and-other)
- CMS acknowledged inconsistent MAC pricing for G0552 but declined to create a national rate, and noted Medicare FFS claims volume for G0552-G0554 "remained low" since creation in CY2025 — [Federal Register](https://www.federalregister.gov/documents/2025/11/05/2025-19787/medicare-and-medicaid-programs-cy-2026-payment-policies-under-the-physician-fee-schedule-and-other) (via secondary summaries; final rule text not read directly)
- Implication for anxiety apps: eligibility requires FDA clearance under the relevant device classification (an unregulated wellness app does not qualify) — [Federal Register](https://www.federalregister.gov/documents/2025/11/05/2025-19787/medicare-and-medicaid-programs-cy-2026-payment-policies-under-the-physician-fee-schedule-and-other)

**US — Pear Therapeutics**
- Pear had >45,000 prescriptions, ~half filled, and was reimbursed for ~40% of filled prescriptions; only ~10 states reimbursed; ASP ~$1,195; mostly Medicaid coverage — [Pharmaceutical Technology](https://pharmaceutical-technology.com/analyst-comment/pear-therapeutics-a-lesson-for-future-dtx-developers); [In Vivo / Citeline](https://invivo.pharmaintelligence.informa.com/IV147722/Pear-Bankruptcy-Filing-Highlights-Reimbursement-Barriers-for-Digital-Therapeutics)
- Revenue ~$13M vs expenses ~$140M in one year; burn ~$35M/quarter; nearly half of revenue from three payers with different contract structures — [Pharmaceutical Technology](https://pharmaceutical-technology.com/analyst-comment/pear-therapeutics-a-lesson-for-future-dtx-developers); [MMIT / AIS Health](https://www.mmitnetwork.com/aishealth/health-plan-weekly/pear-bankruptcy-filing-highlights-reimbursement-barriers-for-digital-therapeutics/)
- Chapter 11 in April 2023; assets auctioned May 2023 for just over $6M (Nox Health paid $3.9M for Somryst; Harvest Bio bought reSET/PearConnect) — [Pharmaceutical Technology](https://www.pharmaceutical-technology.com/?p=244524)
- Lack of predetermined reimbursement rate and ambiguous CMS guidance led to claim-by-claim adjudication — [PMC12314708](https://pmc.ncbi.nlm.nih.gov/articles/PMC12314708/); see also [Managed Healthcare Executive](https://managedhealthcareexecutive.com/view/what-does-pear-therapeutics-bankruptcy-mean-for-pdts-)

**US — Big Health (DaylightRx for GAD, SleepioRx for insomnia)**
- Big Health raised $23.7M strategic funding (Feb 2026), with CVS Health Ventures among investors, to scale commercialization, provider partnerships, and health system/payer access — [Business Wire (Feb 12, 2026)](https://www.businesswire.com/news/home/20260212541697/en/Big-Health-Secures-Funding-to-Accelerate-Adoption-of-Digital-Mental-Health-Treatments); [Big Health news](https://www.bighealth.com/news/big-health-secures-funding-to-accelerate-adoption-of-digital-mental-health-treatments)
- Big Health positions the CY2025 DMHT G-codes as a national Medicare reimbursement route for SleepioRx and DaylightRx, while noting codes don't guarantee reimbursement; Medicare has 20% coinsurance — [Big Health: FDA-cleared digital treatments](https://www.bighealth.com/news/fda-cleared-digital-treatments-are-shaping-the-future-of-mental-healthcare); [SleepioRx page](https://www.bighealth.com/sleepio-rx)
- Daylight and Sleepio added to Evernorth (Cigna) Digital Health Formulary; Henry Ford Health adopted SleepioRx in primary care and sleep clinics; APA member benefit partnership — [Big Health news](https://www.bighealth.com/news/fda-cleared-digital-treatments-are-shaping-the-future-of-mental-healthcare); [APA](https://www.apa.org/members/your-membership/benefits/big-health)
- No CVS Caremark formulary listing found (CVS link is investment only) — [Sleep Review](https://sleepreviewmag.com/sleep-treatments/behavioral-sleep-medicine/cognitive-behavioral-therapy/scale-fda-cleared-digital-sleep-anxiety-treatments-sleepiorx/)

**US — Talkspace (payer pivot, human-delivered therapy)**
- FY2025 revenue $228.9M (+22%); payor revenue $171.5M (+37.9%) on +31.5% completed payor sessions, +29.7% active payor members, +29.6% health plan customers; consumer revenue $17.5M (-29.5%); net income $7.8M; adj. EBITDA $15.8M; 2026 revenue guidance $275-290M — [Talkspace FY2025 10-K](https://www.sec.gov/Archives/edgar/data/1803901/000119312526105146/talk-20251231.htm); [Talkspace FY2025 results release](https://www.barchart.com/story/news/302728/talkspace-announces-fourth-quarter-and-full-year-2025-results)

**Germany — DiGA**
- GKV-SV DiGA report 2025: average manufacturer price rose from €411 (first reporting year) to €544 (2025); range €119-€2,077; negotiated prices for 40 DiGA average €227 — [GKV-Spitzenverband DiGA-Bericht 2025](https://www.gkv-spitzenverband.de/media/dokumente/krankenversicherung_1/telematik/digitales/2025_DiGA_Bericht_GKV_SV.pdf); also cited €566 average manufacturer price as of Dec 2025 and €552 average trial-phase price (BVMed critique) — [BVMed statement](https://www.bvmed.de/download/stellungnahme-diga-bericht-2025-des-gkv-sv)
- Cumulative to end-2025: ~1.6M DiGA dispensed, ~€400M spending (GKV report) — [GKV-SV DiGA-Bericht 2025](https://www.gkv-spitzenverband.de/media/dokumente/krankenversicherung_1/telematik/digitales/2025_DiGA_Bericht_GKV_SV.pdf); ~690,000 dispensed in 2025 alone with ~€171.3M spend (per search summary; figures should be checked against the report) — [Peix DiGA review 2025](https://en.peix.de/forward-pharma/diga-im-kreuzfeuer)
- Mental health share: ~27-28% of DiGA use attributable to psychiatric indications (most-used category in prior years; metabolic now leads at 34.2%); 55% of listed DiGA address mental disorders (AOK); Bitkom counts 32 mental health DiGA — [GKV-SV report](https://www.gkv-spitzenverband.de/media/dokumente/krankenversicherung_1/telematik/digitales/2025_DiGA_Bericht_GKV_SV.pdf); [AOK data](https://www.aok.de/pp/gg/daten-und-analysen/digitale-gesundheitsanwendungen/); [Bitkom DiGA study 2026](https://www.bitkom.org/sites/main/files/2026-10/bitkom-studienbericht-digitale-gesundheitsanwendungen-diga-2026_1.pdf); Bundestag (May 2025) gives 30% for psychiatric — [Bundestag hib 148/2025](https://www.bundestag.de/presse/hib/kurzmeldungen-1064486)
- Only 16 DiGA (22%) moved from provisional ("Erprobung") to permanent listing; end-2025: 48 permanent, 10 provisional — [GKV-SV report](https://www.gkv-spitzenverband.de/media/dokumente/krankenversicherung_1/telematik/digitales/2025_DiGA_Bericht_GKV_SV.pdf)
- GPs issue about half of DiGA prescriptions — [Medical Tribune](https://www.medical-tribune.de/praxis/e-health/hausaerztinnen-und-aerzte-stellen-jede-zweite-verordnung-aus)
- GKV-SV frames the manufacturer-vs-negotiated price gap as a control deficit; industry (SVDGV) frames it as compensation for trial-phase costs — [Peix](https://en.peix.de/forward-pharma/diga-im-kreuzfeuer); market consolidation/survival commentary — [mybusinessfuture](https://mybusinessfuture.com/diga-apps-rezept-markt-wachstum-bereinigung-2026/); [DUX DiGA Market Report 2026](https://dux-healthcare.com/en/knowledge/business-strategy/diga-market-report-2026/)
- e-prescription for DiGA started on a voluntary basis (KBV, Mar 2026) — [KBV](https://www.kbv.de/praxis/tools-und-services/praxisnachrichten/2026/03-12/digitale-gesundheitsanwendungen-elektronische-verordnung-startet-freiwillig)

**UK — NICE / NHS Talking Therapies**
- NICE HTG676 (early value assessment): digitally enabled therapies for adults with anxiety disorders conditionally recommended while more evidence is generated; preliminary evidence suggests cost-effectiveness vs standard care; products include Beating the Blues, Minddistrict, SilverCloud, iCT-SAD; use requires DTAC approval and an NHS England digitally enabled therapies assessment — [NICE HTG676](https://www.nice.org.uk/guidance/htg676/resources/digitally-enabled-therapies-for-adults-with-anxiety-disorders-early-value-assessment-pdf-1809598771294405)
- NICE HTG756 / HTE10055 (digital front door for Talking Therapies): may offer value for money if they save >~3 minutes of clinical assessment time; committee flagged limited data on training, promotion and digital safety assurance costs (which experts said can be significant) — [NICE HTG756](https://www.nice.org.uk/guidance/htg756/chapter/3-Committee-discussion); [PubMed HTE10055](https://pubmed.ncbi.nlm.nih.gov/42366809/)

### Inferences
- US Medicare DMHT is a real but thin channel: it requires FDA clearance, a prescribing/managing clinician, MAC-by-MAC pricing, and 20% coinsurance — and CMS itself reports low claim volume. It helps legitimacy more than revenue in the near term.
- DiGA offers the most concrete reimbursement in Europe, but the economics compressed: negotiated prices (~€227) are ~58% below launch prices, only ~22% of provisional listings convert to permanent, and annual volume (~690k across all indications) is modest. A mental-health DiGA might expect thousands to low tens of thousands of prescriptions per year, not hundreds of thousands (inference).
- In England, entry is via NICE EVA + DTAC + NHS England assessment, with procurement by local Talking Therapies services; incumbents (SilverCloud, etc.) already hold the position.
- Pear and Big Health together suggest the path for an FDA-cleared anxiety DTx: health system/PBM formulary placement and payer contracts first, with Medicare codes as a supplement; budget for multi-year runway before reimbursement scales.

### Gaps
- Actual MAC rates for G0552 and real Medicare DMHT claim counts were not found.
- DaylightRx prescription volumes/revenue are not public.
- NHS per-patient prices for digital CBT in Talking Therapies were not found.
- Specific DiGA anxiety products (e.g., Mindable, Velibra) uptake and negotiated prices not found.
- France (PECAN) and other EU reimbursement pathways not covered.

## 5. Other models (B2B2C via insurers, universities, clinician-prescribed, freemium + coaching, licensing)

### Takeaway
The models showing commercial traction route through payers or institutions that already own the patient relationship (health plans, PBM formularies, health systems), while DTC freemium is shrinking; health plan partnerships pay very low per-member rates (~$0.85-2.50 PMPM, low-confidence), so success requires scale or per-engaged-user/per-outcome pricing.

### Cited Findings
- Talkspace grew health plan customers +29.6% and active payor members +29.7% in 2025 while deliberately shrinking DTC — [Talkspace FY2025 10-K](https://www.sec.gov/Archives/edgar/data/1803901/000119312526105146/talk-20251231.htm)
- Health plan partnership pricing $0.85-2.50 PMPM (low-confidence sales-ops source) — [PulseRevOps](https://pulserevops.com/knowledge/ik0105)
- PBM digital formularies (Evernorth Digital Health Formulary) as a B2B2C route; Big Health's Daylight and Sleepio listed — [Big Health](https://www.bighealth.com/news/fda-cleared-digital-treatments-are-shaping-the-future-of-mental-healthcare)
- Clinician-prescribed route: DiGA prescriptions predominantly from GPs (~50%) — [Medical Tribune](https://www.medical-tribune.de/praxis/e-health/hausaerztinnen-und-aerzte-stellen-jede-zweite-verordnung-aus); US DMHT requires an ongoing clinician plan of care — [AAPC](https://www.aapc.com/blog/93550-cms-issues-final-rule-for-2026-medicare-part-b-payment-policies/)
- Professional-association distribution: Big Health offered as an APA member benefit — [APA](https://www.apa.org/members/your-membership/benefits/big-health)
- Woebot exited consumer and refocused on enterprise/clinical partnerships (secondary sources) — [HLTH (Apr 2025)](https://hlth.com/insights/news/woebot-health-is-shutting-down-its-app-2025-04-28); [Telehealth.org](https://telehealth.org/news/ai-psychotherapy-shutdown-what-woebots-exit-signals-for-clinicians/)

### Inferences
- Licensing CBT content/modules to scaled platforms (employer platforms, insurers, EAPs) is a lower-cost channel than direct enterprise sales but likely yields low per-user economics; no pricing data found.
- University counselling centres are plausible B2B buyers but no 2025-2026 market data was found.

### Gaps
- No data on university/student mental health app procurement volumes or pricing.
- No data on content-licensing deal terms in digital mental health.
- No quantitative data on freemium + coaching hybrid conversion economics (e.g., coaching attach rates).

## 6. Lessons from failures, pivots and successes

### Takeaway
The failures cluster into three causes: no reimbursement despite regulatory clearance (Pear), unproven clinical value of novel technology (Mindstrong), and regulatory/compliance cost or violations (Woebot's FDA cost, Cerebral's FTC privacy fine); the clearest successes (Talkspace's payer pivot, Big Health's formulary/health-system approach) moved away from DTC toward payers and clinical integration.

### Cited Findings
- Woebot retired its consumer app on June 30, 2025; founder Alison Darcy attributed it largely to the cost and challenge of meeting FDA marketing-authorization requirements, saying AI is moving faster than regulators — [STAT News (Jul 2, 2025)](https://www.statnews.com/2025/07/02/woebot-mental-health-chatbot-shuts-down-founder-says-ai-moving-faster-than-regulators/) (headline/summary only; page not fetchable in session); [HLTH (Apr 28, 2025)](https://hlth.com/insights/news/woebot-health-is-shutting-down-its-app-2025-04-28)
- Mindstrong ended patient care in March 2023 and sold technology assets and some staff to SonderMind, after laying off >100 workers; terms undisclosed — [MobiHealthNews](https://www.mobihealthnews.com/news/mindstrong-sells-tech-assets-sondermind-shuts-down-operations); [MedTech Dive](https://www.medtechdive.com/news/sondermind-acquires-mindstrong-technology-digital-mental-health/645794/); STAT investigation of Mindstrong's unraveling — [STAT (Feb 28, 2023)](https://www.statnews.com/2023/02/28/mindstrong-mental-health-technology-prediction/)
- Commentary: Mindstrong's digital biomarkers lacked evidence that they improved outcomes or reduced costs — [Bioethics.com](https://bioethics.com/?p=69633)
- Cerebral agreed to a $7.1M FTC settlement (2024) for sharing sensitive health data with advertisers via tracking technologies; FTC position: no disclosure of health info to ad platforms without affirmative express consent — [Healthcare Dive](https://www.healthcaredive.com/news/cerebral-federal-trade-commission-7-million-fine-data-sharing-privacy/713295/); [WSGR Data Advisor](https://www.wsgrdataadvisor.com/2024/05/ftc-announces-proposed-settlement-agreements-with-two-digital-health-companies-for-disclosing-consumers-health-information-to-third-party-advertisers-among-other-violations/)
- Pear: FDA-cleared, but reimbursement gap; ~$6M asset sale after Chapter 11 (Apr 2023) — see Section 4 sources — [Pharmaceutical Technology](https://pharmaceutical-technology.com/analyst-comment/pear-therapeutics-a-lesson-for-future-dtx-developers)
- Headspace layoffs (13% in 2025; 181 staff/15% earlier) and therapist staff moved to contract network; Calm layoffs (~20%) — see Section 3 sources — [eMarketer](https://www.emarketer.com/content/headspace-cuts-13--of-its-workforce--transitions-staff-therapists-contract-part-time-roles); [eMarketer](https://www.emarketer.com/content/calm-laid-off-20-of-its-staff-here-s-what-signals-about-digital-health-marketing-amid-economic-uncertainty)
- Funding environment: US digital health venture funding $14.2B across 482 deals in 2025; mega-deals (>$100M) were 42% of funding; AI-enabled companies took 54% (up from 37%) — [Rock Health 2025 year-end](https://rockhealth.com/insights/2025-year-end-digital-health-funding-overview-a-tale-of-two-markets/); [Fierce Healthcare (JPM26)](https://www.fiercehealthcare.com/digital-health/jpm26-digital-health-funding-hit-142b-2025-ai-companies-taking-lions-share-dollars)
- Rock Health notes AI mental health chatbots as a 2025 flashpoint; Slingshot debuted with a $93M raise for a purpose-built mental health AI — [Rock Health: turn of 2026](https://rockhealth.com/?p=41211)
- Mental health tech funding ~$1.4B in 2024, ~50% below the 2021 peak (secondary) — [ValueAdd VC](https://valueaddvc.com/blog/mental-health-tech-in-2026-where-the-5b-market-is-consolidating)

### Inferences
- Privacy is a commercial risk, not just compliance: the standard DTC growth playbook (Meta/TikTok pixels for conversion optimization) is precisely what triggered FTC action against Cerebral (and BetterHelp, not re-verified here). This constrains paid-acquisition performance for a mental health app.
- Capital is concentrating in AI and mega-rounds; a modestly funded evidence-based anxiety app will compete for investor attention against AI-native mental health companies.

### Gaps
- Ginger + Headspace merger (2021) and subsequent integration outcomes not re-verified in this session.
- BetterHelp (Teladoc) 2025 revenue/customer trends and its FTC settlement were not retrieved in this session.
- Did not obtain Rock Health's mental-health-specific share of 2025 funding.

## 7. Realistic budget/team needed per channel

### Takeaway
No source publishes channel-specific budgets for new anxiety apps; benchmarks from comparable companies imply DTC requires sustained paid spend against ~$6-10 CPIs, payer/DTx paths require multi-year runway (Pear burned ~$35M/quarter and still failed; Big Health raised a further $23.7M in 2026 to scale), and employer sales require enterprise sales teams through 4-18 month cycles.

### Cited Findings
- Pear burn ~$35M/quarter; ~$140M annual expenses vs ~$13M revenue — [Pharmaceutical Technology](https://pharmaceutical-technology.com/analyst-comment/pear-therapeutics-a-lesson-for-future-dtx-developers)
- Big Health $23.7M round (Feb 2026) to scale commercialization of two FDA-cleared products — [Business Wire](https://www.businesswire.com/news/home/20260212541697/en/Big-Health-Secures-Funding-to-Accelerate-Adoption-of-Digital-Mental-Health-Treatments)
- Woebot cited FDA authorization cost as prohibitive for its consumer app — [STAT News](https://www.statnews.com/2025/07/02/woebot-mental-health-chatbot-shuts-down-founder-says-ai-moving-faster-than-regulators/)
- DiGA: only 22% of provisionally listed DiGA achieved permanent listing (evidence generation risk) — [GKV-SV report](https://www.gkv-spitzenverband.de/media/dokumente/krankenversicherung_1/telematik/digitales/2025_DiGA_Bericht_GKV_SV.pdf)
- Employer sales cycles 4-9 months (mid-market) / 9-18 months (enterprise), low confidence — [PulseRevOps](https://pulserevops.com/knowledge/ik0105)
- Wellness Meta CPI ~$6-10 (US) — [Superads](https://www.superads.ai/facebook-ads-costs/cost-per-app-install/wellness-holistic-health/united-states)

### Inferences (illustrative estimates, not sourced figures)
- DTC: to reach ~10,000 paying subscribers at an illustrative CAC of $150-400 per payer implies ~$1.5-4M in acquisition spend alone, plus a growth/product team; payback is uncertain given low category demand.
- DiGA: a provisional listing requires a German entity/partner, CE-marked medical device (MDR), data protection certification, and an RCT during the 12-24 month trial phase; with ~€227 negotiated price, ~10,000 prescriptions/year ≈ ~€2.3M revenue (illustrative).
- US payer/DTx: FDA De Novo/510(k) plus pivotal RCT, then payer contracting; Pear/Big Health precedents suggest tens of millions of dollars and 3-5+ years before material revenue.
- Employer: requires outcomes data, security reviews (SOC 2/HIPAA), and enterprise sales staff; more realistic as a partner integration than direct sales for an early-stage company.

### Gaps
- No published cost benchmarks for DiGA dossier/RCT, FDA DTx clearance, or NHS DTAC/EVA entry for a new entrant.
- No team-size benchmarks for each channel found.
