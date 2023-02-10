# Strawberry Detection
This set of Notebooks provides a complete set of code to be able to train and leverage your own custom Strawberry Detection model using the Tensorflow Object Detection API.
![alt text](https://github.com/naruep/StrawberryDetection/blob/main/images/001.JPG?raw=true)
## Steps
### Step 1. 
Clone this repository: [StrawberryDetection](https://github.com/naruep/StrawberryDetection.git)
### Step 2.
Create a new virtual environment
### Step 3.
Activate your virtual environment
### Step 4.
Install dependencies and add virtual environment to the Python Kernel
### Step 5.
Collect images using the Notebook 1. [Image Collection.ipynb](https://github.com/naruep/StrawberryDetection/blob/main/ImageLabelling.ipynb) - ensure you change the kernel to the virtual environment as shown below
![alt text](https://github.com/naruep/StrawberryDetection/blob/main/images/007.JPG?raw=true)
### Step 6.
Training process by opening 2. [Training and Detection.ipynb](https://github.com/naruep/StrawberryDetection/blob/main/StrawberryDetectionVersion1.0.1.ipynb), this notebook will walk you through installing Tensorflow Object Detection, making detections, saving and exporting your model.
### Step 7.
Once you get to step 6. Train the model, inside of the notebook, you may choose to train the model from within the notebook. I have noticed however that training inside of a separate terminal on a Windows machine you're able to display live loss metrics.
### Step 8.
You can optionally evaluate your model inside of Tensorboard. Once the model has been trained and you have run the evaluation command under Step 7. Navigate to the evaluation folder for your trained model e.g.
```ruby
cd Tensorlfow/workspace/models/my_ssd_mobnet/eval
```
and open Tensorboard with the following command
```ruby
tensorboard --logdir=.
```
![alt text](https://github.com/naruep/StrawberryDetection/blob/main/images/002.JPG?raw=true)
### Dataset
This is the dataset of the [Strawberry Digital Images (StrawDI)](https://strawdi.github.io/), which contains 8000 images of strawberries, taken from 20 plantations, within an approximate area of 150 hectares, in the province of Huelva, Spain.
