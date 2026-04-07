# Cultural Diversity Multiplier (CDM) — Interactive Prototype

**Live Demo:** https://rianhussain007.github.io/cdm-prototype/

Supplementary material for the policy proposal:
**"Silenced by the Algorithm: A Policy Framework for Linguistic Cultural Equity in Digital Platform Governance"**
Submitted to the SDGs Youth Public Policy Innovation Challenge 2026
by Rian Hussain,Shriya U & Pranav R, CMR University

---

## What is the Cultural Diversity Multiplier?

Platform recommendation algorithms — YouTube's Up Next, Instagram's Explore, TikTok's For You Page — are trained primarily on English data. As a result, they systematically underrank content in minority and regional languages like Bhojpuri, Gondi, Yoruba, and Quechua. A creator making content in Bhojpuri earns ₹15–50 CPM. An identical creator in English earns ₹80–250 CPM. The gap is not audience preference. It is structural algorithmic bias.

The **Cultural Diversity Multiplier (CDM)** is a corrective weighting mechanism proposed under the Digital Cultural Equity Act (DCEA). It partially compensates for training-data disadvantage by applying a defined boost to underrepresented language content in recommendation scoring — not to inflate quality, but to remove the artificial penalty.

---

## How It Works

Languages are classified into three tiers by the National Digital Language Equity Authority (NDLEA):

| Tier | Languages | CDM Applied |
|------|-----------|-------------|
| Tier 1 | Hindi, English | None (baseline) |
| Tier 2 | Tamil, Telugu, Bengali, Kannada | Moderate multiplier |
| Tier 3 | Bhojpuri, Gondi, Tulu, and 400+ others | Higher multiplier |

The CDM adjusts the algorithm's internal content score before ranking. A Bhojpuri video that scores 0.65 on engagement signals receives a CDM-adjusted score of ~0.85 — closer to its true audience-preference value, corrected for training data skew.

CDM values are:
- Set annually by NDLEA using language AI performance benchmarks
- Designed to **shrink to zero** as platform language AI improves
- Applied only to organic reach, not to advertising rates directly

---

## What This Prototype Shows

The interactive dashboard demonstrates:

1. **CDM Sliders** — Adjust the multiplier for Tier 2 and Tier 3 languages and see how recommendation scores change in real time
2. **Reach Comparison Table** — Baseline algorithmic score vs CDM-corrected score across language tiers
3. **Earnings Gap Chart** — Before and after DCEA impact on CPM earnings by language

This prototype was built to validate the technical feasibility of the CDM mechanism as described in Section III.d of the proposal, grounded in Lasser & Poechhacker (2025) and Kirdemir et al. (2021).

---

## Academic Grounding

- **Kirdemir et al. (2021)** — Large-scale audit of 256,725 YouTube videos confirming structural and systemic bias in recommendations varying by language. Springer / SBP-BRiMS 2021.
- **Lasser & Poechhacker (2025)** — Establishes that alternative recommendation algorithms designed for societal good are technically feasible and legally justified. *Annals of the New York Academy of Sciences*, 1548(1), 20–28.
- **Roy & Ghosh (2025)** — Documents 20–50% higher moderation error rates for low-resource languages including Tamil, Swahili, and Quechua. AAAI / arXiv.

---

## Policy Context

The CDM is Pillar 3 of the proposed **Digital Cultural Equity Act (DCEA)** — a targeted amendment to India's IT Rules 2021 framework. The full proposal covers:

- **Pillar 1:** Annual Algorithmic Impact Assessments for linguistic diversity
- **Pillar 2:** Quarterly Language-Disaggregated Reach Transparency Reports
- **Pillar 3:** Cultural Diversity Multiplier (this prototype)
- **Pillar 4:** National Digital Language Equity Authority (NDLEA)

The DCEA is India-first but globally scalable through a proposed UNESCO Digital Cultural Diversity Protocol — directly advancing SDG 10 (Reduced Inequalities), SDG 11.4 (Cultural Heritage), SDG 16.10 (Access to Information), and SDG 17 (Partnerships for the Goals).

---

## Built With

HTML, CSS, JavaScript — no frameworks, no dependencies. Fully client-side.

Generative AI tools were used in research synthesis and in generating the logic and code for this prototype, validating the technical feasibility assessment in the proposal.

---

*For the full policy proposal and research documentation, contact: CMR University, Bengaluru.*
