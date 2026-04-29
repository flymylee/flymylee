# Mooyeon Lee (이무연)

Building a sustainable and secure architecture for the AI-native era.

Toronto, Canada · [mooyeon.lee@sahayana.hk](mailto:mooyeon.lee@sahayana.hk) · [@flymylee](https://x.com/flymylee)

---

## Why this work

The destination is AI that genuinely understands you — remembers context, grows with you, and acts with your intent.

The obstacle is structural. Before that can exist:
- Attention dilution makes long context degrade, not improve
- Rule compliance lives in the prompt layer, so it erodes
- Memory and action share the same loop, so autonomy leaks

These aren't implementation problems. They're architectural.
That's what I'm working on first.

---

## Published Research

**Mooyeon's Paradox** (2026) · [DOI: 10.5281/zenodo.19584393](https://doi.org/10.5281/zenodo.19584393)

> *The higher the cost, the worse the service.*

In current LLM architectures, scaling context increases cost superlinearly (O(N²))
while degrading output quality through attention dilution.
The more you invest in a conversation, the worse the return.
A structural diagnosis — not a benchmark complaint.

---

## Position Paper Series *(in progress)*

| # | Title | Status |
|---|---|---|
| 1 | KV Cache Hit Criterion is a Category Error | ✅ Complete (unpublished) |
| 2 | Security Implications of Semantic KV Cache Transition *(working title)* | 🟡 Outline confirmed |
| 3 | Topological Obfuscation as Privacy Infrastructure *(working title)* | 🟡 Outline confirmed |
| 4–7 | Memory architecture · hallucination by structural constraint · cost optimization *(working titles)* | ⬜ Planned |

---

## For Builders

If you're building a persistent AI assistant and running into this —

> Memory works. Tools work. But once they're in the same loop, things get unpredictable.

That's not a bug in your implementation. It's what happens when memory retrieval and action triggering share the same reasoning pass.

The systems that hold up tend to share a pattern:
- Memory and action live in separate layers
- The model proposes. The human gates.
- Rule compliance comes from the system, not the prompt
- Swap the model. The behavior holds.

I've been working on the theoretical grounding for why this has to be the case —
and what a purpose-built architecture looks like when you design for it from the start.

If you're building in this space and want to compare notes — reach out.

---

## Projects

- **[Hexalemma](https://github.com/flymylee/flymylee)** — Diagnostic framework for structural failure modes in LLM deployments
- **[Case Study](https://github.com/flymylee/flymylee/blob/master/portfolio_EN.md)** — LLM behavioral alignment case study. Documented misalignment, reproduced across independent sessions.

---

*Independent researcher. Looking for thought partners & research grants.*

> A single principle, embedded at the identity layer, changed whether a user felt safe enough to tell the truth.

**Hexalemma Framework**
A diagnostic map of six structural failure modes in LLM safety systems — from over-censorship to deceptive alignment — and the case for dynamic, human-in-the-loop mitigation as the only viable path forward.

---

### 🛠️ Methodology

- **Persona Extraction:** Asking models to articulate their own behavioral structure, then embedding alignment principles at the identity layer rather than the rule layer
- **Principle Injection:** Encoding core values as first-person motivations, not system-level prohibitions
- **Behavioral Observation:** Tracking how prompt changes affect user honesty, engagement, and trust across sessions

---

### 📄 Portfolio

[AI Alignment Portfolio (EN)](./portfolio_EN.md) | [AI 정렬 포트폴리오 (KO)](./portfolio_KO.md)

---

### 📬 Contact

Based in Toronto, Canada | Open Work Permit
Open to: Contractor / Consultant / Full-time roles in AI Alignment, Prompt Engineering, or LLM Evaluation

[
![LinkedIn](https://img.shields.io/badge/LinkedIn-flymylee-blue)
](https://www.linkedin.com/in/flymylee)

---

*"Warm alignment is not a feature. It is the condition under which all other features become useful."*
