## **MSA Text-to-SQL Final Project**
## **Overview**
This project builds and evaluates a multi-model Text-to-SQL pipeline for translating natural language questions into executable SQL queries. The goal is to compare specialized Text-to-SQL models, general-purpose LLMs, and prompt engineering strategies, then use error analysis to design a mixture-of-experts routing system that improves overall execution accuracy.

All experiments were implemented in Google Colab for reproducibility and ease of evaluation.

The pipeline evaluates multiple models on a subset of the Spider dataset and compares performance using execution accuracy, followed by detailed error categorization and visualization.

## **Pipeline**
The pipeline consists of five main stages:
1. Baseline model evaluation
2. LLM evaluation (Gemma and OpenAI)
3. Prompt engineering experiments
4. Error analysis
5. Mixture-of-experts routing

## **Libraries / Packages Used:**
- Python 3.x
- transformers
- torch
- datasets
- pandas
- numpy
- matplotlib
- seaborn (only if actually used)
- scikit-learn (only if actually used)
- json
- argparse
- google-colab (environment used for experiments)

## Online Publicly Available Repository Code Used or Adapted:
- Hugging Face model repositories:
  - cssupport/t5-small-awesome-text-to-sql
  - suriya7/t5-base-text-to-sql
  - tscholak/1zha5ono
- Spider dataset
- 

## Code That We Wrote:
- src/baseline_t5/
- src/
- src/

## Source Code Directory:
All project source code written by the team is located in src/.

