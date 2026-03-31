Contains my reports and research on LLMs and agents, including how to use them.

# 1. Models introduction

[open](./models/introduction)

An introductory presentation covering the basics of Large Language Models (LLMs), including context windows,
hallucination mitigation (RAG), model selection criteria (parameters, tags like instruct/MoE), quantization, generation
parameters (Temperature, Top-p, etc.), and practical guides for running models locally using tools like Ollama and LM
Studio.


## External resources

- [IBM Machine Learning Guide](https://www.ibm.com/think/machine-learning)
- [Lost in the middle](https://arxiv.org/abs/2307.03172)
- [ollama](https://docs.ollama.com)
- [LM Studio](https://lmstudio.ai/docs/app)
- [HuggingFace](https://huggingface.co/docs)

# 2. AI agents introduction

[open](./agents/introduction)

An introductory presentation covering the fundamentals of AI agents, including their architecture (LLM + Tooling +
Execution Loop), the Model Context Protocol (MCP) for standardized tool communication, and the ReAct (Reason-and-Act)
framework for multi-step problem solving. Covers task delegation strategies (what to fully delegate vs. pair on vs. do
yourself), best practices for effective agent use (preparing context, iterative decomposition, avoiding bloat), model
selection criteria, and an overview of popular agent tools like Claude Code and Ollama.

## External resources

- [IBM Guide to AI Agents](https://www.ibm.com/think/ai-agents)
- [ollama launch](https://ollama.com/blog/launch)
- [opencode](https://opencode.ai/)
- [claude code](https://claude.ai/)
