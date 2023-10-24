# Prompt-Engineering
Notes of ChatGPT Prompt Engineering for Developers - Deep Learning AI Course in Collaboration with OpenAI

## Types of LLMs:
1. Base LLMs
2. Instruction Tuned LLMs

### Base LLMs:
- Predicts next word, based on textual training data
- Trained on Large amounts of data available on the internet

### Instruction Tuned LLMs:
- It is fine-tuned on Base LLMs with instruction data and how to follow those instructions.
- And they are often further refined using RLHF i.e. Reinforcement Learning with Human Feedback.
- They are trained to sound Friendly, Helpful, and Honest compared to Base LLMs.

## Principles of Prompting:
1. Write clear and Specific Instructions
2. Give the model time to think

### Write clear and Specific Instructions
1. Writing clear instructions does not mean instructions should be short.
2. Tactic 1: Use delimiters
   - Triple Quotes: """
   - Triple Backticks: ```
   - Triple Dashes: ---
   - Angle Brackets: <>
   - XML Tags: <tag></tag>
3. Tactic 2: Ask for structured output
   - HTML, JSON
4. Tactic 3: Check if conditions are satisfied
   Check if assumptions are required to do the task
5. Tactic 4: Few-shot prompting
   Give successful examples of similar computing tasks
   Then ask the model to perform the task

### Give the model time to think
1. Tactic 1: Specify the steps to complete the task. (break down if the problem is large)
2. Tactic 2: Instruct the model to work out its own solution before rushing to a conclusion.

## Model Limitation
1. Hallucination: Makes statements that sound plausible but are not true.
   Though models are exposed to vast amounts of data while training, models have not yet memorized everything. Model is not aware of the boundaries due to which models also tend to answer topics which it is not aware of yet the answers sound so appealing. These fabricated ideas are called Hallucinations.
2. Reducing Hallucinations: We should first ask the model to first find relevant information, from a relevant source and then answer the questions.





