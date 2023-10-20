# Collaboration Mechanisms for LLM Agents
[Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View](https://arxiv.org/abs/2310.02124)demonstrates that agents utilizing LLM (Large Language Models) can enhance their accuracy in addressing problems through cooperation. In this paper, cooperation is divided into two patterns, namely "debate" and "reflection," and it conducts examinations for a total of eight patterns, including sequences like "debate -> reflect -> debate."

This repository experiment:
- employed the model, llama2 (GPT-3.5-turbo was also used for comparison).
- tested the most effective cooperation pattern as indicated in the paper, which is "debate -> debate -> reflect."
- focused on ten problems randomly sampled from LLMU (Large Language Model Utilization) data. Due to the small sample size, results may vary depending on factors such as problem difficulty.

## result (score by GPT-4):
|      |  result  |
| ---- | ---- |
|  llama2 collaboration  | 83% (25/30)    |
|  llama2 oneshot  | 57% (17/30)    |
|  gpt3.5 oneshot  | 95% (28.5/30)    |


## execution environment
local mac(M2)

## models
- llama2: https://huggingface.co/elyza/ELYZA-japanese-Llama-2-7b-instruct
- gpt3.5-turbo

## reference
- code: [zjunlp/MachineSoM](https://github.com/zjunlp/MachineSoM)
