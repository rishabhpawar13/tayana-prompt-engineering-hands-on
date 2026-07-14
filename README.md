# tayana-prompt-engineering-hands-on

Exercise 1: Identify the Prompt Technique

Answer: Zero-Shot Prompting
Justification: The prompt directly asks the AI to perform a task (summarize a paragraph) without providing any examples of how the output should look.

Exercise 2: Prompt Recognition
Answer: One-Shot Prompting
Justification: The prompt provides exactly one example of a question-and-answer pair to guide the AI's response before asking the actual question.

Exercise 3: Choose the Correct Technique
Answer: Few-Shot Prompting
Justification: Providing multiple examples (few-shot) allows the AI to learn and mirror a complex pattern, ensuring it mimics the exact writing style consistently across different outputs.

Exercise 4: One-Shot Prompt Creation
Answer (Sample Prompt):
Example:
Complaint: "My order arrived late and the box was damaged!"
Response: "Dear valued customer, we sincerely apologize for the delay and the condition of your package. We have processed a replacement immediately to make this right."

New Task:
Complaint: "The app keeps crashing every time I try to log in."
Response:

Exercise 5 & 6: Rewrite & Concept Trap
Exercise 6: True or False
Answer: False
Justification: Few-shot prompting is actually used for complex, nuanced, or unfamiliar tasks where the AI needs multiple examples to understand a specific format, tone, or rule system. Simple, well-known tasks only require Zero-Shot prompting.

Exercise 5 (Instruction variant): Rewrite Using Correct Technique
Answer (One-Shot Rewrite):
Example:
Casual: "Tell me what happened."
Professional: "Could you please provide an update on the current status of the situation?"

New Task:
Casual: "Send this now."
Professional:

Exercise 7: Prompt Comparison
Answer: Prompt B will give a much better output.
Explanation: Prompt B provides clear constraints (3 sentences), specifies the target audience (young professionals), and details the context (budgeting app). Prompt A is too vague, which will result in a generic response that might not fit the intended goal.

Exercise 8: Technique Selection (Tricky)
Answer: Few-Shot Prompting
Reasoning: To consistently replicate a distinct writing style across multiple outputs, the AI needs to analyze a pattern. Providing 3 to 5 diverse examples (Few-Shot) gives the AI enough context to grasp the nuances of the tone, vocabulary, and sentence structures you want.

Exercise 9: Bonus Challenge (Fill in the blanks)
Simple task, no examples -> Zero-Shot prompting
One example to guide style -> One-Shot prompting
Multiple examples to train pattern -> Few-Shot prompting
