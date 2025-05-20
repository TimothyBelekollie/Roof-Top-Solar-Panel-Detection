# RoofTop Solar Panel Detection using Deep Learning

## Project Overview

This repository contains code and documentation for an end-to-end deep learning pipeline to detect rooftop solar panels from high-resolution satellite imagery. We leverage an EfficientNetB0-based CNN for binary classification (panel vs. non-panel) and demonstrate robust performance in an urban African context. :contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}

## Features

- **Binary Classification** of satellite image tiles into “solar panel” or “no solar panel.”
- **EfficientNetB0 Backbone** pre-trained on ImageNet, with custom top layers for binary output.
- **Class Imbalance Handling** via computed class weights.
- **Stratified K-Fold Cross-Validation** for reliable performance estimation.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrices.
- **Visualization** of ROC curves and confusion matrices.
- **Jupyter Notebook** demonstrating full training, validation, and inference workflow.
