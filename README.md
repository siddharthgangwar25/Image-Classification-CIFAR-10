# Image-Classification-CIFAR-10
## About
[**CIFAR-10**](https://en.wikipedia.org/wiki/CIFAR-10)  is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of **60,000 32x32 color images** containing one of **10 object classes**, with 6000 images per class. It was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. The classes are completely mutually exclusive. For example, there is no overlap between automobiles and trucks. Also, Automobiles includes sedans, SUVs, etc. The project also contains a **Tkinter based GUI**. <br />Here are the classes in the dataset: <br /> <br />
<img src="https://paperswithcode.com/media/datasets/CIFAR-10-0000000431-b71f61c0_U5n3Glr.jpg" width="300" height="300"><br />
## Usage:
To create and train CNN model:
```bash
Run CIFAR_Classification.ipynb
``` 
To run the graphical user interface: <br />
*File model1_cifar.h5 contains weights of an already trained CNN model for CIFAR-10*
```bash
Run GUI.py
``` 
```bash
Upload an image to be predicted
``` 
*Three images for testing are provided*
## CNN 
<img src="https://i.ibb.co/W5bgqzR/Capture.png" width="450" height="280"><br /><br />
A 24-layer CNN model is created consisting of multiple Convolution, Pooling and Dense Layers. Batch Normalization and Dropout is used for Regularization to avoid overfitting.<br />
File **model_plot.png** consists the architecture of the model.
