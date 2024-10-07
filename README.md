Enhancing Medical Diagnosis Through Multimodal Medical Image Fusion

OVERVIEW 

The proposed system is a Flask-based web application designed for multimodal medical image fusion, focusing on brain tumor detection and classification. It consists of three modules:

1. *Image Registration Module*: Aligns Brain MRI and CT scan images using Procrustes analysis to ensure spatial correspondence, enhancing accuracy for subsequent analysis.

2. *Image Fusion Module*: Utilizes the Discrete Wavelet Transform technique to decompose MRI and CT images into frequency bands. It selects relevant subbands and combines them to create a fused image. Integration of the VGG19 model enhances the fused image and extracts meaningful features.

3. *Image Classification Module*: Employs a custom CNN architecture trained on a diverse dataset of brain tumor types. This module accurately detects and categorizes tumors, enabling clinicians to understand their nature and tailor treatment strategies accordingly.

Submitted by Team-12

How to Setup
1. Clone the repository using git clone
2. Install the necessary libraries and dependencies
3. Run the Image registration module first before executing the main script

System Requirements

    SOFTWARE REQUIREMENTS
    •	Operating System	    :	Windows, MacOS, or Linux distributions.
    •	Programming Language	:	Python for implementing image processing and deep learning models.
    •	Development Environment	:	PyCharm, Visual Studio Code, or Jupyter Notebook.
    •	Libraries	            :	OpenCV, Numpy, TensorFlow or PyTorch, tensorFlow, Scikit-learn, Matplotlib.

    HARDWARE REQUIREMENTS
    •	Processor	   :	intel i3(minimum)
    •	Ram	           :	4 GB (minimum)
    •	Hard Disk	   :	250GB (minimum)
    •	Input Devices  :	Keyboard and mouse.
