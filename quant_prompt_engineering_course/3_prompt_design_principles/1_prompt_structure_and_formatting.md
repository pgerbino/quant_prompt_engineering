# Prompt Structure and Formatting

## Objective
Learn how to structure and format prompts for optimal LLM performance in finance. Understand how clarity, context, and formatting affect the quality of model outputs.

## Why Structure and Formatting Matter
- Well-structured prompts reduce ambiguity and improve accuracy.
- Formatting (tables, lists, bullet points) guides the model to produce outputs in the desired format.
- Consistent structure helps automate downstream processing (e.g., parsing LLM outputs into dashboards).

## Elements of a Good Prompt
- **Clear Instruction:** State exactly what you want the model to do.
- **Context:** Provide relevant background or data.
- **Output Format:** Specify if you want a table, list, summary, etc.
- **Constraints:** Set limits (e.g., word count, number of items).

## Examples
### Example 1: Table Output
> "List the top 5 performing stocks in a table with columns for ticker, sector, and YTD return."
**Discussion:** The model is more likely to output a structured table.

### Example 2: Bullet Points
> "Summarize the key risks in this portfolio in 3 bullet points."
**Discussion:** Encourages concise, organized output.

### Example 3: Step-by-Step Instructions
> "First, extract all transactions over $10,000. Then, summarize them by category."
**Discussion:** Decomposes a complex task into manageable steps.

### Example 4: Including Context
> "Given the following Q3 earnings report, highlight any unusual expenses."
**Discussion:** Context helps the model focus on relevant details.

## Best Practices
- Use templates for recurring tasks (e.g., report generation).
- Test prompts with different data to ensure robustness.
- Specify output format explicitly to avoid surprises.

## Practice Exercise
- Write a prompt to extract all bond trades from a transaction log and present them in a table.
- Reformat a vague prompt into a clear, structured one.

## Further Reading
- [Prompt Engineering Best Practices](https://platform.openai.com/docs/guides/prompting)
- [Prompt Formatting Tips](https://www.promptingguide.ai/techniques/formatting)
