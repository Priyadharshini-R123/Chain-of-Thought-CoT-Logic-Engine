# Chain-of-Thought (CoT) Logic Engine

## Project Overview

The Chain-of-Thought (CoT) Logic Engine is a Prompt Engineering project designed to improve the reasoning capabilities of Large Language Models (LLMs) by enforcing structured, step-by-step problem solving.

This project focuses on reducing hallucinations, improving logical reasoning, and enabling self-correction mechanisms through carefully engineered prompts.

Developed as part of the Industrial Training Kit - Prompt Engineering Project 2.

---

## Objective

The primary goal of this project is to:

- Force AI models to perform step-by-step reasoning.
- Reduce hallucinations and incorrect outputs.
- Implement self-review and self-correction mechanisms.
- Improve performance on logical and multi-step reasoning tasks.
- Evaluate reasoning accuracy using benchmark logic problems.

---

## Features

### Normal Prompting
Standard question-answer interaction without structured reasoning.

### Chain-of-Thought Prompting
Guides the model to:

1. Understand the problem.
2. Break it into smaller parts.
3. Solve each part.
4. Verify the reasoning.
5. Produce the final answer.

### Self-Correction Engine
After generating an answer, the model:

- Reviews its own reasoning.
- Identifies mistakes.
- Corrects incorrect steps.
- Produces a verified final answer.

### Hallucination Detection
Analyzes generated responses to identify unsupported claims or reasoning errors.

### Performance Evaluation
Compares:

- Normal Prompting
- Chain-of-Thought Prompting
- Self-Corrected Reasoning

using logical benchmark questions.

---

## Technologies Used

- Python
- Jupyter Notebook
- Google Gemini API
- Pandas
- Matplotlib

---

## Project Structure
