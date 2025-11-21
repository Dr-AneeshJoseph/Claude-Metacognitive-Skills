# 🧠 Claude Metacognitive Skill: Frosty

This repository contains a specialized prompt or set of instructions designed to enhance Claude's metacognitive abilities, allowing it to better **plan, monitor, and evaluate** its own reasoning processes for improved output quality and reliability.

## ✨ What Does This Skill Do?

* **[Briefly explain the primary benefit, e.g.,]** It forces Claude to use a three-step internal process (Deconstruct, Solve, Reflect) before providing the final answer.
* **[Explain the outcome, e.g.,]** Reduces hallucination rates by requiring internal error checking.
* **[Mention a specific use case, e.g.,]** Ideal for complex analysis, coding tasks, or multi-step problem-solving.

## 🛠️ How to Implement and Use

Using this skill is as simple as copying the text and prepending it to your regular Claude prompts.

### Step 1: Initialization

Copy the entire metacognitive instruction block (found in `skill-instructions.txt` or similar file) and paste it into the **System Prompt** field or at the very beginning of a new conversation with Claude.

### Step 2: Prompting

Once the instructions are loaded, submit your task.

#### Example Input Prompt:

> "I need a concise summary of the key differences between quantum entanglement and quantum tunneling, written for a high school student."

### Step 3: Observation

Claude will now apply the structured internal reasoning defined by the skill before presenting its final response.

## 📜 Source Code and Instructions

The core metacognitive skill text is located here:

* [`claude-skill.txt`](./claude-skill.txt) - *[Link this to the file containing your actual prompt/skill]*

## ⚖️ License and Attribution

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License**.

### Key License Requirements:

1.  **Attribution:** You must always give appropriate credit to the original developer.
2.  **Non-Commercial:** You may not use this work for commercial purposes.

---

### **Original Developer & Attribution**

This Claude Metacognitive Skill was developed by ** Dr. Aneesh Joseph**.

If you use or adapt this skill, please ensure you clearly attribute the source by including a link back to this repository.

---

## 🤝 Contribution & Feedback

While this skill is shared for free use, it is not currently open for external contributions. However, I welcome feedback and suggestions for improvement! Please open an issue if you encounter unexpected behavior or have ideas for enhancement.