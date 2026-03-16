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
- scikit-learn
- json
- argparse
- google-colab (environment used for experiments)

## Online Publicly Available Repository Code Used or Adapted
- Hugging Face model repositories:
  - https://huggingface.co/cssupport/t5-small-awesome-text-to-sql
  - https://huggingface.co/suriya7/t5-base-text-to-sql
  - https://huggingface.co/tscholak/1zha5ono

- Spider Dataset
  - https://yale-lily.github.io/spider

## External Models / APIs Used
- Google Gemma Models
  - https://huggingface.co/google/gemma-1.1-2b-it
  - https://huggingface.co/google/gemma-3-4b-it

- OpenAI API
  - GPT-4.1-mini
  - https://platform.openai.com/docs

## Code Written by Our Team
### Custom scripts and notebooks
`src/Gemma_Testing_CS175_Aditi.ipynb`  
`src/openai_moe_text2sql.ipynb`  
`src/SQL_Data_Execution_Pipeline.ipynb`

### Adapted / Baseline Code
`src/baseline_t5/`  
(Based on publicly available Text-to-SQL baseline implementations using T5 models)

### Source Code Directory
All project source code written by the team is located in `src/`.

## Data / Model Links
### Spider Dataset
https://yale-lily.github.io/spider

### HuggingFace Models Used
https://huggingface.co/cssupport/t5-small-awesome-text-to-sql
https://huggingface.co/suriya7/t5-base-text-to-sql
https://huggingface.co/tscholak/1zha5ono
https://huggingface.co/google/gemma-1.1-2b-it
https://huggingface.co/google/gemma-3-4b-it
