# Breast Cancer Image Classification using Swin Transformer Transfer Learning

This repository presents a simple implementation of breast cancer histopathology image classification using a Swin Transformer with transfer learning. The study explores how pretrained hierarchical transformer representations can be fine-tuned to support medical image recognition in an efficient and reproducible manner.

The notebook provides an end-to-end workflow, including data loading from external storage, image preprocessing and resizing, adaptation of pretrained weights, replacement of the final classification layer, supervised training, and performance evaluation. By leveraging transfer learning, the model benefits from prior visual knowledge while reducing computational demand.

The experiments are primarily designed to run in Google Colab, but they can also be executed in a local Jupyter Notebook setup with minor modifications to the directory paths.

📂 Dataset

Because of repository size limitations, the datasets are stored externally on Google Drive. Please download or mount them before running the code.

- BreakHis 200× dataset : https://drive.google.com/drive/folders/1fHrMNHqArqTD9XtANHzNlNDq41q9nxqj?usp=sharing

- BreastCancerImager dataset : https://drive.google.com/drive/folders/1hV7RVMtem8z2GUffm1_T3exBM32qE5zz?usp=sharing

After downloading, place the folders inside a directory such as data/, or mount Google Drive in Colab and update the paths accordingly.

This implementation is intended as a lightweight educational project, suitable for introductory experimentation, baseline development, and comparison with models trained from scratch.
