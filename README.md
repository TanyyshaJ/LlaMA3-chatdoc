# Fine-Tuning LLaMA3 on Medical Dataset

This repository contains code for fine-tuning LLaMA3, a language model, on a medical dataset using LoRA (Low Rank Adaption of LLM's).

## Files

- **Fine-Tuning Notebook**: 
  - This notebook details the process of fine-tuning LLaMA3 on a specific medical dataset.

- **Merging Adapter Notebook**: 
  - This notebook outlines the process of merging the adapter layer with the base LLaMA3 model. *Note: This part is a work in progress and not yet completed.*

## Objective

The main objective of this project is to adapt LLaMA3 to better understand and generate medical text based on a specialized dataset. The fine-tuning process involves leveraging the capabilities of LoRA to enhance the model's performance in medical domain tasks.

## Future Scope

- **Local Deployment**: Enable the fine-tuned model to run locally for practical applications.
- **Performance Evaluation**: Conduct thorough evaluation of the fine-tuned model's performance metrics.
- **Model Expansion**: Explore opportunities to expand the fine-tuning to other related datasets for broader applicability.

## Technologies Used

- **LoRA**: Large Rotation Adapter for adapting LLaMA3.
- **Python Libraries**: Including PyTorch, Transformers, and others for deep learning tasks.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fine-tuning-llama3-medical.git
   ```

2. Open and run the notebooks in a Jupyter environment or your preferred Python IDE.

3. Follow the instructions within the notebooks to execute fine-tuning and merging processes.

## Contributions

Contributions are welcome! If you have any suggestions, improvements, or issues, please create a pull request or raise an issue in the repository.

