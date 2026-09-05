# MuscleMind 🦵⚡
### Integral Feasibility Analysis for Implementing Surface Electromyography (sEMG) to Monitor Stabilizer Muscles in Real Sports Environments

> Academic project — Interdisciplinary Projects Workshop (TPI) + Expoideas
> Group #17 · Universidad Nacional de Colombia, Bogotá Campus — Faculty of Engineering
> 165th anniversary of the Faculty of Engineering · *Ingenia Futuro* Meeting 2026-1S

---

## 📌 Overview

**MuscleMind** is a technology venture project that investigates whether **surface electromyography (sEMG)** can be implemented as an objective tool to monitor the activation of **stabilizer muscles** (particularly the gluteus medius and stabilizing hamstrings) during functional training and CrossFit, in order to support the prevention of sports injuries.

The project does not deliver a finished commercial device: its main output is a **comprehensive feasibility analysis**, evaluating the proposal across five dimensions — technical, market, economic-financial, environmental, and regulatory — before moving toward the construction of a functional prototype.

**Research question:**

> Is it feasible to implement surface electromyography (sEMG) technology to monitor the activation of muscles with a stabilizing function in a real sports environment, in order to contribute to the prevention of sports injuries?

**Overall verdict:** ✅ **Feasible, conditionally and partially** — sEMG reliably measures a subset of 15 to 18 superficial stabilizer muscles (including, precisely, the ones prioritized by the business need: gluteus medius and stabilizing hamstrings), provided it is used as **objective support** for the coach's or physiotherapist's judgment, and never as a standalone clinical diagnosis.

---

## 🧩 The problem

The project originated from a problem identified in the field at **Dynamic Center** (Villavicencio, Meta), a training and rehabilitation center led by Ricardo Ibarra, and clinically validated by physiotherapist Mariangel Colina:

- **73.5%** of CrossFit practitioners with more than 1.5 years of experience have suffered at least one musculoskeletal injury, at a rate of 3.1 injuries per 1,000 hours of training.
- The activation of stabilizer muscles — the ones that hold a joint steady while the body moves, not the ones that produce the movement — **is currently assessed only through subjective visual observation**, since the human eye cannot accurately register compensations that occur in milliseconds.
- This leads to faulty movement patterns (knee valgus, hip collapse) that progressively cause preventable injuries, while properly strengthening stabilizers can reduce overuse injuries by up to **50%**.

---

## 🎯 Objectives

**General objective**
To analyze the feasibility of implementing EMG technology to monitor the activation of stabilizer muscles in a real sports environment.

**Specific objectives**
1. Identify and characterize activation failures in stabilizer muscles during functional exercises.
2. Describe the operating principles and sports applications of electromyography (EMG).
3. Evaluate the capability of EMG systems to detect, record, and quantify muscle activation.
4. Analyze the technical feasibility of EMG (accuracy, portability, cost) in sports scenarios.
5. Establish guidelines for integrating EMG into biomechanical monitoring and training.

---

## 🔬 Methodology

The project followed the **Design Thinking** methodology, across five phases:

| Phase | Key activities |
|---|---|
| **1. Empathize** | Interviews with Dynamic Center, literature review, analysis of the sports environment (PESTEL) |
| **2. Define** | Problem statement, problem tree, feasibility criteria |
| **3. Ideate** | Alternatives tree, comparative evaluation (5 technological routes), justified selection of EMG technology |
| **4. Prototype** | System architecture design, technical requirements, limitations analysis |
| **5. Evaluate** | Technical, economic, operational, legal, and environmental feasibility; integral conclusion |

Development was planned over a 16-week schedule (see the Gantt chart in the business plan document).

---

## 🧪 Feasibility analysis results

