# Real-time-Object-detection
Prerequisites
Before working on this project
Python
TensorFlow
Tensorboard
Protobuf v3.4 or above

# Introduction
Creating accurate Machine Learning Models which are capable of identifying and localizing multiple objects in a single image 
remained a core challenge in computer vision. But, with recent advancements in Deep Learning, Object Detection applications
are easier to develop than ever before. TensorFlow’s Object Detection API isan open source framework built on top of TensorFlow 
that makes it easy to construct, train and deploy object detection models.

In this Object Detection project, i focussed on Deep Learning Object Detection as Tensorflow uses Deep Learning for computation.

Setting up the Environment
Now to Download TensorFlow and TensorFlow GPU you can use pip or conda commands:
# For CPU
pip install tensorflow
# For GPU
pip install tensorflow-gpu
 

For all the other libraries we can use pip or conda to install them. The code is provided below:
pip install --user Cython
pip install --user contextlib2
pip install --user pillow
pip install --user lxml
pip install --user jupyter
pip install --user matplotlib

Next, i have downloaded the model which is trained on the COCO dataset. COCO stands for Common Objects in Context, 
this dataset contains around 330K labeled images. Now the model selection is important as you need to make an important 
tradeoff between Speed and Accuracy.Depending upon your requirement and the system memory, the correct model must be selected.




