# Awesome-Agentic-LLM


## Benchmarking
- (*arXiv:2412*) StructTest: Benchmarking LLMs’ Reasoning through Compositional Structured Outputs [[paper](https://arxiv.org/html/2412.18011v1 )]


## Considerations
- (*arXiv:2412*) Practical Considerations for Agentic LLM Systems [[paper](https://arxiv.org/pdf/2412.04093)]
- (*arXiv:2502*) Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research [[paper](https://arxiv.org/abs/2502.04644)]
- (*ICLR'25*) Automated Design of Agentic Systems [[paper](https://arxiv.org/pdf/2408.08435)]
- (*ICLR'25*) AFlow: Automating Agentic Workflow Generation [[paper](https://arxiv.org/abs/2410.10762)]

## Strutured Outputs
- (*arXiv:2408*) Let Me Speak Freely? A Study on the Impact of Format Restrictions on Performance of Large Language Models [[paper](https://arxiv.org/abs/2408.02442)] ] [[comment 2](https://dylancastillo.co/posts/say-what-you-mean-sometimes.html)]
    - Say What You Mean: A Response to 'Let Me Speak Freely' [[website](https://blog.dottxt.co/say-what-you-mean.html)]
    - Structured outputs can hurt the performance of LLMs [[website](https://dylancastillo.co/posts/say-what-you-mean-sometimes.html)]
- (*website*) Bad Schemas could break your LLM Structured Outputs - Instructor [[website]( https://python.useinstructor.com/blog/2024/09/26/bad-schemas-could-break-your-llm-structured-outputs/#try-instructor-today)]

    $\to$ we should add `reasoning_stesp` field [[video](https://www.youtube.com/watch?v=_69dZuBVha4)]

## Tools/Libraries
- [outlines](https://github.com/dottxt-ai/outlines) 🗒️ Make LLMs speak the language of every application.  (from .txt Team)

## Tutorials
### Tool Calling
Tool calling is basically generating input arguments for your function using LLM. You give context of function(tool) to the LLM, it will generate the input arguments as a response. And you are the one calling the function with those input arguments. [[ref](https://www.reddit.com/r/LocalLLaMA/comments/1fvdtqk/comment/lq9a0gj/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)] [[ref](https://docs.langchain4j.dev/tutorials/tools/)]