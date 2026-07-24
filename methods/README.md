# Methods

The **Methods** directory contains reusable reasoning frameworks that define **how an AI should think**, analyze, and solve problems.

Unlike **skills**, which provide domain knowledge (e.g., React, Linux, Cybersecurity), methods are model-agnostic thinking strategies that can be applied to any task regardless of the topic or AI model.

The goal of this folder is to improve reasoning quality, encourage structured thinking, reduce hallucinations, and produce more reliable, explainable, and consistent outputs.

## What belongs here?

Examples of methods include:

- The Council

## Method Structure

Each method should ideally contain:

```text
method-name/
├── Overview of the method
├── Instructions for the AI
├── Example inputs and outputs
├── Known weaknesses
└── Papers, articles, or inspirations
```

## Principles

Every method should be:

- Reusable
- AI-agnostic
- Modular
- Explainable
- Composable with other methods
- Focused on reasoning rather than knowledge

> **Skills** tell the AI *what it knows*.
>
> **Methods** tell the AI *how it thinks*.
