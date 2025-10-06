# Animal_Detection_Models
Overview:
This project uses the VGG16 pre-trained model for image classification tasks.
It demonstrates how to apply transfer learning to a custom dataset using Keras and TensorFlow.

Files:
- ipynb files   : Jupyter notebook with the full implementation.
- dataset/      : Folder containing training and testing images (create this yourself).
- README.txt    : This file.

Instructions:
1. Install required libraries:
   - tensorflow
   - keras
   - matplotlib

   Use the following command:
   pip install tensorflow keras matplotlib

2. Prepare your dataset for train and test.
link for dataset: "/kaggle/input/animals-detection-images-dataset"
link for Imagent_weights: "/kaggle/input/imagent-weight"
4. Open VGG16.ipynb using Jupyter Notebook.
5. Run all cells to train and evaluate the model.

Features:
---------
- Loads every model with pre-trained ImageNet weights
- Custom top layers added for transfer learning
- Uses image data generators for augmentation
- Trains on custom dataset
- Plots training/validation accuracy and loss

Requirements:
-------------
- Python 3.7 or higher
- Jupyter Notebook
- TensorFlow 2.x
- Keras
- Matplotlib
