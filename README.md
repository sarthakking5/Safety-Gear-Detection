# Safety-Gear-Detection
The project aims to detect whether the person is wearing the gear that ensures safety in factories and construction sites.Using the Tensorflow Object Detection API the model has been extensively trained using a Single Shot Multibox Detector framework and have achieved an accuracy over 98%.

![](https://github.com/sarthakking5/Safety-Gear-Detection/blob/4da7d2544711652d922bd10509c3986012491610/images/output_gif.gif)

**<font size="+3">Steps</font>**

**1.Cloning the model**

You can install the TensorFlow Object Detection API either with Python Package Installer (pip) or Docker, an open-source platform for deploying and managing containerized applications. For running the Tensorflow Object Detection API locally, Docker is recommended. If you aren't familiar with Docker though, it might be easier to install it using pip.

First clone the master branch of the Tensorflow Models repository:

https://github.com/tensorflow/models.git

**2.Protobuf Installation/Compilation**

The Tensorflow Object Detection API uses Protobufs to configure model and training parameters. Before the framework can be used, the Protobuf libraries must be downloaded and compiled.

This should be done as follows:

# From within TensorFlow/models/research/
protoc object_detection/protos/*.proto --python_out=.

**3.Installation**

Install the Tensorflow\models\research\object_detection package by running the following from Tensorflow\models\research:

# From within TensorFlow/models/research/
pip install .
