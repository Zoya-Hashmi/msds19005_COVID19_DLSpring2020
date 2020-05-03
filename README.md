# msds19005_COVID19_DLSpring2020
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”

# Datasets
* Shared Google Drive Link to the Dataset for __covid vs normal__ can be found here
[link](https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK&authuser=0)
* Shared Google Drive Link to the Dataset for __covid vs pneumonia vs normal__ can be found here
[link](https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=0)

# Trained Weights
## Part1
The Shared Google Drive Link for saved weights corresponding to Finetuning and Retraining are given below
* [Finetuning FC Layers](https://drive.google.com/open?id=1IdKY0K4D15RHScjDLYbunJ8L3lWTiF5-)
* [Unfreezing Partial Conv Layers](https://drive.google.com/open?id=1i3QHQNg_Bq4UAAWiK-_VRoPZpmXnFuVq)
* [Retraining Complete Model](https://drive.google.com/open?id=1Gp6H6SaXs6nsU8Pts98LY3MeB48K_0yC)</br>
## Part2
The Shared Google Drive Link for saved weights corresponding to Finetuning with and without focal loss on VGG and ResNet is given [link](https://drive.google.com/open?id=1V7MaxYag43sEwmUNl1NklidXI3gIz6XC)

# Qualitative Results (Without Focal Loss)
## ResNet
<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/images/res_full.png" width=600 height=300>

## VGG

<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/images/vgg_full.png" width=600 height=300>

</br>

__To interpret images:__ </br>

Column1 00 | Column2 01 | Column3 10 | Column4 11</br>
0 is infected class 1 is healthy, first number represents true label, 2nd represents predicted label
<!--![image](https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/images/res_full.png){:height="50%" width="50%"}
![image](https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/images/vgg_full.png | width=600px | height=300px)--!>

<!--<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/blob/master/images/res_full.png" width=600 height=300>
<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/New Folder/vgg_full.png>--!>


# With Focal Loss
<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/tree/master/results./res.png" width=600 height=300>
<img src="https://github.com/Zoya-Hashmi/msds19005_COVID19_DLSpring2020/tree/master/results/vgg.png" width=600 height=300>
