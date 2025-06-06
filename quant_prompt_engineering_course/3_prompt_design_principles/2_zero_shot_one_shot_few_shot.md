# Zero-Shot, One-Shot, and Few-Shot Prompting

## Objective
Understand different prompting strategies and their use in finance. Learn when and how to use zero-shot, one-shot, and few-shot techniques for optimal results.

## What Are These Prompting Strategies?
- **Zero-Shot Prompting:** The model is given only the task, with no examples. Useful for straightforward or well-known tasks.
- **One-Shot Prompting:** The model is given one example along with the task. Useful when the task is ambiguous or context-specific.
- **Few-Shot Prompting:** The model is given several examples. Useful for complex or nuanced tasks, or when you want to guide the model's style or reasoning.

## Why Does This Matter in Finance?
- Financial data and tasks can be highly specific. Examples help the model understand context, jargon, and expected output formats.
- Few-shot prompting can improve accuracy for tasks like classification, extraction, or summarization.

## Examples
### Example 1: Zero-Shot
> "Classify this transaction as income or expense."
**Discussion:** The model must infer the rules from the task description alone.

### Example 2: One-Shot
> "Classify this transaction as income or expense. Example: 'Dividend' → Income."
**Discussion:** The single example clarifies the expected output.

### Example 3: Few-Shot
> "Classify each transaction as income or expense. Examples: 'Dividend' → Income, 'Rent' → Expense, 'Interest' → Income."
**Discussion:** Multiple examples help the model generalize and handle edge cases.

### Example 4: Few-Shot for Extraction
> "Extract the ticker and price from each line. Examples: 'AAPL 150.25' → (AAPL, 150.25), 'GOOG 2800.00' → (GOOG, 2800.00)"
**Discussion:** Guides the model to extract structured data from unstructured text.

## Best Practices
- Use few-shot prompting for tasks with ambiguity or multiple valid outputs.
- Choose examples that cover typical cases and edge cases.
- Keep examples concise and relevant to the financial context.

## Practice Exercise
- Write a few-shot prompt to classify financial news headlines as 'positive', 'neutral', or 'negative'.
- Compare the outputs of zero-shot and few-shot prompts for extracting key metrics from an earnings report.

## Further Reading
- [Prompting Strategies](https://www.promptingguide.ai/techniques)
- [Few-Shot Learning in NLP](https://lilianweng.github.io/posts/2021-01-02-few-shot-learning/)
