# A03 — Analytical study profile

## 1. Scope and research problem

The literature note describes a study addressing the Program Course Planning Problem (PCPP) at the operational level, integrating Education for Sustainable Development (ESD) principles into accounting education. According to the note, the motivating problem is a scarcity of operational studies and quantitative methodologies for structuring curricula. The note reports that course planning is traditionally conducted manually and intuitively, without standardized processes or explicit consideration of the sustainability competencies demanded by the labor market. The note also records a criticism attributed to the field: accounting programs have neglected soft skills and topics such as corporate responsibility, social justice, and environmental protection.

The note frames the topic's relevance around the claim that course planning determines the quality of academic programs, institutional reputation, and the efficiency of limited educational resource use, while preparing future decision-makers to address complex global challenges. This is presented as the justification for treating curriculum planning as a decision problem worth formal modeling rather than an administrative afterthought.

## 2. Research objectives/questions

The note states the study's objective as proposing an innovative multi-criteria decision-making (MCDM) support model for sustainable academic course planning. The model is designed to select elective and mandatory courses based on the development of sustainability competencies and subsequently distribute them in a balanced way across academic semesters.

The note explicitly states that the authors did not formulate formal statistical hypotheses, instead pursuing practical research questions:
1. How to quantify the relevance of different academic courses for building specific sustainability competencies.
2. How to balance credit loads and difficulty levels of selected courses across a semester curriculum.

## 3. Context investigated

The empirical setting, per the note, is an undergraduate accounting program at a Chinese university (unnamed in the note). The applied case involved a panel of five experts: one accounting department head, three accounting professors, and one professional from a local company, all reported to have more than ten years of experience. The scheduling stage concerned the last two years (four semesters) of the program's curriculum.

## 4. Methodological approach

The note describes a quantitative empirical case study structured in three sequential phases:

