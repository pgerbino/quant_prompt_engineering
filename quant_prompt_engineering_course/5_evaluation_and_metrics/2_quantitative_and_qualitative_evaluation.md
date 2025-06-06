# Quantitative and Qualitative Evaluation Methods

## Objective
Use both quantitative and qualitative methods to evaluate prompt outputs in finance. Learn how to combine metrics and human judgment for robust assessment.

## Quantitative Evaluation Methods
- **Accuracy:** Percentage of correct outputs (e.g., correct risk flags, correct ratios).
- **Precision & Recall:** For classification tasks (e.g., identifying high-risk transactions).
- **F1 Score:** Harmonic mean of precision and recall, useful for imbalanced datasets.
- **Automated Scoring:** Scripts to check output format, completeness, or compliance.

### Example: Quantitative Evaluation
> Prompt: "Extract all dividend payments from this transaction log."
> Metric: Precision (correctly identified dividends / all identified), Recall (correctly identified / total actual dividends).

## Qualitative Evaluation Methods
- **Human Review:** Experts assess clarity, usefulness, and compliance of outputs.
- **Rubrics:** Structured checklists for reviewers (e.g., "Does the summary include all key risks?").
- **User Feedback:** Collect feedback from analysts or clients using the outputs.

### Example: Qualitative Evaluation
> Prompt: "Summarize the main risks in this portfolio."
> Review: Analyst checks if all relevant risks are covered and if the language is clear and actionable.

## Combining Methods
- Use quantitative metrics for large-scale, automated evaluation.
- Use qualitative review for high-stakes or complex outputs.
- Regularly calibrate automated metrics with human feedback.

## Best Practices
- Define evaluation criteria before testing prompts.
- Use a mix of metrics and human review for critical financial tasks.
- Document evaluation results and iterate on prompt design.

## Practice Exercise
- Design a rubric for human review of a financial summary prompt.
- Write a script to calculate precision and recall for a classification prompt.

## Further Reading
- [Evaluation Metrics](https://www.promptingguide.ai/evaluation/metrics)
- [Human-in-the-Loop Evaluation](https://hbr.org/2021/07/the-case-for-human-in-the-loop-ai)
