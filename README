# Text-to-SQL

This project is a text-to-SQL conversion tool that aims to convert natural language queries into SQL queries.

## Overview

The system is built on the `Code Llama` Large Language Model (LLM) with 7B parameters, fine-tuned for text-to-SQL generation using the `SQL Create Context` dataset. The dataset, which extends from the foundations of WikiSQL and Spider datasets, comprises 78,577 instances of natural language queries, SQL CREATE TABLE statements, and SQL queries. 

The system is integrated with a PostgreSQL database, allowing the model to execute SQL queries directly on the database. A user-friendly front end developed using HTML and CSS serves as the interface between the user and the Language Model.

## Usage

To use this tool, follow these steps:

1. Load the `Text-to-SQL.ipynb` notebook in a platform like Kaggle.
2. Make sure you have access to a GPU, such as the P100, for faster processing.
3. Run the notebook to execute the code and test the project.


## Fine-Tuning Process

The fine-tuning process is a crucial part of this project. The Code Llama Large Language Model (LLM) was fine-tuned specifically for the task of text-to-SQL generation. 

The code used for this fine-tuning process is available in the `fine-tuning` folder of this repository. It is provided as a Jupyter notebook, which can be run in environments like Kaggle.

The fine-tuning was performed using two T4 GPUs, each with 15 GB of memory. The training process took approximately 10 to 11 hours to complete. 

To replicate the fine-tuning process, follow these steps:

1. Load the `CodeLlama_finetuning.ipynb` notebook from the `fine-tuning` folder in a platform like Kaggle.
2. Ensure you have access to sufficient GPU resources, similar to the two T4 GPUs used in this project.
3. Run the notebook to start the fine-tuning process.

Note: The fine-tuning process is resource-intensive and time-consuming. Ensure you have sufficient resources and time before starting the process.

