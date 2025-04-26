# Design Thinking - Multiclass Image Classification

## Introduction

This project is a hands-on application of machine learning principles focused on solving a multiclass image classification problem.  
I curated the dataset by scraping images from the web, creating a real-world and practical dataset that captures the diversity of the target classes.

Through this notebook, I explore the end-to-end pipeline:
- Image data collection
- Preprocessing
- Model development
- Evaluation and interpretation of results

This work embodies the spirit of Design Thinking — understanding the problem, ideating creative solutions, and iteratively improving through experimentation.

## Project Overview

- **Problem Type**: Multiclass Classification
- **Data Source**: Self-scraped image dataset from the web
- **Number of Classes**: 5
- **Approach**:
  - Image scraping and organization
  - Data augmentation and preprocessing
  - Model building using deep learning techniques
  - Performance evaluation and visualization

## Highlights

- Data Scraping: Automated image scraping for multiple classes
- Preprocessing: Resizing, normalization, and augmentation
- Modeling: Fine-tuned deep learning architectures
- Evaluation: Accuracy, loss metrics, and visualization of predictions
- Iterative Improvement: Guided by Design Thinking methodology

## Application Idea

An exciting real-world extension of this project would be to build a mobile application that uses this trained model as a backend service for **waste segregation**.  
- Users can scan their waste items, and the app classifies them into the appropriate categories.
- Users who segregate waste properly earn **rewards based on the amount** they recycle.
- This promotes environmental responsibility and aligns with a **global cause** of promoting sustainable living.

By combining technology, incentive systems, and social good, we can encourage better waste management practices at the community level.

## How to Run

1. Clone this repository.
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the `DesignThinking.ipynb` notebook end-to-end.

## Notes

- This dataset is custom-scraped and may have noisy labels, representing a real-world messy data scenario.
- Focused on applying Design Thinking: Empathize with the problem, Define the challenge, Ideate solutions, Prototype models, and Test performance.

## Future Improvements

- Fine-tune scraping pipeline for higher-quality images
- Experiment with more advanced CNN architectures
- Deploy model via a simple web application for live demo

## Acknowledgements

Inspired by the core principles of Design Thinking and the continuous pursuit of building human-centered AI solutions.
