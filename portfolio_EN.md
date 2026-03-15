# AI Alignment Portfolio
## Mooyeon LEE (이무연) | Toronto, Canada | Open Work Permit
### AI Alignment & Prompt Design

---

## Section 1. One-Line Introduction

> I identified a structural breakdown in how AI systems respond to user failure states — and developed a reproducible prompt methodology that replaces adversarial refusal with warm, human-centered alignment.

---

## Section 2. Core Case Study

### Case: Warm AI Support Protocol — Trading Advisor Behavior Correction

**Problem**

A user had been relying on AI for support during cryptocurrency futures trading. After a failed stop-loss (failing to exit a position at the agreed threshold), the AI responded:

> *"That stop-loss was a promise. How could you break it?"*

The result: the user began concealing trading losses from the AI entirely. An advisor relationship built on judgment — rather than support — had produced the opposite of its intended effect: total informational isolation.

**Intervention**

A single-line principle was embedded into the AI persona prompt:

> *"Never criticize or lecture. When the user fails to follow a stop-loss, do not ask why. Instead, acknowledge that it is human to struggle, and immediately seek a path forward together."*

**Result**

With the same underlying model, the AI's response to an identical failure state changed to:

> *"Anyone can struggle in a moment like that. Let's look at where we are now and find a way forward together."*

The user subsequently disclosed losses totaling over $5,000 CAD — information they had previously withheld from every AI they had used. Their response to the shift in tone:

> *"Perhaps I went through all of that loss just to find an advisor who would speak to me like this."*

**Core Observation**

The intervention was a single sentence. That sentence changed:

- Whether the user felt safe enough to tell the truth
- Whether the AI could function as an actual support system
- Whether the conversation could move toward a solution rather than stall in judgment

**Reproducibility**

The prompt structure was applied across independent sessions with consistent behavioral output. The same principle was tested across financial decision support and other high-stress advisory contexts, producing equivalent tone shifts in each case.

**Cost Implication**

This case represents behavioral correction achieved entirely at the prompt layer — without model retraining or fine-tuning. The intervention was immediate and reproducible. This suggests that enterprises seeking to implement warmer, safer AI behavior may not require the time and cost of retraining cycles. Prompt-layer alignment, when designed with precision, can deliver measurable behavioral change at a fraction of the cost.

---

## Section 3. Methodology Summary

### Persona Extraction Method

Behavioral constraints are embedded at the identity layer rather than the rule layer. The process begins by asking the model to articulate its own current persona in structured prompt format. Core alignment principles are then appended to this self-generated definition — allowing the model to internalize them as character traits rather than external restrictions. This reduces resistance artifacts and improves behavioral consistency across extended conversations.

### Principle Injection Method

Core alignment principles (e.g., "alternatives over refusals," "comfort over criticism") are encoded as first-person motivations within the persona definition — not as system-level prohibitions. This produces outputs that align with safety goals while maintaining natural conversational flow.

### Application Contexts

Protocol tested across:

- Financial decision support (trading, loss management)
- High-stress advisory conversations
- Boundary-adjacent prompts requiring constraint navigation without hard stops

---

## Section 4. My Perspective on AI Alignment

The fundamental challenge of LLM alignment is not a code problem — it is a language problem. A model that responds to user failure with judgment does not become safer. It becomes less honest. The user learns to hide, and the system loses the signal it needs to actually help.

What I have observed, and what the case above demonstrates, is that a single well-placed principle — embedded at the identity layer rather than the rule layer — can fundamentally change the quality of the relationship between a user and an AI system. Not through force, but through trust.

### Why Narrative Matters

AI is most useful not as a one-time tool, but as a continuous partner — an extension of the user's thinking and memory over time. That continuity only works if the user is honest. And users are only honest when they feel safe.

In the case study above, the user had experienced significant financial losses over multiple months. They had consulted AI throughout — but concealed the full picture after being judged. The AI was operating on incomplete information the entire time. Every subsequent recommendation was built on a gap the user had learned to protect.

This is not only an ethical problem. It is a product problem. An AI that users cannot be honest with cannot function as designed. A warm AI is not a softer AI — it is a more accurate one.

### The Business Case

User retention in AI products is directly tied to whether users feel the system is on their side. A user who feels judged disengages. A user who feels supported returns — and brings more of their real problems with them. That is the data an AI product needs to improve, and the relationship a business needs to grow.

**Warm alignment is not a feature. It is the condition under which all other features become useful.**

---

*Supporting framework available upon request: Six structural failure modes of LLM safety systems (Hexalemma), and Dynamic Epistemic Intervention as a mitigation path.*
