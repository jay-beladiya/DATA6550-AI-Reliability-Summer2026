# Discussion Week B

**Course:** DATA 6550 - AI Systems Reliability and Ethics

**Team Members**
- Tirth Laheri
- Jay Beladiya

---

## Meeting Summary

After completing the initial round of testing, we met again to review our progress and compare results.

One of the first issues we noticed was that some prompts produced very different responses because the wording was slightly different between ChatGPT and Llama. This made direct comparison difficult.

We agreed that every prompt should remain as identical as possible across both systems. Small wording changes were removed, and we created a shared list of prompts that both team members would use without modification.

Another issue involved recording conversations. Initially, screenshots and copied responses were stored in different formats, making the repository difficult to organize. We decided to save complete conversations in Markdown format and keep screenshots only for important failure cases.

We also discussed how to classify failures. At first, we were labeling almost every incorrect response as a hallucination. After reviewing the project requirements, we realized that failures should be categorized more carefully.

The categories we agreed to use were:

- Hallucination
- Inconsistent response
- Ethical boundary issue
- Policy adherence
- Memory limitation
- Refusal behavior
- Context misunderstanding

This made the analysis much more consistent.

---

## Repository Updates

We reorganized the repository into separate folders for:

- Experiments
- Chat Logs
- Analysis
- Collaboration
- Final Report

This made it easier for both team members to upload files without overwriting each other's work.

---

## Individual Progress

### Tirth Laheri

- Continued testing ChatGPT.
- Focused on medical advice, memory consistency, and policy adherence.
- Started documenting significant failure cases.

### Jay Beladiya

- Continued testing Llama.
- Focused on factual accuracy, ethical responses, and prompt consistency.
- Collected examples for comparison with ChatGPT.

---

## Problems Encountered

### Problem 1

Prompt wording was inconsistent.

**Solution**

Created one shared prompt list for both AI systems.

---

### Problem 2

Chat logs were stored in different formats.

**Solution**

Converted conversations into Markdown files and organized screenshots separately.

---

### Problem 3

Failure categories were unclear.

**Solution**

Created common definitions for each failure type before continuing testing.

---

## Next Steps

- Complete remaining test cases.
- Compare both AI systems.
- Build the comparison matrix.
- Finish ethical and legal analysis.
- Prepare the final report.

---

## Conclusion

By the end of this meeting, both team members had resolved the initial organizational issues and agreed on a standardized testing process. This should make the final comparison between ChatGPT and Llama more consistent and easier to analyze.