| Dimension | Verdict | Summary |
|---|---|---|
| **Technical** | With conditions | sEMG reliably measures 15-18 of ~40 stabilizer muscles, including the gluteus medius and hamstrings (the clinically prioritized ones). Not viable for deep stabilizers (transversus abdominis, multifidus, psoas) nor as a standalone diagnosis. |
| **Market** | Favorable | Real, underserved niche. Colombian fitness industry ≈ USD 400M/year; TAM ≈ COP $8,000M, SAM ≈ COP $2,000M, SOM ≈ COP $40-80M/year. |
| **Economic-financial** | Favorable | Low initial investment (≈COP $800,000-850,000). Positive NPV (~COP $56.9M at 15%) across multiple scenarios and discount rates; payback period of 1.2 years. |
| **Environmental** | With conditions | Feasible if extended producer responsibility is incorporated (Law 1672/2013, WEEE), along with recyclable materials and rechargeable batteries from the prototype stage. |
| **Regulatory** | Favorable | By positioning itself as non-diagnostic support, the product would qualify as a Class I medical device before INVIMA. Must comply with Law 1581 of 2012 (sensitive data) and the Consumer Statute (Law 1480 of 2011). |

A deeper analysis (including a muscle-by-muscle inventory, cross-talk considerations, measurement protocols, and a proposed diagnostic flow) is available in the full technical report (IEEE format) included in this repository.

---

## 🛠️ Minimum Viable Product (MVP)

**For whom:** sports coaches, physiotherapists, physical trainers, and functional training centers.

**Must have:** surface EMG sensors over specific stabilizer muscles, adhesive electrodes, real-time data acquisition, processing microcontroller, basic graphic interface, noise/interference filtering, an experimental protocol for electrode placement, portable power supply.

**Materials:** flexible EMG sensors and electrodes, microcontroller, wiring and connectors — estimated prototype cost: ≈ COP $80,000.

**Operating requirements:** designed for dynamic training use (breathable, antibacterial), resistant to moisture/splashes (IP5).

**Applicable standards:** NTC 2050 (Colombian electrical code), NTC 2800/ISO 9001 (sports textiles), IEEE 802.15 (wireless communication), ASTM (biomechanical testing).

---

## 💼 Business model (summary)

- **Value proposition:** prevent sports injuries by monitoring, in real time, the activation of stabilizer muscles, providing objective feedback before an injury occurs.
- **Customer segments:** functional training centers and CrossFit boxes (early adopters); physiotherapy clinics, universities, and clubs (secondary); individual coaches and athletes (future).
- **Revenue streams:** EMG kit sales, platform subscriptions, B2B licensing, consumables, biomechanical evaluation services, training and consulting.
- **Projected scale-up:** validation at Dynamic Center (Year 1) → B2B commercialization in Bogotá/Villavicencio/Medellín (Years 2-3) → SaaS model with cloud analytics (Years 4-5) → regional internationalization (post-Year 5).

The complete model (Canvas, TAM-SAM-SOM, PESTEL analysis, empathy map, problem and alternatives trees) is documented in the business plan included in this repository.

---

## 🧭 How the project came together

*(From the problem identified in the field to the final feasibility document)*

This project began as part of an Interdisciplinary Projects Workshop (TPI) focused on turning a real-world problem into a rigorous feasibility analysis — not just a product pitch. The process unfolded as follows:

1. **Where the problem started.** It all began with a conversation with Ricardo Ibarra, director of Dynamic Center, who — from his day-to-day experience training CrossFit athletes — had noticed that most injuries didn't happen suddenly, but resulted from muscular compensations invisible to the naked eye. Physiotherapist Mariangel Colina confirmed this finding from a clinical standpoint. That conversation became the question that guided the entire project.

2. **Empathizing and researching.** We carried out an extensive literature review (studies from PubMed, ScienceDirect, SENIAM, among others), a PESTEL analysis of the Colombian sports environment, and interviews with the sports center's stakeholders to understand the problem from a biomechanical perspective, not just an engineering one.

3. **Defining the problem.** We built a problem tree to separate causes (lack of objective monitoring, a reactive training culture) from effects (recurring injuries, dropout, medical costs), which allowed us to formulate a clear, bounded research question.

