# ollama-nuggets
Coding nuggets about using Ollama and its LLM models

## Context Length Experiments

This repository contains experiments exploring Ollama's behavior with different context and prediction length settings, using the llama3.2 model.

### Key Findings

- Demonstrated how to use different context lengths (`num_ctx`) and prediction lengths (`num_predict`) with Ollama
- Compared output quality between default and expanded context settings
- Explored the relationship between prediction length and output completeness
- Analyzed token counts and model behavior under different configurations

### Experiments Include:

1. Basic context handling (default 2048 tokens)
2. Extended context (3072 tokens = 1024*3)
3. Various prediction lengths (128, 256, 512, 1024, -1, -2)
4. Comparison with GPT-4o-mini outputs

### Key Takeaways

- Longer context doesn't always mean better results
- Performance trade-offs with increased context length
- Optimal prediction length varies by use case