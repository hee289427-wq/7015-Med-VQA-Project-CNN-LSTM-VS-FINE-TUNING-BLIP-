# 7015-Med-VQA-Project-CNN-LSTM-VS-FINE-TUNING-BLIP-
# Medical Visual Question Answering (Med-VQA)
#Creator: HE CHENZHEN(24205431) & WANG SHENGYONG(24080261)

This repository contains the code for a course project on Medical Visual Question Answering using the VQA-RAD dataset.

## Project Structure
- `preliminary_project.ipynb`: CNN baseline(image only) model and Zero-shot BLIP model
- `BLIP_FINAL_PROJECT.ipynb`: fine-tuning BLIP model
- `CNN_LSTM_FINAL_PROJECT.ipynb`: CNN + LSTM model
- `processed`: The processed/ folder contains all preprocessed data splits derived from the VQA-RAD dataset and is used across both preliminary and final experiments. The dataset is split into training, validation, and test sets using a fixed 7:1:2 ratio to ensure reproducibility. For CNN-based models, filtered versions (*_filtered.json) are provided, retaining only the Top-K most frequent answers to enable closed-set classification. For BLIP-based experiments, the same splits are also exported in tabular format (*_blip.xlsx) for zero-shot and fine-tuning evaluation. All files reference images stored in the original VQA_RAD Image Folder.

## Dataset
The experiments are conducted on the VQA-RAD dataset. Due to the file upload restrictions, the dataset is not included in this repository. You can visit and dowanload VQA-RAD dataset from this link https://huggingface.co/datasets/flaviagiammarino/vqa-rad

## Requirements
The code is implemented in Python and uses PyTorch and HuggingFace Transformers.  
All experiments were run on Google Colab.

## Notes
This repository is for academic and educational purposes only.

