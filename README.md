# Transformers and Fine-tuning with LLM

This repository contains two main implementations:

## 1. NanoGPT Implementation

A complete implementation of NanoGPT from scratch using PyTorch. The implementation is modular and includes detailed debugging capabilities.

### Features

- Built from scratch using PyTorch
- Modular architecture with clear separation of components
- Comprehensive debugging capabilities
- Trained on Pride and Prejudice for text generation

### Resources

- [Medium Article: Detailed Explanation of the Code](placeholder_for_medium_article)
- [Video Tutorial: Step-by-Step Implementation](placeholder_for_video_explanation)

### Files

- `nanogpt_implementation.ipynb`: Main implementation notebook

### Usage

1. Open `nanogpt_implementation.ipynb` in Google Colab
2. Run all cells in order
3. The notebook will:
   - Download the dataset
   - Train the model
   - Generate text samples

## 2. Textbooks Are All You Need - Case Study

An implementation of the "Textbooks Are All You Need" paper's approach using alternative datasets.

### Features

- Uses three high-quality datasets:
  - CodeParrot for main code corpus
  - Python documentation for textbook content
  - LeetCode problems for exercises
- Follows the paper's three-stage training process
- Includes quality filtering using CodeBERT

### Files

- `textbook_study.ipynb`: Main implementation notebook

### Usage

1. Open `textbook_study.ipynb` in Google Colab
2. Run all cells in order
3. The notebook will:
   - Download and process the datasets
   - Train the model in three stages
   - Evaluate on coding tasks

## Requirements

- PyTorch
- Transformers
- Datasets
- BeautifulSoup4 (for textbook study)
- Requests

## License

MIT
