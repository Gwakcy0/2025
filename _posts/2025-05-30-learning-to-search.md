---
layout: distill

# title: Learning to Search: fine-tuning LLMs to decide with reasonable flows
# description: We all know chain-of-thought reasoning improves language model's performance.
#   But how do we fine-tune the model to do the chian-of-thought reasoning, given only the question and answer pairs?
#   Since there are infinite possible ways of reasoning, it is intractable to sample every combinations of tokens to evaluate.
#   Here, we provide one solution proposed in "Amortizing intractable inference in large language models".

# Optional titles
# Amortized Reasoning: Fine-tuning LLMs for Intractable Chain-of-Thought Inference
# Fine-tuning LLMs for Reasoning: From Token Predictions to Latent Search with GFlowNets

title: Learning to Search: Amortized Inference for Latent Reasoning in LLMs
description: Chain-of-thought (CoT) reasoning is known to improve LLM performance on complex tasks.
  But how do we fine-tune a language model to generate such reasoning chains, given only question–answer pairs — and no reasoning annotations?
  This challenge is fundamentally a problem of intractable inference: the reasoning path is a latent variable, and there are exponentially many possible paths.
  In this blogpost, we explore a principled solution proposed in "Amortizing Intractable Inference in Large Language Models": using Generative Flow Networks (GFlowNets) to amortize posterior sampling over latent reasoning sequences.
  This approach enables diverse and data-efficient fine-tuning of LLMs — from story infilling to multi-step arithmetic — by treating training as a form of learned search.

date: 2025-05-30
future: true
htmlwidgets: true
hidden: false

# Anonymize when submitting
authors:
  - name: Anonymous

# authors:
#   - name: 
#     url: "https://"
#     affiliations:
#       name: 


# must be the exact same name as your blogpost
bibliography: 2025-05-30-learning-to-search.bib  

# Add a table of contents to your post.
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly. 
#   - please use this format rather than manually creating a markdown table of contents.
toc:
  - name: Why Reasoning is Inference
  - name: A Toy Case: Sampling Uniform Numbers
  - name: GFlowNets: Learning to Sample
  - name: Fine-Tuning CoT via Amortized Inference
  - name: Inference over Knowledge: Story Infilling
  - name: What We Learned (and Didn’t)
  - name: Broader Impact & Future Directions



---

## Why Reasoning is Inference

## A Toy Case: Sampling Uniform Numbers

## GFlowNets: Learning to Sample

## Fine-Tuning CoT via Amortized Inference

## Inference over Knowledge: Story Infilling

## What We Learned (and Didn't)

## Broader Impact & Future Directions

### Reference
Broader Impact & Future Directions

<d-cite key="hu2024amortizingintractableinferencelarge"></d-cite>
<d-cite key="bengio2023gflownetfoundations"></d-cite>
<d-cite key="niu2024gflownettrainingpolicygradients"></d-cite>

pmlr-v202-hu23c
NEURIPS2024_2fb57276
malik2023batchgfngenerativeflownetworks