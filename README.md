# Classify-Monkey-Images

[Tutorial Found Here](https://www.youtube.com/playlist?list=PL3Dh_99BJkCEhE7Ri8W6aijiEqm3ZoGRq)

## 1. Calculating Mean and Std Dev  

Necessary to allow for image transformations and normalization.

## 2. Image Dataset Preparation

Apply transformations, normalization, and conversion to Tensor. Then visualize a small batch size of data to ensure correctness

## 3. Train Neural Network

Use ResNet18 model with Pretrained Weights to take datasets, load into DataLoader, and iterate through to train neural net. Save epoch checkpoints and finished model when training complete.

## 4. Load and Classify Images

Reload saved trained model. Test classifying new images not in dataset by transforming and passing through neural net.
