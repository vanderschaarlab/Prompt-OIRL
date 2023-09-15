# Prompt-OIRL
code for paper Offline Prompt Evaluation and Optimization with Inverse Reinforcement Learning
https://arxiv.org/pdf/2309.06553.pdf 

### Abstract 

> The recent advances in the development of Large Language Models (LLMs) like ChatGPT have achieved remarkable performance by leveraging human expertise. Yet, fully eliciting LLMs' potential for complex tasks requires navigating the vast search space of natural language prompts. While prompt engineering has shown promise, the requisite human-crafted prompts in trial-and-error attempts and the associated costs pose significant challenges. Crucially, the efficiency of prompt optimization hinges on the costly procedure of prompt evaluation. This work introduces Prompt-OIRL, an approach rooted in offline inverse reinforcement learning that seeks to bridge the gap between effective prompt evaluation and affordability. Our method draws on offline datasets from expert evaluations, employing Inverse-RL to derive a reward model for offline, query-dependent prompt evaluations. The advantages of Prompt-OIRL are manifold: it predicts prompt performance, is cost-efficient, produces human-readable results, and efficiently navigates the prompt space. We validate our method across four LLMs and three arithmetic datasets, highlighting its potential as a robust and effective tool for offline prompt evaluation and optimization. 
>
> Our code, as well as the offline datasets, will be released, and we highlight the Prompt-OIRL can be reproduced within a few hours using a single laptop using CPU. With our implementation, conducting OIRL for the GSM8k takes 50 minutes on a MacBookAir with M2 chip, and takes only 5 minutes on a server with 16(out of 64)-core AMD 3995WX CPUs.
