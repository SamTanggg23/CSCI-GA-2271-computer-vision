# CSCI-GA-2271-computer-vision

## Brief Introduction

Here are the final project codes for our CV course.

We pre-trained Masked AutoEncoder on Food 101 dataset from HuggingFace, which contains around 100k images of 101 different types of foods. Then we used the pre-trained model to fine-tune on food classification task.

We compared the fine-tuning results of MAE models pre-trained for different epochs (200, 400, 600). To show the strong power of transfer learning, we also include training a plain ViT(also MAE) from scratch on our classification task, which should be a baseline for our experiments.

Meanwhile, we combine ResNet-50 to explore the difference between Vision Transformer and Convolutional Neural Net.

## Team members

Huanze(Sam) Tang: ht2413@nyu.edu

Kundan Suri: ks6965@nyu.edu