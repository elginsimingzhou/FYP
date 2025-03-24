# UrbanLLM: Fine-Tuning Llama-3.1-8B to improve spatial knowledge understanding using POI information data

## Overview  
UrbanLLM is a fine-tuned large language model designed for solving complex urban planning queries with spatial understanding of POI locations. The project enhances LLMs' capability in spatial reasoning and location-based query responses by leveraging fine-tuning techniques on high-quality POI information datasets.  

## Repository Structure  

This repository contains two primary Jupyter notebooks:  

- **`FYP_Submission_Dataset_Generation.ipynb`**:  
  - Generates a structured dataset containing POI locations and information (ie restaurants, banks & hospitals).  
  - Uses APIs (such as Overpass and Yelp Fusion) to collect real-world urban data.  
  - Processes and cleans the dataset for fine-tuning UrbanLLM.  

- **`FYP_Submission_POI_Finetuning_and_Evaluation.ipynb`**:  
  - Fine-tunes the base Llama-3.1-8B model on the generated dataset using Low-Rank Adaptation (LoRA) and 4-bit quantization for efficiency.  
  - Evaluates model performance against baseline LLMs (e.g., GPT-3.5, GPT-4o, Llama-2, Llama-3) on POI queries.  

## Key Features  

- **Custom Dataset Generation**: Extracts relevant urban data from external data sources to train UrbanLLM.  
- **LoRA Fine-Tuning**: Optimizes performance while reducing computational costs.  
- **4-Bit Quantization**: Improves memory efficiency for deployment on resource-constrained environments.  
- **Evaluation Against SOTA Models**: Benchmarks UrbanLLM against existing LLMs to demonstrate its effectiveness in spatial context understanding.  

## Installation  

To run the notebooks, download the notebooks and run the cells in order / sections you want.
