# Image-Classification-usng-Deep-Neural-Networks

# Dog vs Cat Classification (CNN from Scratch)

This project builds a Convolutional Neural Network (CNN) from scratch to classify images as either **dog** or **cat**.

## Project Structure
- `src/split_data.py`: splits raw dataset into train/val/test folders
- `src/train.py`: trains CNN model and saves best model
- `src/evaluate.py`: evaluates model on test set + prints confusion matrix
- `src/predict.py`: predicts on a single image
- `data/`: dataset folder (not included in repo)
- `models/`: trained model output

## Setup
```bash
pip install -r requirements.txt
