# Prompt-OIRL
code for paper Query-Dependent Prompt Evaluation and Optimization with Offline Inverse Reinforcement Learning
https://arxiv.org/pdf/2309.06553.pdf 

### Preview

![Image](Prompt_OIRL_preview.png)

### Abstract 

> In this study, we aim to enhance the arithmetic reasoning ability of Large Language Models (LLMs) through zero-shot prompt optimization. We identify a previously overlooked objective of query dependency in such optimization and elucidate two ensuing challenges that impede the successful and economical design of prompt optimization techniques. One primary issue is the absence of an effective method to evaluate prompts during inference when the golden answer is unavailable. Concurrently, learning via interactions with the LLMs to navigate the expansive natural language prompting space proves to be resource-intensive.

> To address this, we introduce Prompt-OIRL, which harnesses offline inverse reinforcement learning to draw insights from offline prompting demonstration data. Such data exists as by-products when diverse prompts are benchmarked on open-accessible datasets. With Prompt-OIRL, the query-dependent prompt optimization objective is achieved by first learning an offline reward model. This model can evaluate any query-prompt pairs without accessing LLMs. Subsequently, a best-of-N strategy is deployed to recommend the optimal prompt. Our experimental evaluations across various LLM scales and arithmetic reasoning datasets underscore both the efficacy and economic viability of the proposed approach.

### Cite Our Paper or Code

```
@article{sun2023offline,
  title={Offline Prompt Evaluation and Optimization with Inverse Reinforcement Learning},
  author={Sun, Hao},
  journal={arXiv preprint arXiv:2309.06553},
  year={2023}
}
