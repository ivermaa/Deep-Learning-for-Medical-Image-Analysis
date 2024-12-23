# Medical Image Processing and Pneumonia Classification
Welcome to the repository where we explore deep learning techniques for medical image analysis. 
Here, you will find code, datasets, 
and documentation on how to apply machine learning models to classify medical images, 
specifically focusing on pneumonia detection. I have started the project learning how to handle Dicom files, followed
by exploring the preprocessing techniques and then the pneumonia classification.

## Key Features
### DICOM File Handling: 
Scripts for loading and inspecting DICOM files to understand metadata and image details.
### Image Visualization: 
Tools to render medical images from DICOM files, aiding in verification and analysis.
### Deep Learning Model:
A convolutional neural network for pneumonia detection, trained on chest X-ray images.

## Libraries and Technologies
1. Pydicom: For reading and manipulating DICOM files.
2. Matplotlib: Used for visualizing data and medical imaging.
3. SimpleITK: For simplified interaction with medical images.
4. Nibabel: Accesses and manipulates neuroimaging data.
5. PyTorch and Torchvision: For constructing and training neural network models.
6. Torchmetrics and Pytorch-lightning: For enhancing training procedures and metrics evaluation.

## Installation
pip install pydicom matplotlib SimpleITK nibabel torch torchvision torchmetrics pytorch-lightning
