# 🧠 Smart Therapist Matching System (YourDOST Case Study)

> **Transforming therapist discovery from a static directory search into a scientific, data-driven matching engine to improve therapy outcomes, user experience, and long-term engagement.**

---

## 📖 Executive Summary
YourDOST provides online counseling to college students and corporate employees navigating diverse stressors (academic pressure, workplace burnout, career transitions, and relationship issues). Currently, users browse a static directory of therapists, relying on clinical titles and brief bios to make a high-stakes choice. 

This repository contains the end-to-end product strategy, comprehensive **Product Requirements Document (PRD)**, and executive presentation structure designed to solve discovery friction, eliminate decision paralysis, and drive higher first-to-second session retention.

---

## 🔍 Problem Statement
Through user journey analysis, three core bottlenecks in the current discovery and selection experience were identified:
1. **Choice Overload & Asymmetric Information:** Users face dozens of profiles filled with clinical jargon (*e.g., CBT, REBT, Eclectic Modality*), leading to cognitive fatigue and decision paralysis.
2. **High Friction in the "Trial-and-Error" Loop:** When an initial match fails, emotional vulnerability and mental health stigma cause users to churn completely rather than switch therapists.
3. **Omission of Cultural & Contextual Nuance:** Standard filters miss critical nuances such as generational workplace pressures, regional linguistic comfort (*e.g., Hinglish*), and specific life-stage empathy (*e.g., tech corporate grind vs. academic stress*).

---

## 🚀 Proposed Solution & Architecture
We replace the traditional directory search with a **Guided Algorithmic Matching Engine** backed by a structured data taxonomy:
* **User Intake Data (Demand Side):** Captures presenting concerns (mapped with severity scores using lightweight GAD-2/PHQ-2 adaptations), therapy style preferences (directive vs. exploratory), and cultural/language context.
* **Therapist Profile Data (Supply Side):** Verified clinical specializations, communication styles, language proficiencies, and anonymous historical outcome vectors.
* **Hybrid Scoring Engine:** 
  * *Hard Constraints (Filtering):* Licensing, language fluency, schedule availability, and user segment alignment.
  * *Soft Matching (Algorithmic Scoring):* Specialization Alignment (40%) + Style/Personality Fit (30%) + Empirical Success Weight (30%).

---

## 📋 Product Requirements Document (PRD) Summary
The full standalone PRD accompanying this project covers:
* **Problem & High-Level Approach Alignment**
* **Detailed User Stories (covering first-time onboarding, matching, cultural preferences, and post-session feedback)**
* **MVP Scope vs. Phase 2 Future Vision (Machine Learning collaborative filtering deferred to later stages)**
* **Scope Boundaries & Out-of-Scope Definitions**

---

## 📊 Executive Presentation Deck Structure
The accompanying 6-slide presentation deck is structured for executive review, avoiding generic labels and focusing on clear product storytelling:
1. **Context & Strategic Vision:** The clinical and business imperative for better matching.
2. **Problem Diagnosis:** Deep-dive into user friction and choice overload.
3. **Solution Architecture:** The data collection framework and hybrid scoring logic.
4. **Product Experience:** The end-to-end user journey from intake to curated matching.
5. **Execution Roadmap:** Prioritized MVP feature breakdown (P0, P1, P2).
6. **Outcome Framework:** Key performance indicators and strategic trade-offs.

---

## 🎯 MVP Scope & Prioritization
* **P0 — Guided Intake Questionnaire:** 5–7 conversational questions capturing core stressors and style preferences.
* **P0 — Top-3 Curated Match View:** Displays top 3 recommendations with transparent "Match Reason" badges.
* **P1 — Post-Session Match Health Check:** Automated pulse check after Session 1 with a frictionless re-match guarantee.
* **P2 — Machine Learning Feedback Loop:** Dynamic weight adjustment based on long-term outcome data *(Deferred to Phase 2)*.

---

## 📈 Success Metrics
* **Matching Effectiveness:** First-to-second session retention target **>80%**; Match acceptance rate **>70%**.
* **User Retention:** Session 4 retention (**>70%**) and Session 8 retention (**>60%**).
* **Clinical Outcomes:** Improvement in pre- and post-therapy self-assessment score deltas over a 4–8 session lifecycle.
