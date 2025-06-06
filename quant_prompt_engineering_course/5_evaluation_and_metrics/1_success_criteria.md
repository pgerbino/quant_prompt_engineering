# Defining Success Criteria for Prompt Outputs in Finance

## Objective
Establish clear criteria for evaluating LLM-generated outputs in financial contexts. Learn how to define, measure, and enforce success for prompt engineering in quantitative workflows.

## Why Define Success Criteria?
- Ensures outputs are accurate, relevant, and actionable for financial decision-making.
- Provides a basis for automated and manual evaluation.
- Supports compliance, auditability, and continuous improvement.

## Key Success Criteria
- **Accuracy:** Are the outputs factually correct and free from hallucinations?
- **Relevance:** Do the outputs address the specific financial question or task?
- **Completeness:** Are all required data points or insights included?
- **Consistency:** Are outputs formatted and structured as expected?
- **Compliance:** Do outputs meet regulatory and business requirements?

## Examples
### Example 1: Financial Summary
> Prompt: "Summarize the key financial ratios in this balance sheet."
> Success Criteria: Output includes at least 3 ratios (e.g., ROE, Debt/Equity, Current Ratio), values are correct, and summary is under 100 words.

### Example 2: Risk Report
> Prompt: "List all high-risk transactions in this portfolio."
> Success Criteria: All transactions above a defined risk threshold are included, output is in a table, and each entry cites the risk factor.

### Example 3: Compliance Checklist
> Prompt: "Check this transaction log for AML violations."
> Success Criteria: All flagged transactions are relevant, output references the specific regulation, and no false positives.

## Best Practices
- Define criteria before deploying prompts in production.
- Use both quantitative (metrics, counts) and qualitative (human review) measures.
- Document criteria for each prompt and update as business needs evolve.

## Practice Exercise
- Write success criteria for a prompt that generates a monthly performance report.
- Review a sample LLM output and evaluate it against defined criteria.

## Further Reading
- [Evaluating LLM Outputs](https://www.promptingguide.ai/evaluation)
- [AI in Financial Reporting](https://www2.deloitte.com/us/en/pages/audit/articles/artificial-intelligence-in-financial-reporting.html)
