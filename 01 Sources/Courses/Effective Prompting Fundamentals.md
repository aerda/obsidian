---
type: source-note
source_type: video-transcript
title: Effective Prompting Fundamentals
language_original: Spanish transcript with some English sections
language_note: Translated and cleaned into English
created: 2026-06-26
status: processed
topics:
  - prompt engineering
  - AI assistants
  - AI communication
tags:
  - ai/prompting
  - source/course
links:
  - "[[AI Learning MOC]]"
  - "[[Prompt Engineering]]"
  - "[[AI Assistants]]"
---

# Effective Prompting Fundamentals

## Assessment

[Certain] This material is worth saving as a source note because it gives a practical framework for prompting AI assistants.

[Probable] It should not become one large permanent note. Its value is in several reusable principles: context, examples, constraints, decomposition, thinking before answering, role prompting, and iteration.

[Assumption] The original course used Claude as the main example, but most principles apply to other AI assistants.

## Cleaned Summary

Effective prompting is the practice of giving AI systems clear instructions so they can understand the task, the context, the desired output, and the preferred interaction style.

The transcript frames prompting as an extension of clear communication. Many principles that help in human communication also help with AI: clarity, relevant context, concrete examples, and explicit expectations. However, AI systems often require more explicit instruction than humans because they may not infer unstated goals, audience, format, or constraints.

The transcript presents six core prompting principles:

1. Give context.
2. Show examples of what good output looks like.
3. Specify output constraints.
4. Break complex tasks into steps.
5. Ask the AI to think before answering when useful.
6. Define the AI's role, style, or tone.

It also adds a practical "secret weapon": ask the AI to help improve the prompt when the user is unsure how to ask.

## Key Ideas From The Source

### Give Context

A vague prompt such as "Tell me about climate change" leaves the AI guessing about scope, audience, depth, geography, and purpose.

A better prompt gives context:

> Explain three major impacts of climate change on agriculture in tropical regions, with examples from the last decade. I am preparing for a job interview at an agricultural research lab in Indonesia. I have a PhD in ecology but no specific background in climate change. Write a summary of key concepts that would help me speak intelligently in the interview.

The added context tells the AI what the user wants, why they want it, how they will use it, and what level of background knowledge they already have.

### Show Examples

Examples are useful when the desired style or pattern is easier to demonstrate than explain.

This is related to [[Few-shot Prompting]], where the user gives one or more examples for the AI to imitate.

### Specify Constraints

Output constraints include format, length, language, sections, tone, code language, visual style, or design requirements.

Clear constraints reduce the chance that the AI produces an answer that is technically correct but practically unusable.

### Break Complex Tasks Into Steps

For complex tasks, the user can guide the AI through the desired process. This is especially useful when there are many valid ways to complete the task or when the user has domain-specific expectations.

### Ask The AI To Think First

For some tasks, it helps to ask the AI to consider factors, constraints, and approaches before recommending a solution. The transcript notes that newer reasoning models may already do some of this by default.

Important distinction: the thinking process should happen before the final answer, not merely as an explanation after the answer.

### Define Role, Style, Or Tone

Specifying the role or perspective changes the output. Examples:

- "Explain rainbows as an experienced science teacher speaking to a bright 10-year-old."
- "As a UX design expert, review this wireframe and suggest three improvements focused on navigation and accessibility."

Role prompting is useful for brainstorming, review, explanation, and domain-specific feedback.

### Improve Prompts Iteratively

Prompting is experimental. If an answer is not useful, refine the prompt by adding context, examples, constraints, decomposition, or a different role.

The transcript recommends asking for variations, requesting different formats, checking confidence, and sometimes starting a fresh conversation when the current one has drifted.

## Suggested Permanent Notes

- [[Effective prompts reduce ambiguity with context]]
- [[Examples teach AI systems the desired output pattern]]
- [[Output constraints define what success looks like]]
- [[Complex AI tasks improve when decomposed into steps]]
- [[AI role prompting shapes perspective style and expertise]]
- [[Prompting is an iterative feedback loop]]

## Suggested Glossary Notes

- [[Prompt Engineering]]
- [[Few-shot Prompting]]
- [[Context Window]]
- [[AI Assistants]]

## Warnings

[Certain] The transcript uses "prompt engineering" in a practical, non-technical way. Do not overcomplicate this note with advanced prompt-engineering jargon unless a later source justifies it.

[Probable] Some advice, especially around asking models to "think first," changes depending on the model. Reasoning models and non-reasoning chat models may respond differently.

[Probable] This source is better as a foundation for practical use than as a rigorous technical explanation of how language models work.

## Follow-up Questions

- [[How should I evaluate whether an AI response is good enough]]
- [[Which prompt patterns remain useful as models improve]]
- How should I adapt prompts differently for Claude, ChatGPT, Gemini, or local models?
- When should I start a new conversation instead of continuing an existing AI chat?

