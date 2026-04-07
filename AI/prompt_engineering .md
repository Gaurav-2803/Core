# Google Prompting Essentials: Cheat Sheet

## 1. The Core Framework (T-C-R-E-I)

**Mnemonic:** _Tiny Crabs Ride Enormous Iguanas_.

1.  **Task**: Define the core action and the **Persona** (role) you want the AI to embody (e.g., "Act as an anime expert").
2.  **Context**: Provide specific background details (e.g., recipient's age, specific interests) to narrow the scope.
3.  **References**: Provide examples, past work, or specific formats to clarify your expectations.
4.  **Evaluate**: Review the output against your requirements.
5.  **Iterate**: Refine the prompt based on the evaluation; adopt the "Always Be Iterating" (ABI) mindset.

---

## 2. Iteration Strategies

**Mnemonic:** _Ramen Saves Tragic Idiots_.

- **Revisit the Framework**: Go back and add more context, a persona, or better references.
- **Separate into Sentences**: Break "word vomit" into shorter, simpler instructions to avoid overwhelming the model.
- **Try Analogies**: If a task yields "boring" results, switch to an **analogous task** (e.g., instead of a "marketing plan," ask for a "compelling story").
- **Introduce Constraints**: Narrow the focus by adding specific rules (e.g., specific tempo for music, region-specific results, or word counts).

---

## 3. Advanced Techniques

### **Prompt Chaining**

A series of interconnected prompts where the output of one serves as the input or layer for the next to handle complex workflows.

### **Reasoning Methods**

- **Chain of Thought (CoT)**: Force the AI to "explain your reasoning as a step-by-step process." Helpful for identifying logic errors.
- **Tree of Thought (ToT)**: Ask the AI to explore multiple reasoning paths ("branches") simultaneously. Useful for abstract or complex creative tasks.
- **Combined**: Ask the AI to provide three different options and explain the reasoning for each.

### **Meta Prompting**

Using the AI itself to write, improve, or optimize prompts for you.

### **Multimodal Prompting**

Using various inputs/outputs beyond text, including **images, audio, video, and code**. Ensure you specify context for the non-textual references provided.

---

## 4. AI Agents

An AI agent is an "expert" designed to simulate specific interactions or provide feedback.

- **Agent SIM (Simulation)**: Used for role-playing scenarios like interview practice or coding simulators.
- **Agent X (Expert Feedback)**: Acts as a personalized tutor or consultant (e.g., a VP of Advertising) to critique your work.

### **5-Step Agent Design**

1.  **Assign Persona**: Define the expert role.
2.  **Detail Context**: Describe the scenario and conversation goal.
3.  **Specify Interaction**: Define the rules of the conversation.
4.  **Set a Stop Phrase**: A specific phrase to end the session (e.g., "No pain, no gain").
5.  **Request Feedback**: Ask the agent to summarize areas for improvement at the end.

---

## 5. Limitations & Safety

- **Hallucinations**: The model may provide inconsistent or nonsensical facts (e.g., miscounting letters in a word).
- **Biases**: Training data may contain human biases regarding gender and race.
- **Mitigation**: Always use a **"Human in the Loop"** approach. You are responsible for verifying the accuracy of every output.
- **Data Privacy**: Avoid inputting sensitive or proprietary data into public models.