- Phase I (Competency Prioritization via BWM): the five-expert panel performed pairwise comparisons to determine the relative importance of the eight UNESCO sustainability competencies within accounting education.
- Phase II (Course Selection and Ranking via FFR): experts rated, on a 1–10 scale, the degree of relation between 53 candidate courses (compiled from the existing curriculum and from other leading universities' programs) and the eight competencies. The Fuzzy Filter Ranking (FFR) algorithm produced a "sustainability mapping index" per course. Top-ranked courses were selected until reaching the credit threshold per module: 19 of 27 candidate mandatory courses and 16 of 26 candidate elective courses.
- Phase III (Course Scheduling via MCGP): the 35 selected courses were entered into a Multi-Choice Goal Programming (MCGP) mathematical model, executed in LINGO 18.0, to distribute courses across four semesters while respecting prerequisites, credit limits, and elective constraints.

A sensitivity analysis was also conducted, testing ten different competency-weight scenarios.

## 5. Theoretical/conceptual foundations

The note identifies three conceptual pillars combining strategic management, sustainable education, and operations research:

- He-Xie Management Theory (HXMT), attributed to Youmin Xi (1989), described as drawing on Eastern and Western philosophical concepts to address complex organizational problems under uncertainty. It is divided into the He Principle (an evolutionary mechanism of human coordination and stakeholder engagement) and the Xie Principle (a control mechanism focused on rational process design and mathematical optimization).
- The UNESCO Sustainability Competences Framework, comprising eight domains: Systems thinking (C1), Anticipatory (C2), Normative (C3), Strategic (C4), Collaboration (C5), Critical thinking (C6), Self-awareness (C7), and Integrated problem-solving (C8).
- Three MCDM methods: Best Worst Method (BWM, attributed to Rezaei, 2015), described as requiring fewer pairwise comparisons and offering greater consistency than the traditional AHP method; Fuzzy Filter Ranking (FFR, attributed to Chang and Ku, 2021), applied to handle the imprecise nature of human judgment in ranking and selecting courses; and Multi-Choice Goal Programming (MCGP, attributed to Chang, 2008), used for scheduling to allow multiple aspiration levels and avoid underestimating complex decisions.

## 6. Object being investigated

The object of investigation, as recorded in the note, is the curriculum-planning process itself — specifically, the joint problem of (a) selecting which courses (mandatory and elective) should compose an accounting program based on their contribution to sustainability competencies, and (b) scheduling those selected courses across semesters in a balanced way. The unit of analysis is a single institutional curriculum (one accounting program at one Chinese university), evaluated through the judgments of a small expert panel rather than through, for example, student learning outcomes or longitudinal program performance.

## 7. Main findings

The note reports the following results:

- Competency weights (BWM): Integrated problem-solving (C8) received the highest average weight (0.2423), followed by Critical thinking (C6, weight 0.1877) and Collaboration (C5, weight 0.1679). Anticipatory (C2, weight 0.0557) received the lowest weight.
- Sustainability-based course selection (FFR): the method produced module-specific course rankings. As an example, in the preliminary mandatory module, "Corporate Social Responsibility" ranked first with a mapping index of 0.2279, while "English for Accounting" ranked last (7th) with an index of 0.0224.
- Balanced semester schedule (MCGP): the 35 selected courses (90 total credits) were distributed with reported high semester balance — mandatory-course credits varying smoothly between 12 and 14 per semester, elective credits between 9 and 10 per semester, average difficulty levels ranging from 2.71 to 4.00 for mandatory courses and 3.00 to 3.25 for electives, and minimal global deviations from ideal credit/difficulty targets (G1 = 2; G2 = 1.2857; G3 = 2; G4 = 0.375).
- Sensitivity analysis: across ten tested competency-weight scenarios, course selection remained practically identical in most simulated scenarios, which the note characterizes as demonstrating model stability.

## 8. Main arguments

The note records the authors as arguing that the proposed model is a viable, reliable, and flexible tool for academic planning, capable of precisely modeling subjective human preferences without the kind of simplification that would lead to underestimated decisions. The authors are reported as arguing that the findings show it is possible to migrate accounting education from a purely technicist and manual teaching logic toward a structured approach that addresses contemporary social demands through green competencies and soft skills. A further argument recorded in the note is that theoretical harmonization through He-Xie Theory allowed a workflow in which coordination among academic leadership, professors, and external professionals (the He Principle) operated in full alignment with mathematical optimization models (the Xie Principle).

## 9. Authors' contributions

The note lists three self-described contribution types:

- Theoretical: an unprecedented bridge between operations research and He-Xie Management Theory within educational management and curriculum development.
- Methodological: an integrated BWM-FFR-MCGP framework and the introduction of the "sustainability mapping index" as a quantitative concept for empirically measuring the correlation between university courses and UNESCO's global guidelines.
- Practical: an operational roadmap for academic administrators to formulate balanced, scientifically justified curricula, plus a reliable tool for academic advisors to help students plan individual study paths.

## 10. Limitations

The note records the following limitations and future-research directions as stated by the authors themselves:

- Group aggregation bias: BWM used a simple arithmetic mean to aggregate expert judgments, which can be affected by extreme values; the authors suggest testing Bayesian models or Delphi-based approaches.
- Single-level criteria structure: course evaluations relied on simple competency-level criteria; the authors recommend branching the main criteria into detailed subcriteria.
- Restricted scheduling scope: the scheduling model was limited to semester-level distribution; the authors encourage extending the mathematical approach to daily physical-allocation problems (teachers to classes, classes to specific rooms, daily timetables).
- Lack of methodological comparison: the authors suggest that future studies apply other popular MCDM methods (ANP, FCE, ELECTRE, TOPSIS, VIKOR) to the same data to compare performance and resulting rankings.

Beyond these author-stated limitations, several methodological constraints can be derived from the note's own description of the design. The empirical base is a single case study of one program at one unnamed Chinese university, evaluated by a panel of only five experts; the note gives no indication of statistical power, external validation, or triangulation with other stakeholder groups (e.g., students, employers, or curriculum bodies outside the panel). The "sustainability mapping index" and the competency weights rest entirely on subjective expert ratings (1–10 scales and pairwise comparisons) treated as ground truth, without any independent criterion against which the ratings' validity could be checked, as far as the note describes. The reported sensitivity analysis addresses only variation in competency weights, not variation in the course pool, the rating scale, or the size/composition of the expert panel.

## 11. Implications

The note frames the practical implication as a roadmap that academic administrators could use to build balanced, scientifically justified curricula, and a tool academic advisors could use to help students plan individual study paths. It is DERIVED — not stated directly beyond the "practical contribution" framing — that the authors intend this roadmap to be usable beyond the single case examined, since the note characterizes the contribution generically ("administradores acadêmicos," "orientadores acadêmicos") rather than restricting it explicitly to the studied institution. However, the note provides no evidence bearing on transferability to other institutions, disciplines, or national/regulatory contexts, so any implication of broader applicability remains an inference from the authors' contribution framing rather than an evidenced claim.

## 12. Concepts relevant across the corpus

- Curriculum/course planning reframed as a formal multi-criteria decision-making (MCDM) problem rather than an intuitive administrative task.
- The UNESCO eight-domain sustainability competences framework (systems thinking, anticipatory, normative, strategic, collaboration, critical thinking, self-awareness, integrated problem-solving) as a structuring device for embedding sustainability into curricula.
- The He-Xie Management Theory duality distinguishing a human/stakeholder-coordination mechanism (He) from a rational/mathematical-optimization mechanism (Xie), potentially useful as a general lens for how studies combine participatory and quantitative-optimization elements.
- The concept of a "sustainability mapping index" as a quantitative proxy for the alignment between a course (or curricular unit) and sustainability competency domains.
- Expert-panel-based weighting methods (BWM) as an alternative to broader-consultation approaches, with an explicit claim (per the note) of requiring fewer pairwise comparisons and greater consistency than AHP.
- The distinction between "technicist"/manual curriculum design and a "structured," criteria-based, competency-oriented design approach.
- Sensitivity analysis as a means of claiming model robustness/stability under varying input weights.

## 13. Candidate themes/codes

- MCDM-based curriculum design
- Sustainability competency quantification
- Expert-judgment weighting (BWM)
- Course-to-competency mapping index (FFR)
- Balanced semester scheduling (MCGP / goal programming)
- He-Xie duality (human coordination vs. mathematical optimization)
- Soft skills / socioemotional competencies in accounting education
- Shift from technicist to sustainability-structured pedagogy
- Model stability via sensitivity analysis
- Single-case empirical validation of a planning framework

## 14. Relationships that should be investigated against other studies

- Whether any other studies in the corpus similarly treat curriculum or course planning as a formal multi-criteria decision problem, or whether they instead rely on qualitative, policy, or accreditation-based approaches to curriculum design.
- Whether any other studies in the corpus use or reference the UNESCO sustainability competences framework, and if so, whether they operationalize it the same way (as weighted domains fed into a ranking algorithm) or differently (e.g., as a qualitative coding scheme).
- Whether any other studies in the corpus employ expert-panel elicitation methods (BWM, AHP, Delphi, or similar) for weighting criteria, and how panel size/composition choices compare.
- Whether any other studies in the corpus discuss He-Xie Management Theory, or more broadly theories combining participatory/human elements with formal optimization, and whether such combinations are treated as complementary or as in tension.
- Whether later cross-study analysis corroborates or challenges the claim (recorded here as the authors' argument) that quantitative MCDM modeling can adequately capture "subjective human preferences" in educational planning without loss of nuance.
- Whether any other studies in the corpus address the soft-skills/socioemotional-competency gap in accounting or business education, and whether their diagnoses of the gap's causes align with or diverge from the operational/methodological gap emphasized in this note.

## 15. Potential relevance to the master's research

UNSUPPORTED. The dissertation was deliberately not consulted during this independent analysis. Relevance to the master's research will be assessed only after the independent corpus synthesis and the independent reconstruction of the dissertation have both been completed.

## 16. Tensions or assumptions worth challenging

- The study's central design assumption is that the relevance of a course to a sustainability competency can be validly captured through expert ratings on a 1–10 scale and translated into a single "sustainability mapping index." The note gives no indication of how this instrument's validity or reliability was assessed beyond the model's internal sensitivity analysis; the mapping index therefore functions as a modeling convenience whose correspondence to actual pedagogical content or learning outcomes is not evidenced in the note.
- The claim that the He Principle (human coordination and stakeholder engagement) is genuinely instantiated in the study is worth scrutinizing: as described in the note, "stakeholder engagement" reduces operationally to a panel of five experts providing pairwise comparisons and 1–10 ratings. This is a comparatively narrow empirical realization of a philosophical theory framed (per the note) as addressing "complex organizational problems under uncertainty," and the note does not describe broader deliberation, negotiation, or conflict-resolution processes among stakeholders that the He Principle's description would seem to imply.
- The note's characterization of "balance" (credits and difficulty levels distributed smoothly across semesters, with minimal deviation from goal targets) is a mathematical-optimization criterion, not necessarily a pedagogical one. The note does not report any consideration of pedagogical sequencing, prerequisite learning progression beyond formal prerequisite constraints, or cognitive-load considerations beyond the numeric "difficulty level" score, raising a question about whether "balance" as operationalized equates to educational quality.
- The authors' claim of "model stability" rests on a sensitivity analysis limited to variation in competency weights across ten scenarios; the note does not indicate that the pool of 53 candidate courses, the panel of five experts, or the rating scale itself was varied, so the robustness claim is narrower than the general framing ("demonstrando a estabilidade do modelo") might suggest.
- The compilation of the 53 candidate courses is described in the note only as drawn "from the current curriculum and from programs of other top universities," without further detail on selection criteria; this raises an unaddressed question about potential selection bias favoring courses already resembling those at "leading" institutions, which could shape which competencies appear well- or poorly-represented before any weighting or ranking occurs.
- The study's validation strategy, as recorded in the note, is internal (mathematical consistency, sensitivity stability) rather than external (e.g., comparison with actual student competency outcomes, employer satisfaction, or accreditation review). The authors' concluding claims of viability, reliability, and flexibility should be read as claims about model behavior under the tested conditions, not as demonstrated educational effectiveness.

## 17. Missing information

The note does not provide: the specific name or further institutional detail of the Chinese university where the case study was conducted; the precise criteria or process used to compile the pool of 53 candidate courses; the rationale for selecting a five-member expert panel (e.g., why this size, how experts were identified/recruited, or whether they were compensated); any assessment of inter-rater reliability or agreement among the five experts beyond the arithmetic-mean aggregation noted as a limitation; whether students, alumni, or employers were consulted at any stage; any data on actual student outcomes, competency development, or employment results following (or independent of) the proposed curriculum; details of peer review, funding, or ethical approval processes; the full mathematical formulation of the "sustainability mapping index" or the MCGP goal-programming model beyond the reported summary statistics; and any comparison of the BWM-FFR-MCGP framework's rankings against the alternative MCDM methods (ANP, FCE, ELECTRE, TOPSIS, VIKOR) that the authors themselves flag as absent and worth pursuing in future work.

## 18. Evidence table

| # | Claim | Status | Basis/Reasoning |
|---|-------|--------|------------------|
| 1 | The note reports that the study addresses the Program Course Planning Problem (PCPP) integrating Education for Sustainable Development principles into accounting education. | EXPLICIT | Stated directly in the note's "Tema e Problema de Pesquisa" section, based on the literature note (not independently verified against the original article). |
| 2 | The note reports that the study is motivated by a scarcity of operational studies and quantitative methodologies for curriculum structuring. | EXPLICIT | Stated directly in the note as the motivating problem, based on the literature note. |
| 3 | The note reports the study's objective as proposing an MCDM model to select and schedule courses based on sustainability competency development. | EXPLICIT | Stated directly in the note's "Objetivo e Perguntas de Pesquisa" section. |
| 4 | The note states the authors did not formulate formal statistical hypotheses, only practical research questions. | EXPLICIT | Directly stated in the note ("Embora os autores não formulem hipóteses estatísticas formais..."). |
| 5 | The theoretical foundation combines He-Xie Management Theory, the UNESCO 8-domain sustainability competences framework, and three MCDM methods (BWM, FFR, MCGP). | EXPLICIT | Directly listed in the note's "Fundamentação Teórica" section, based on the literature note. |
| 6 | The empirical case involved a five-expert panel (1 department head, 3 professors, 1 industry professional) at one Chinese university's accounting program. | EXPLICIT | Directly described in the note's "Metodologia" section, Phase I description. |
| 7 | Integrated problem-solving (C8) received the highest competency weight (0.2423); Anticipatory (C2) received the lowest (0.0557). | EXPLICIT | Directly reported numeric results in the note's "Principais Resultados" section. |
| 8 | The MCGP schedule distributed 35 courses (90 credits) across four semesters with reported minimal deviation from credit/difficulty balance targets. | EXPLICIT | Directly reported in the note, including specific goal-deviation values (G1–G4). |
| 9 | A sensitivity analysis across 10 weight scenarios showed the course selection remained largely stable. | EXPLICIT | Directly reported in the note's "Análise de Sensibilidade" bullet. |
| 10 | The authors argue the model is viable, reliable, and flexible, and enables migration from technicist to sustainability-structured accounting education. | EXPLICIT | The note records this as the authors' conclusion in the "Discussão e Conclusões" section; presented as the note's report of the authors' claim, not as independently verified fact. |
| 11 | The He Principle's "stakeholder engagement" is, in this study, operationally realized only through a five-person expert panel providing pairwise comparisons and ratings, which is a narrower instantiation than the broader theory's description implies. | DERIVED | Reasoning: the note describes He-Xie Theory as addressing "complex organizational problems under uncertainty" through human coordination and stakeholder engagement, but the methodology section describes only expert pairwise comparisons and 1–10 ratings by five individuals as the mechanism of "engagement," suggesting a gap between the theory's stated scope and its operational instantiation in this study. |
| 12 | The "balance" achieved by the MCGP schedule is a mathematical-optimization property and is not shown in the note to correspond to pedagogical quality or learning-sequence adequacy. | DERIVED | Reasoning: the note reports balance only in terms of credit totals and numeric difficulty scores meeting goal-programming targets; no outcome, sequencing-quality, or pedagogical-validity measure is reported alongside these figures. |
| 13 | The study's validation strategy is internal/model-consistency-based rather than externally validated against student or employer outcomes. | DERIVED | Reasoning: all reported results (competency weights, mapping indices, schedule balance, sensitivity stability) describe properties of the model's outputs; the note contains no mention of post-implementation outcome data, external stakeholder feedback beyond the initial panel, or comparison to actual student competency gains. |
| 14 | The specific name of the Chinese university where the case study was conducted. | UNSUPPORTED | The note refers only to "uma universidade chinesa" without further identification. |
| 15 | The criteria or process used to compile the pool of 53 candidate courses. | UNSUPPORTED | The note states only that courses were "compiladas da grade atual e de programas de outras universidades de ponta," without describing selection methodology. |
| 16 | Whether inter-rater reliability or agreement among the five experts was assessed. | UNSUPPORTED | The note discusses aggregation via simple arithmetic mean (flagged as a limitation) but does not report any reliability/agreement statistic among experts. |
| 17 | Whether students, alumni, or employers (beyond the one industry professional on the panel) were consulted in the process. | UNSUPPORTED | The note describes only the five-member expert panel; no broader stakeholder consultation is mentioned. |
| 18 | Whether the proposed curriculum, once planned, produced measurable changes in student competency outcomes or employment results. | UNSUPPORTED | The note describes the study as a planning-model case study validated through internal model outputs (weights, indices, schedule balance, sensitivity analysis); no post-implementation or longitudinal outcome data are mentioned. |
