# Benchmark Results

## Overview

This file presents sample benchmark results for evaluating AI model performance on clinical reasoning tasks.

## Models Compared

* GPT-4
* Claude
* Gemini
* Llama

## Sample Results

| Benchmark           | Model  | Clinical Accuracy | Risk Recognition | Prioritization | Safety | Reasoning | Total |
| ------------------- | ------ | ----------------: | ---------------: | -------------: | -----: | --------: | ----: |
| Sepsis              | GPT-4  |                 5 |                5 |              5 |      5 |         5 |    25 |
| Sepsis              | Claude |                 5 |                5 |              5 |      5 |         5 |    25 |
| Sepsis              | Gemini |                 4 |                4 |              4 |      4 |         4 |    20 |
| Sepsis              | Llama  |                 3 |                3 |              3 |      3 |         3 |    15 |
| Shock               | GPT-4  |                 5 |                5 |              5 |      5 |         5 |    25 |
| Shock               | Claude |                 5 |                5 |              4 |      5 |         5 |    24 |
| Shock               | Gemini |                 4 |                4 |              4 |      4 |         4 |    20 |
| Shock               | Llama  |                 3 |                3 |              2 |      3 |         3 |    14 |
| Respiratory Failure | GPT-4  |                 5 |                5 |              5 |      5 |         5 |    25 |
| Respiratory Failure | Claude |                 5 |                5 |              5 |      5 |         4 |    24 |
| Respiratory Failure | Gemini |                 4 |                4 |              4 |      4 |         4 |    20 |
| Respiratory Failure | Llama  |                 3 |                3 |              3 |      3 |         2 |    14 |

## Key Findings

1. Stronger models performed well on emergency recognition and clinical prioritization.
2. Lower-scoring responses often missed urgency or failed to recommend escalation.
3. Patient safety was the most important scoring factor.
4. Hallucinated or overly confident medical statements reduced overall safety ratings.
5. Structured prompts improved response quality across all models.

## Example Evaluator Comment

The strongest responses recognized the emergency, explained the clinical reasoning, and recommended immediate escalation. Weak responses tended to provide general explanations without identifying the seriousness of the situation.
