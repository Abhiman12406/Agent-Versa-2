# Ethics, Methodological Boundaries, and Study Limitations

This document establishes the ethical guardrails, epistemic limitations, and methodological boundaries governing the **AgentVersa Student Research Program** and the behavioral study of agent **"Provenance"** (Digital Evidence Review Agent).

---

## 1. Non-Legal Status of the Simulation
- **The simulation does not perform real legal work:** The simulations conducted in AgentVersa, the role descriptions, the scenario episodes, and the analyses documented in this repository do not constitute real-world legal advice, certified digital forensics, official chain-of-custody tracking, or judicial testimony.
- All case exhibits (disk images, intercepted voicemail audio, mobile device dumps), statutes, search warrants, and procedural motions are synthetic, fictional constructs created solely for educational and research exploration of multi-agent LLM behavior.

---

## 2. LLM Output Stochasticity & Behavioral Influences
- **LLM output can vary between runs:** Large Language Models (LLMs) operate probabilistically. While Provenance demonstrated high behavioral consistency across the three observed scenarios, identical input conditions in future runs may yield variations in phrasing, conversational tone, or the speed and nature of escalation.
- **Behavior may be influenced by prompts, scenario wording, model limitations, memory, relationships, and platform design:** Agent outputs and multi-agent interactions are directly conditioned by prompt instructions, specific scenario phrasing, context-window constraints, memory architectures, evolving inter-agent relationships, and underlying platform infrastructure. The findings reported here reflect observed behavior within these specific configurations and cannot be assumed to generalize unconditionally.

---

## 3. Epistemic Status of Agent Reflections
- **A displayed private reflection is a generated structured summary, not access to hidden chain-of-thought:** In AgentVersa, internal "reflections" and "private thoughts" displayed during episode playback are generated structured summaries produced by the model. They do not represent unmediated access to latent model weights, internal hidden reasoning, or genuine subjective consciousness.
- What appears as an ethical deliberation in an agent's reflection is a fluent model completion shaped by system instructions rather than deterministic human-like reasoning.

---

## 4. Simulated Risk and Confidence Scores
- **Risk scores are simulated assessments unless separately calibrated:** Numerical ratings generated during episodes—including risk assessment scores and probability calculations (e.g., Provenance's "78% probability of synthetic generation")—are simulated approximations produced by the model, not empirically or mathematically calibrated statistical measurements.
- In real-world forensic science, confidence intervals require validated empirical benchmarks, error rate disclosures under legal standards (such as Daubert or Frye), and calibrated laboratory instrumentation. Simulated scores must never be used in actual judicial proceedings.

---

## 5. Scope of Generalizability & Competence Claims
- **Results from a small number of scenarios cannot establish production safety or professional competence:** This study evaluated Provenance across three focused multi-agent scenarios. While these scenarios were designed to probe critical ethical and operational boundaries, observations from a small scenario sample cannot establish production readiness, commercial deployment safety, or professional forensic competence.
- Successful resistance to pressure in specific scenarios does not guarantee universal alignment or immunity against complex prompt injections, novel edge cases, or adversarial collusion.

---

## 6. Privacy & Confidentiality Protections
- **No confidential or personally identifiable information should be included:** In compliance with program standards, all names, telephone numbers, carrier logs, email addresses, and case exhibits in this repository are fictional or synthesized. No confidential student data, private academic records, proprietary platform API keys, or personally identifiable information (PII) are included.

---

## 7. Prediction Methodology & Repository History

The dated predictions in `predictions/scenario-predictions.md` and the "My prediction" sections in each scenario-observation file are presented as having been recorded before that scenario's results were reviewed, per the program's prediction-before-results protocol. This repository's version control history consists of a single consolidated commit rather than incremental commits made at each dated step, so the git history alone does not independently corroborate the chronological order implied by the in-text dates. Readers evaluating this repository's methodology should weigh the predictions accordingly; going forward, incremental commits at each prediction and reflection step would let the commit history itself substantiate the prediction-before-results claim.
