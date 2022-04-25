# Dataset

If you Want to create a new dataset taking pictures using the webcam, you can run the file **Dataset_creation.ipynb**. Use key 1 to take a new photo and key q you close the camera.

To create the labels of the images, labelimg can be used. Instalation and configuration of labelimg can be found in the link:
 - **Labelimg: https://github.com/tzutalin/labelImg**

Labelimg creates a set of xml files asociated to each image. The file **Dataset_generation.ipynb** could be used to transform the xml files to csv files and to divide the dataset into train and test.

# Model training

To train the model keras-retinanet implementation (link: https://github.com/fizyr/keras-retinanet). In this case the model was trained using a Resnet50 backbone. The configuration and trainig can be found in file: **train_V2.ipynb**

# Model Inference

Some examples of model inference can be found in files:

- **webcam_inference.ipynb** : Inference of trained model using webcam 
- **Model_Inference.ipynb** : Inference of trained model in a set of images
- **ResNet50RetinaNet(COCO_Example).ipynb** : Inference of a model trained in COCO dataset.

# Enviorment:

macOS Monterrey
Conda-Miniforge-pypy3
Python 3.9.12

- keras                     2.8.0
- tensorflow-macos          2.8.0
- tensorflow-metal          0.4.0
- scikit-image              0.19.2
- scikit-learn              1.0.2
- seaborn                   0.11.2
- opencv-python             4.5.5.64
- h5py                      3.6.0
- pandas                    1.4.2
