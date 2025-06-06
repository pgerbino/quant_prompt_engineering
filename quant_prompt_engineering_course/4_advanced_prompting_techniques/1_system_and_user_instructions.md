# Using System and User Instructions Effectively

## Objective
Learn to leverage system and user instructions for better prompt outcomes in finance. Understand how to set context, roles, and constraints for LLMs.

## What Are System and User Instructions?
- **System Instructions:** Set the overall behavior, role, or constraints for the LLM (e.g., "You are a financial analyst.").
- **User Instructions:** Provide the specific task or question (e.g., "Summarize the risk profile of this portfolio.").

## Why Use Them in Finance?
- System instructions help the model adopt the right persona (analyst, auditor, trader) and follow compliance or style guidelines.
- User instructions focus the model on the immediate task, ensuring clarity and relevance.

## Examples
### Example 1: Setting a Role
> System: "You are a compliance officer."
> User: "Review this transaction report for potential AML violations."
**Discussion:** The model is primed to focus on compliance and risk.

### Example 2: Adding Constraints
> System: "You are a financial analyst. Always provide answers in bullet points."
> User: "Summarize the key findings from this earnings call transcript."
**Discussion:** Ensures output is concise and formatted for easy review.

### Example 3: Combining Instructions
> System: "You are an investment advisor. Use only publicly available information."
> User: "Provide a risk assessment for this portfolio."
**Discussion:** Helps ensure compliance and transparency.

## Best Practices
- Use system instructions to set the right role and tone for the model.
- Combine system and user instructions for complex or regulated tasks.
- Be explicit about constraints (format, data sources, compliance).

## Practice Exercise
- Write a system instruction for a model acting as a risk manager.
- Combine system and user instructions to automate a compliance check.

## Further Reading
- [System vs User Prompts](https://platform.openai.com/docs/guides/gpt)
- [Prompt Roles and Instructions](https://www.promptingguide.ai/techniques/role)
