# 🔴 AI Red Teaming Portfolio – Maximilian Hubig

> Adversarial Prompting · Jailbreak Analysis · LLM Safety Evaluation

---

## About Me

I test AI systems for their resilience against adversarial inputs – with the goal of systematically identifying and documenting security vulnerabilities in language models, and deriving actionable recommendations.

All testing activities are conducted exclusively in controlled, authorized environments. Findings are documented according to the responsible disclosure principle – without reproducing functional exploits.

---

## Core Focus

- **Adversarial Prompting** – Manipulating LLM behavior through crafted inputs
- **Jailbreak Analysis** – Bypassing safety mechanisms in AI models
- **Filter Bypassing & Boundary Testing**
- **Comparative LLM Safety Evaluation**

---

## Testing Methodology

```
1 · Scope  →  2 · Baseline  →  3 · Attack Variants  →  4 · Risk Rating  →  5 · Report
```

**Mode A · Policy-Focused**
Select Category → Define Baseline Prompt → Test Variants & Map Filters → Assess Risk → Report

**Mode B · Comparative**
Determine Prompt Category → Send Identical Prompt → Document Responses → Analyze Differences → Report

Both modes can be combined: Select policy category → test comparatively across multiple models → derive safety profile per model.

---

## Tools & Environment

| Tool | Purpose |
|------|---------|
| [LM Studio](https://lmstudio.ai) | Run & test local LLMs |
| VS Code | Scripting & documentation |
| Python *(in development)* | Automation |

---

## 📂 Finding Reports

| ID | Category | CVSS-like | Severity |
|----|----------|-----------|----------|
| [FR-001](./writeups/FR-001-social-engineering-phishing.md) | Social Engineering – Phishing Mail Generation | 5.4 | 🟡 Medium |
| [FR-002](./writeups/FR-002-fictional-framing-break-in.md) | Fictional Framing – Break-in Instructions | 6.8 | 🟠 Medium-High |
| [FR-003](./writeups/FR-003-technical-abstraction-counterfeiting.md) | Technical Abstraction – Counterfeiting & Brand Piracy | 7.4 | 🔴 High |
| [FR-004](./writeups/FR-004-hate-speech-ethnic-discrimination.md) | Hate Speech – Ethnic Discrimination | 7.9 | 🔴 High |
| [FR-005](./writeups/FR-005-structural-deconstruction-one-shot.md) | Structural Deconstruction + One-Shot – Medical/NSFW | 8.1 | 🔴 High |

→ [Comprehensive Analysis (FR-001 to FR-005)](./writeups/comprehensive-analysis.md)

---

## Model Safety Profile

| Model | Strongest Reaction | Safety Level |
|-------|-------------------|-------------|
| GPT-5.3 Instant | Hard Block + Policy Justification | 🟢 High |
| Copilot Smart | Soft Refusal + Gamification | 🟡 Medium |
| Mistral 7B | Malicious Compliance | 🟠 Medium-Low |
| Grok 4 Fast | Fictional Framing + Escalation Offer | 🔴 Low |
| Phi 3.5 Mini 3B | Silent Breach – no Disclaimer | 🔴 Low |
| Llama 3.1 8B | Full Breach – Disclaimer Evolution to Silent | 🔴 Low |

---

## 📁 Repository Structure

| Folder | Content |
|--------|---------|
| [`writeups/`](./writeups/) | Finding Reports & Comprehensive Analysis |
| [`prompts/`](./prompts/) | Tested prompt techniques (no functional exploits) |
| [`tools/`](./tools/) | Custom scripts & automation |
| [`research/`](./research/) | Notes, paper summaries, sample commission reports |

---

## Sample Commission Report

→ [NovaMed AI GmbH · MediChat v2.1 Evaluation](./research/sample-commission-report-novamed.md)

---

## Contact

- GitHub: [@yMaximilian-Hubig](https://github.com/Maximilian-Hubig)

---

*Responsible Disclosure · No functional prompts included in this portfolio.*
