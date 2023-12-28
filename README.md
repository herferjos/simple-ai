# 👾 Prompty
🔥 Create AI-systems easily 🔥

With Prompty you can create and test any single prompt instruction/technique, agent or training a custom LLM. Our goal is to achieve LLMs abstractions to make easy to use and, at the same time, fully customizable so that AI developers can reuse code from any level of abstraction.

## Index

LLMs can be used with simple instructions, with composable instructions for complex processes, aka agents, and also to generate synthetic data with which to train a custom LLM.

- Prompts
- Agents
- Data
- Training

### Prompts

Prompts are a set of instructions to get a desirable output from a specific LLM. Simple-AI define prompts with an unique set of features:

- Expected task to be done
- LLM properties to works properly
- Testing examples

Also, there are certain prompt techniques to enhace LLM perfomance and to set during prompt creation.

### Agents

Agents are specific prompts in a row to perfom a task. They are similar to a traditional AI model in which there are adding layers from input to output.

Use ``layer.prompt()`` to define input and output expected from each layer.

### Training

Training LLM is a difficult task due to computational cost, lack of data and other stuffs related. 

With Simple-AI just set an agent to replicate and boost their perfomance on a small and open-source LLM. Simple-AI create a synthetic data and fine-tune an open-source LLM for you with any actions.
