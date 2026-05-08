# DL-Spring-2026-Pixels-to-Predictions-DL-Vision-Challenge
This repository contains one notebook, including training, validation, and inference pipelines for fine-tuning `HuggingFaceTB/SmolVLM-500M-Instruct` with LoRA.

## Files:
- `0501_first_fixed.ipynb`: notebook for training, validation, and inference pipeline

## Important Note:
- For the notebook, please run the "first block" first to install the required package and restart the notebook before executing the whole notebook.
- Some intermediate cells may contain outputs from experimental trials or testing steps. The final notebook is provided to demonstrate the complete training, validation, and inference pipeline.
- The notebook is provided to demonstrate the full training, validation, and inference pipeline.
- The notebook loads the base model `HuggingFaceTB/SmolVLM-500M-Instruct` with `from_pretrained`. If executed in a fully offline environment, this checkpoint must already be cached or available locally before attaching the saved LoRA adapter weights from the attached google drive link.

## How to Reproduce:
- This competition applied the training, validation, images, and testing dataset from Kaggle competition: Pixels to Predictions: DL Vision Challenge, please download these files and the file from the model weights below before executing the pipelines.
1. Clone the repository
2. Environment: Open the .ipynb file and execute the first code block to install all dependencies.
3. Data: Download all of the datasets from the Kaggle competition `DL Spring 2026 – Pixels to Predictions: DL Vision Challenge`.
4. Install the required package mentioned in Important Notes and run the training pipeline for training model, validation pipeline for validation, and inference pipeline for generating the submission file in the notebook.

## Model Weights
- The link is my model weights.
https://drive.google.com/drive/folders/1x_vcX9UIxlH7M5Fwdb8b6RshV397nCZO?usp=drive_link
