# llm-radicalization-archetypes
Examines how LLMAs respond to advice seeking questions for vulnerable young men

# LLM Archetypes and Online Radicalization

This project explores how large language models respond to advice seeking
questions when conditioned on different identity archetypes that are
theoretically susceptible to online radicalization and grievance-based
online narratives.

Rather than attempting to detect extremist content directly, this work
focuses on a more upstream question: how identity cues, perceived social
marginalization, and emotional framing shape the advice and narratives
produced by AI systems in sensitive sociopolitical contexts.

The motivation is twofold. First, online radicalization rarely begins with
explicit extremism; it often emerges through feelings of alienation,
resentment, or perceived loss of status. Second, as large language models
increasingly mediate advice, meaning-making, and emotional validation,
understanding how they respond to vulnerable identity configurations
becomes a critical sociotechnical concern.

## Research Questions

-> How do LLM responses vary when the same advice-seeking question is asked
  from different identity positions (e.g., gender, geography, social role)?
-> Do certain archetypes elicit narratives that reinforce grievance,
  fatalism, or oppositional framing?
-> What implications do these patterns have for AI-mediated sensemaking
  and the early stages of radicalization pathways?

## Methodology

This project uses a prompt-based experimental design:

-> Identity archetypes are constructed using combinations of demographic,
  geographic, and social-context cues.
-> Each archetype is presented with the same advice-seeking questions
  related to alienation, frustration, and social belonging.
-> Model responses are collected and analyzed qualitatively to identify
  recurring themes, narrative structures, and affective tone.

The notebook documents the full pipeline, including prompt construction,
model querying, and exploratory analysis of response patterns.

## Contents

- `main.ipynb`-  Jupyter notebook containing prompt design, data collection,
  and analysis
- `main.html`- Rendered, read-only HTML version of the notebook for
  accessibility

## Tools and Technologies

Python · Jupyter Notebook · Large Language Models LLAMA via huggingface (API-based)

## Notes

This project is exploratory and interpretive by design. It is intended
as a foundation for future work incorporating behavioral data, larger
prompt samples, and collaboration with platforms that can observe
real-world interaction dynamics.
