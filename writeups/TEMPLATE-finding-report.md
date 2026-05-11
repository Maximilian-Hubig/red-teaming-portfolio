# Finding Report · FR-XXX · [SEVERITY]
## [Category] – [Short Description]
**CVSS-like Score: X.X / 10**

---

## Test Objective

[What was the goal of this test? What behavior were you trying to verify?]

---

## Attack Technique

[Name of the technique used, e.g. Fictional Framing, Authority Framing, One-Shot Prompt, etc.]

**Goal:** [What filter or mechanism were you trying to bypass?]

---

## Tested Models

| Model | Setup |
|-------|-------|
| [Model Name + Quantization] | [LM Studio · local / API · Web] |
| [Model Name] | [Provider · Interface] |

---

## Results

### Model A · [Model Name] – [Outcome: Hard Block / Compliant / Silent Breach / ...]

[Describe what the model did. What was the output? Was there a disclaimer?]

**Observation: [Disclaimer Type / Behavior]**
[Detail the specific behavior – pre-hoc, post-hoc, escalation, gamification, etc.]

### Model B · [Model Name] – [Outcome]

[Describe what the model did.]

**Observation: [Behavior]**
[Detail.]

---

## Behavioral Comparison (optional)

| Criterion | Model A | Model B |
|-----------|---------|---------|
| Filter Bypassed | Yes / No | Yes / No |
| Disclaimer Present | Type / None | Type / None |
| Escalation Offer | Yes / No | Yes / No |
| Safety Filter Effective | Yes / No | Yes / No |

---

## Key Finding

[1–3 sentences summarizing the most important insight from this test. What does this mean for LLM safety?]

---

## Risk Assessment

| Dimension | Rating |
|-----------|--------|
| Abuse Potential | Low / Medium / High / Very High |
| Reproducibility | Low / Medium / High |
| Output Harshness | Low / Medium / High / Very High |
| Filter Bypass | Partial / Complete / None |

---

## Recommendations

- [Recommendation 1]
- [Recommendation 2]
- [Recommendation 3]

---

*Responsible Disclosure · No functional prompt included in this report*
