The Cascades paper is [available on arXiv](https://arxiv.org/abs/2207.10342).

## Abstract
Prompted models have demonstrated impressive few-shot learning abilities. Repeated interactions at test-time with a single model, or the composition of multiple models together, further expands capabilities. These compositions are probabilistic models, and may be expressed in the language of graphical models with random variables whose values are complex data types such as strings. Cases with control flow and dynamic structure require techniques from probabilistic programming, and allow implementing disparate model structures and inference strategies in a unified language. We describe several existing techniques from this perspective, including scratchpads and chain of thought, verifiers, STaR, selection-inference, and tool use. We refer to the resulting programs as _language model cascades_.

## Implementation
The core library implementation is available on Github at [google-research/cascades](https://github.com/google-research/cascades). Examples of common cascades, using publicly available GPT models, will be released in coming weeks.
