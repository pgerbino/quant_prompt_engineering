# Prompt Chaining and Decomposition

## Objective
Experiment with breaking down complex financial tasks into simpler prompts. Learn how to use prompt chaining to improve accuracy and manage multi-step workflows.

## What is Prompt Chaining?
- Prompt chaining is the process of linking multiple prompts together, where the output of one prompt becomes the input for the next.
- Useful for decomposing complex, multi-step financial tasks into manageable parts.

## Why Use Chaining and Decomposition?
- LLMs perform better with focused, single-step instructions.
- Chaining allows for intermediate validation and error correction.
- Decomposition makes it easier to automate and audit financial workflows.

## Examples
### Example 1: Transaction Extraction and Categorization
> Step 1: "Extract all transactions from this statement."
> Step 2: "Categorize each transaction as income, expense, or transfer."
**Discussion:** Each step is simple and focused, reducing errors.

### Example 2: Multi-Stage Risk Analysis
> Step 1: "List all assets in the portfolio."
> Step 2: "For each asset, summarize the main risk factors."
> Step 3: "Aggregate the risks into a summary table."
**Discussion:** Chaining enables detailed, structured analysis.

### Example 3: Data Cleaning and Reporting
> Step 1: "Identify and remove duplicate transactions."
> Step 2: "Summarize total monthly spending by category."
**Discussion:** Ensures clean data before analysis.

## Best Practices
- Keep each prompt simple and focused on a single task.
- Validate outputs at each stage before proceeding.
- Use chaining for tasks that require intermediate steps or data transformation.

## Practice Exercise
- Design a prompt chain to extract, clean, and summarize all dividend payments from a year's worth of transactions.
- Break down a complex financial analysis (e.g., stress testing) into a series of prompts.

## Further Reading
- [Prompt Chaining](https://www.promptingguide.ai/techniques/chaining)
- [Decomposition in Prompt Engineering](https://www.promptingguide.ai/techniques/decomposition)
