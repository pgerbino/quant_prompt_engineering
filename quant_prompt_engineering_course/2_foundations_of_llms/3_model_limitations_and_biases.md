# Model Limitations and Biases

## Objective
Recognize the limitations and biases of LLMs in financial applications. Learn how to identify, mitigate, and manage these issues in quantitative workflows.

## Common Limitations of LLMs
- **Context Window:** LLMs can only process a limited number of tokens at once. Long financial documents may be truncated or lose context.
- **Hallucinations:** LLMs may generate plausible-sounding but incorrect or fabricated information, especially when data is ambiguous or missing.
- **Lack of Real-Time Data:** Most LLMs are trained on static datasets and may not reflect the latest market events or regulations.
- **Numerical Reasoning:** LLMs can struggle with complex calculations or interpreting financial tables accurately.

## Sources of Bias
- **Training Data Bias:** If the training data overrepresents certain markets, sectors, or time periods, outputs may be skewed.
- **Prompt Bias:** The way a prompt is phrased can influence the model's response, sometimes reinforcing stereotypes or errors.
- **Confirmation Bias:** LLMs may favor information that matches the prompt's implied assumptions.

## Impact on Financial Decision-Making
- Biased or incorrect outputs can lead to poor investment decisions, compliance failures, or reputational risk.
- Regulatory bodies may scrutinize AI-driven outputs for fairness and transparency.

## Examples
### Example 1: Hallucination
> "Summarize the latest earnings report for XYZ Corp."
**Discussion:** If the model has no data on XYZ Corp., it may invent plausible numbers or statements.

### Example 2: Prompt-Induced Bias
> "Why is Company A a better investment than Company B?"
**Discussion:** The prompt assumes Company A is better, biasing the response.

### Example 3: Data Bias
> "Analyze global market trends."
**Discussion:** If the model was trained mostly on US data, its analysis may underrepresent other regions.

## Best Practices
- Always verify LLM outputs against trusted data sources.
- Use neutral, open-ended prompts to reduce bias.
- Regularly audit model outputs for fairness and accuracy.
- Fine-tune models on diverse, representative financial data when possible.

## Practice Exercise
- Write a prompt that could introduce bias and rewrite it to be neutral.
- Test an LLM on a non-US financial report and analyze the output for bias or errors.

## Further Reading
- [AI Bias in Finance](https://www.brookings.edu/articles/ai-bias-in-financial-services/)
- [Hallucinations in LLMs](https://arxiv.org/abs/2302.06453)
