## **Principle 1**
Write clear and specific instructions. Clear =! short\
 Tactic 1: Use delimiters - Triple quotes, Triple backticks, Triple dashes, Angle Brackets, XML tags\
 Tactic 2: Ask for structured output - JSON, HTML\
 Tactic 3: Ask the model to check whether conditions are satisfied\
 Tactic 4: Few-shot prompting: Give successful examples of completing tasks. Then ask model to perform the task


## **Principle 2**
Give the model time to think\
 Tactic 1: Specify the steps required to complete a task or Ask for output in a specified format.\
 Tactic 2: Instruct the model to work out its own solution before rushing to a conclusion.\
 Tactic 3: Be aware of Model Limitations: Hallucinations\
           Hallucinations make statements that sound plausible but are not true.\
           Reducing Hallucinations: First find relevant information, then answer the question based on the relevant information.


## **Iterative Prompt Development**
1. Idea
2. Implementation (code/data) -> Prompts
3. Experimental Result
4. Error Analysis

### **Prompt Guidelines**
1. Be clear and specific
2. Analyze why result does not give desired output.
3. Refine the idea and the prompt
4. Repeat
