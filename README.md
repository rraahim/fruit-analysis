# Fruit Segmentation with Computer Vision :rocket:

## Getting started

- Clone this repository
- Unzip the FruitSegmentation.zip file
- Open the FruitSegmentation.ipynb file in [Google Colab](https://colab.research.google.com/)
- Connect to a GPU powered instance. (Runtime -> Change runtime type -> Hardware accelerator -> GPU)

## Dataset

The dataset used for this project is the [Fruit-Images-Dataset](https://storage.googleapis.com/openimages/web/visualizer/index.html?type=segmentation&set=train&r=false&c=%2Fm%2F014j1m)

## Trained Model Weights

The trained model weights can be found [here](https://drive.google.com/drive/folders/1mMUBrGo9Ng1qCs8606zNDF6SQ8XujmKb?usp=sharing)

## Results

The model acheives a 98.67% class-accuracy on the test set, with transfer learning on MaskRCNN. Here's a snapshot from the model output,
![alt text](<https://oshi.at/TcmJ/lYpU.png>)

## Tensorboard 

The tensorboard logs are as follows. 
![DATA](https://oshi.at/rvtV/Maov.png)
![ETA](https://oshi.at/Udmt/DmZX.png)

## Quality Classification

The quality classification uses Google's Efficientnet B0, trained on classifying good fruits v/s bad fruits based on the fruit's shelf life.
