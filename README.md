# msds19005_COVID19_DLSpring2020
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”

# Datasets
* Shared Google Drive Link to the Dataset for __covid vs normal__ can be found here
[link](https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK&authuser=0)
* Shared Google Drive Link to the Dataset for __covid vs pneumonia vs normal__ can be found here
[link](https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=0)

# Trained Weights
## Part1
The Shared Google Drive Link for saved weights corresponding to Finetuning and Retraining with naive appraoch are given below
* [Finetuning FC Layers](https://drive.google.com/open?id=1IdKY0K4D15RHScjDLYbunJ8L3lWTiF5-)
* [Unfreezing Partial Conv Layers](https://drive.google.com/open?id=1i3QHQNg_Bq4UAAWiK-_VRoPZpmXnFuVq)
* [Retraining Complete Model](https://drive.google.com/open?id=1Gp6H6SaXs6nsU8Pts98LY3MeB48K_0yC)</br>
## Part2
The Shared Google Drive Link for saved weights corresponding to Finetuning with and without focal loss for class balancing on VGG and ResNet is given [link](https://drive.google.com/open?id=1V7MaxYag43sEwmUNl1NklidXI3gIz6XC)

# Results (No Class Balancing)
_Test Accuracy and F1 Score_
||ResNet|VGG|
|---|-----|------|
|Fine Tuning FCs|89%-0.91|92%-0.93|
|Complete Retraining|95%-0.96|95%-0.96|

The above row corresponds to ResNet and bottom row corresponds to VGG Confusion Matrices for Test Set(right FineTuned FCs, left Complete Retraining) *Note* 0->covid-19  1->normal
<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/results/task1_test.png" width =500 height =400>


# Results (Class Balancing)
Below are the results with and without application of focal loss for class balancing.
_Validation Accuracy and F1 Score_
||ResNet|VGG|
|---|-----|------|
|with Focal Loss|95%-0.69|96%-0.83|
|without-Focal Loss|96%-0.68|96%-0.90|

In the following images pper row corresponds to confusion matrices obtained per class with application of focal loss. And the bottom row corresponds to the confusion matrices obtained when no focal loss is applied (clearly demonstrating how focal loss improves the representation learning of sparse classes).
## ResNet

<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/results/res.png" width=800 height=400>

## VGG

<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/results/vgg.png" width=800 height=400>

