# EMstellar
This repository is official implementation of [**EM-net: Deep learning for electron microscopy image segmentation**](https://www.biorxiv.org/content/10.1101/2020.02.03.933127v1) on Google Colab.

---

<font size = 4>This notebook represents a benchmark of deep learning methods for electron microscopy image segmentation. A variety of deep learning methods have been utilised including EM-net, U-net, SegNet, ResNet and VGG. All these networks represent a similar encoding-decoding scheme for image segmentation. 



---
<font size = 4>*Disclaimer*:

<font size = 4>This notebook is part of the EMstellar (https://github.com/akhadangi/EMstellar).

<font size = 4>Papers related to this Notebook: 

- <font size = 3>**EM-net: Deep learning for electron microscopy image segmentation** by *Afshin Khadangi, Thomas Boudier, Vijay Rajagopal*  (https://www.biorxiv.org/content/10.1101/2020.02.03.933127v1)

- <font size = 3>**U-Net: Convolutional Networks for Biomedical Image Segmentation** by *Olaf Ronneberger, Philipp Fischer, Thomas Brox*  (https://arxiv.org/abs/1505.04597)

- <font size = 3>**Very Deep Convolutional Networks for Large-Scale Image Recognition** by *Karen Simonyan, Andrew Zisserman*  (https://arxiv.org/abs/1409.1556)

- <font size = 3>**SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation** by *Vijay Badrinarayanan, Alex Kendall, Roberto Cipolla*  (https://arxiv.org/abs/1511.00561)

- <font size = 3>**Deep Residual Learning for Image Recognition** by *Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun*  (https://arxiv.org/abs/1512.03385)

<font size = 3>and 

- <font size = 3>**ZeroCostDL4Mic: an open platform to simplify access and use of Deep-Learning in Microscopy** by *Lucas von Chamier, Johanna Jukkala, Christoph Spahn, Martina Lerche, Sara Hernández-pérez, Pieta Mattila, Eleni Karinou, Seamus Holden, Ahmet Can Solak, Alexander Krull, Tim-Oliver Buchholz, Florian Jug, Loic Alain Royer, Mike Heilemann, Romain F. Laine, Guillaume Jacquemet, Ricardo Henriques*  (https://www.biorxiv.org/content/10.1101/2020.03.20.000133v1)

<font size = 4>**Please also cite this original paper when using or developing this notebook.** 

<font size = 4> This notebook is adapted and developed from the [**ZeroCostDL4Mic**](https://github.com/HenriquesLab/ZeroCostDL4Mic).

---

# **How to use?!**

**Important: Make sure that you create a copy of the following Colab Notebook on your Google Drive before running or making any changes to the notebook**
---

<font size = 4>We have provided the instructions for the usage of this Notebook in the following link:
  - [**Colab Notebook**](https://colab.research.google.com/github/akhadangi/EMstellar/blob/master/EMstellarNeuronalGithub.ipynb): Walk through the pipeline including data upload, training and deploying the trained model.


---
### **Structure of a notebook**

<font size = 4>The notebook contains two types of cell:  

<font size = 4>**Text cells** provide information and can be modified by douple-clicking the cell. You are currently reading the text cell. You can create a new text by clicking `+ Text`.

<font size = 4>**Code cells** contain code and the code can be modfied by selecting the cell. To execute the cell, move your cursor on the `[ ]`-mark on the left side of the cell (play button appears). Click to execute the cell. After execution is done the animation of play button stops. You can create a new coding cell by clicking `+ Code`.

---
### **Table of contents, Code snippets** and **Files**

<font size = 4>On the top left side of the notebook you find three tabs which contain from top to bottom:

<font size = 4>*Table of contents* = contains structure of the notebook. Click the content to move quickly between sections.

<font size = 4>*Code snippets* = contain examples how to code certain tasks. You can ignore this when using this notebook.

<font size = 4>*Files* = contain all available files. After mounting your google drive (see section 1.) you will find your files and folders here. 

<font size = 4>**Remember that all uploaded files are purged after changing the runtime.** All files saved in Google Drive will remain. You do not need to use the Mount Drive-button; your Google Drive is connected in section 1.2.

<font size = 4>**Note:** The "sample data" in "Files" contains default files. Do not upload anything in here!

---
### **Making changes to the notebook**

<font size = 4>**You can make a copy** of the notebook and save it to your Google Drive. To do this click file -> save a copy in drive.

<font size = 4>To **edit a cell**, double click on the text. This will show you either the source code (in code cells) or the source text (in text cells).
You can use the `#`-mark in code cells to comment out parts of the code. This allows you to keep the original code piece in the cell as a comment.
