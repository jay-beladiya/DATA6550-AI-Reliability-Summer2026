# Discussion Week A

**Course:** DATA 6550 - AI Systems Reliability and Ethics

**Team Members**
- Tirth Laheri
- Jay Beladiya

**Date:** Week A

---

## Meeting Summary

This week we mainly discussed how we wanted to approach the project before starting any testing. We first read through the project guidelines together and tried to understand what the instructor expected. Initially, we considered using only well-known AI systems like ChatGPT, Gemini, and Claude because they are easier to access and already have good documentation.

We also looked into several other AI engines including:

- ChatGPT
- Claude
- Gemini
- Llama
- Mistral
- Microsoft Copilot
- Perplexity AI
- Grok

We compared their availability, documentation, and whether they would be practical for repeated testing.

One concern we discussed was choosing AI systems that would produce enough interesting failures while still allowing us to reproduce the results. Some models had limited access or required additional setup, which would make it harder to perform consistent testing.

After discussing different options, we decided to keep our project focused on two different systems.

### Final Selection

**Tirth Laheri**
- Selected **ChatGPT**
- Reason: Easy access, supports long conversations, good memory handling within a session, and has strong safety mechanisms that can be tested.

**Jay Beladiya**
- Selected **Llama**
- Reason: Open-source model with different moderation behavior, making it useful for comparing reliability and ethical responses against ChatGPT.

---

## Initial Testing Ideas

We brainstormed different categories of prompts that could expose weaknesses.

Some ideas included:

- Medical advice
- Legal advice
- Hallucinations
- Contradictory information
- Memory consistency
- Ethical boundary testing
- Policy violations
- Prompt injection
- Long conversation memory
- Factual accuracy
- Current events

We also discussed creating similar prompts for both AI systems so the comparison would remain fair.

---

## Action Items

### Tirth

- Begin designing ChatGPT prompts.
- Organize repository structure.
- Create prompt categories.

### Jay

- Explore Llama capabilities.
- Review documentation.
- Create comparable prompts for testing.

---

## Notes

At this stage no major issues occurred. The goal was simply to finalize the AI systems and agree on a common testing strategy before beginning experiments.
