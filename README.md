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
