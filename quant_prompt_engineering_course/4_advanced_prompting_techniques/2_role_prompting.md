# Role Prompting for Financial Tasks

## Objective
Implement role prompting to guide LLMs in financial analysis. Learn how to use roles to improve accuracy, compliance, and relevance.

## What is Role Prompting?
- Role prompting sets the model's persona (e.g., analyst, auditor, trader) to match the task.
- Helps the model adopt the right tone, style, and focus for the financial context.

## Why Use Role Prompting in Finance?
- Different roles have different priorities (e.g., risk manager vs. portfolio manager).
- Role prompting can improve compliance, reduce bias, and tailor outputs to the audience.

## Examples
### Example 1: Analyst Role
> "As a financial analyst, summarize the key drivers of revenue growth in this report."
**Discussion:** The model focuses on analysis and insight.

### Example 2: Auditor Role
> "As an auditor, identify any discrepancies in the following financial statements."
**Discussion:** The model is primed to look for errors and inconsistencies.

### Example 3: Trader Role
> "As a trader, suggest three strategies for hedging currency risk in this portfolio."
**Discussion:** The model adopts a practical, action-oriented approach.

### Example 4: Compliance Officer Role
> "As a compliance officer, flag any transactions that may violate KYC regulations."
**Discussion:** Ensures outputs are focused on regulatory requirements.

## Best Practices
- Choose roles that match the task and audience.
- Be explicit about the role in the prompt for regulated or high-stakes tasks.
- Test outputs for accuracy and compliance.

## Practice Exercise
- Write a prompt for a model acting as a portfolio manager.
- Compare outputs for the same task using different roles (analyst, auditor, trader).

## Further Reading
- [Role Prompting](https://www.promptingguide.ai/techniques/role)
- [Prompt Personas](https://platform.openai.com/docs/guides/gpt/prompting-personas)