4. **Ideating and comparing alternatives.** Five possible technological routes were proposed (traditional methods, EMG, indirect biomechanics via IMU/video, advanced clinical technologies, muscle performance measurement) and evaluated using weighted criteria for technical feasibility, preventive impact, costs, timelines, and usability. Surface EMG came out as the alternative with the best overall balance.

5. **Conceptual prototyping.** We defined the system architecture (sensors → acquisition module → processing → interface → feedback), the product's preliminary specifications, and a Minimum Viable Product organized into three evolutionary levels (essential, consolidation, future scalability).

6. **Evaluating feasibility as a whole.** This was the most extensive phase of the project: it wasn't enough to prove the technology *works* — it also had to be commercially, financially, environmentally, and regulatorily viable. This led us to build a muscle-by-muscle inventory of real measurability with sEMG (using SENIAM criteria), a market sizing exercise (TAM-SAM-SOM), five-year financial projections with indicators like NPV and IRR, a regulatory compliance analysis (INVIMA, Law 1581 of 2012, WEEE), and an empathy map validated directly with Dynamic Center's stakeholders.

7. **Synthesis and integral conclusion.** The most relevant finding of the whole process was the coherence across dimensions: the muscles Dynamic Center had clinically identified as priorities (gluteus medius and hamstrings) turned out to be, precisely, the ones that scientific evidence confirms are the most technically measurable with surface sEMG. That match — found only after cross-referencing the biomechanical review with the business need — is what allowed the project to move from a reasonable idea to an evidence-backed feasibility conclusion.

The output of this process is the document **"MuscleMind: Integral Feasibility Analysis for Implementing Surface Electromyography in the Monitoring of Stabilizer Muscles in Real Sports Environments,"** included in this repository, along with the business plan, the outreach poster, and the informational brochure that summarize the work for non-technical audiences.

---

## 📁 Repository contents

| File | Description |
|---|---|
| `MuscleMind_Integral_Feasibility_Analysis_IEEE.pdf` | Full technical report in IEEE format: technical, market, economic-financial, environmental, and regulatory feasibility. |
| `Business_Idea_Problem_Analysis_and_Business_Plan.pdf` | Full business plan: problem/alternatives trees, Business Model Canvas, empathy map, WBS, financial projections. |
| `POSTER17_MuscleMind.pdf` | Presentation poster for the Ingenia Futuro 2026-1S Meeting. |
| `MuscleMind_Brochure.pdf` | Informational brochure written in non-technical language about the problem and the proposed solution. |


---

## 👥 Team (Group #17)

| Member | Email |
|---|---|
| Andrés Camilo Ricaurte Abadía | anricaurtea@unal.edu.co |
| Laura Karina Cuadrado Orduz | lcuadrado@unal.edu.co |
| Juan Andrés Moreno Benavides | jumorenobe@unal.edu.co |
| Catalina Jiménez Varela | cjimenezva@unal.edu.co |
| Juan Diego Ruiz Trejo | jruiztr@unal.edu.co |
| Willian Camilo Castro Toro | wcastrot@unal.edu.co |

**Strategic partner:** Dynamic Center (Villavicencio, Meta), pilot validation site.

---

## 📚 References

This project relied on peer-reviewed scientific literature (SENIAM, *Journal of Orthopaedic & Sports Physical Therapy*, *Journal of Biomechanics*, among others), current Colombian regulations (Law 1581 of 2012, Law 1672 of 2013, Decree 4725 of 2005, Resolution 851 of 2022), and market sources (Sectorial, Mercado Fitness, Fortune Business Insights). The full reference lists (38 sources in the business plan and 28 in the IEEE report) are available in each respective document.

---

## 🎓 Academic context

Project developed as an Interdisciplinary Projects Workshop (TPI) assignment, Universidad Nacional de Colombia, Bogotá Campus, presented at the Ingenia Futuro 2026-1S Meeting as part of the 165th anniversary celebrations of the Faculty of Engineering.
