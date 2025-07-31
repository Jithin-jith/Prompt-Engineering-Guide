# 🚀 Prompt Engineering Guide

Prompt Engineering is the art and science of crafting inputs (prompts) to effectively guide large language models (LLMs) like GPT, Claude, Gemini, or Mistral to produce desired outputs. This repository serves as a comprehensive guide covering different types of prompting techniques, use cases, and best practices.

---

## 📌 What is Prompt Engineering?

Prompt engineering involves designing and structuring inputs to:
- Solve tasks accurately.
- Maximize the performance of language models.
- Adapt model behavior for custom applications.

It is especially important in natural language applications such as chatbots, summarization tools, Q&A systems, and LLM-powered agents.

---

## 📚 Types of Prompting (Based on Examples)

### 1. 🔹 Zero-shot Prompting
- No examples are provided—just a direct instruction.
- ✅ Best for simple or well-understood tasks.

📌 **Example**:
> Translate this sentence into French: I am happy today.

### 2. One-shot Prompting
One example is given before the actual input.

📌 **Example**:

> Translate this sentence into French:  
> I am tired → Je suis fatigué.  
> Translate this sentence into French: I love programming →

### 3. Few-shot Prompting
A few examples (usually 2–5) are given before the task.

📌 **Example**:

```text
Translate this sentence into French:
- I am hungry → J'ai faim
- She is a teacher → Elle est professeur
- They are going to school → Ils vont à l'école
- I like cats →

# 🔹 Prompting Techniques Based on Strategy

### 4. Chain-of-Thought (CoT) Prompting
Encourages the model to reason step-by-step.

📌 **Example**:
> If Tom has 5 apples and gives 2 to Sarah, how many does he have left?  
> Let’s think step by step.

✅ Improves reasoning tasks like math, logic, and QA.

---

### 5. Self-Consistency Prompting
Uses multiple sampled CoT outputs and selects the most consistent answer.

✅ Increases robustness and accuracy.

---

### 6. Retrieval-Augmented Prompting
Adds external context retrieved from documents or knowledge bases.

✅ Often used in **RAG (Retrieval-Augmented Generation)** systems.

---

### 7. Instruction-based Prompting
Clear instructions are given to the model.

📌 **Example**:
> Summarize the following article in 3 bullet points.

---

### 8. Role Prompting
Sets a role or persona for the model to follow.

📌 **Example**:
> You are a helpful medical assistant. Answer concisely and factually.

---

### 9. Multimodal Prompting
Combines text with images, audio, or other modalities as input.  
Used in models like **GPT-4o**, **Gemini**, and **Claude 3**.

📌 **Example**:
> Describe this image and write a caption suitable for social media.

---
