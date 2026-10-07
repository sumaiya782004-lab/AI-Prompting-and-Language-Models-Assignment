# AI Prompting and Language Models - Practical Assignment

## 1. Introduction

This project explores basic concepts related to AI language models and practical prompt engineering.

The main topics covered are:

* Tokens
* Context windows
* Inference
* Hallucinations
* Prompting
* RAG
* Fine-tuning
* Prompt comparison
* Correctness and instruction-following

---

## 2. Important Concepts

### Tokens

Tokens are small pieces of text processed by a language model. A token can be a complete word, part of a word, or punctuation.

Tokens are important because language models have limits based on the number of tokens they can process.

### Context Window

A context window is the amount of information a language model can consider at one time.

For example, when a user provides a document and asks questions about it, the model uses the available context to understand and answer the question.

### Inference

Inference is the process of using a trained AI model to generate an output.

For example, when a user gives ChatGPT a prompt and receives an answer, the model is performing inference.

### Hallucinations

A hallucination occurs when an AI model generates information that may sound correct but is actually incorrect or unsupported by the given information.

AI-generated answers should therefore be checked, especially for important information.

---

## 3. Prompt Types

### Summarization

A prompt can ask an AI model to summarize a long piece of text into a shorter version.

### Extraction

An extraction prompt asks the model to identify specific information from a given text.

### Classification

A classification prompt asks the model to place information into a particular category.

### Question Answering

A question-answering prompt asks the model to provide an answer based on supplied information.

---

## 4. Prompting vs RAG vs Fine-tuning

### Prompting

Prompting means giving instructions to an AI model to control the type and format of its response.

### RAG

RAG stands for Retrieval-Augmented Generation. It allows an AI system to retrieve relevant information from an external knowledge source before generating an answer.

### Fine-tuning

Fine-tuning means additional training of an existing model using a specific dataset so that it performs better for a particular task or behavior.

### Simple Comparison

| Technique   | Main Purpose                                 |
| ----------- | -------------------------------------------- |
| Prompting   | Give instructions to the model               |
| RAG         | Give the model relevant external information |
| Fine-tuning | Adapt the model through additional training  |

---

## 5. Conclusion

This assignment demonstrates how prompt design can influence AI-generated responses. It also highlights the importance of checking correctness and instruction-following when working with language models.

