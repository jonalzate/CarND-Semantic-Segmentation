# Semantic Segmentation
### Introduction
In this project, we label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.


##### Run
Run the following command to run the project:
```
python main.py
```

### Model Output

Output images after passing them through the trained model
The rest of output images are located in the 'runs' directory

![image_1](/runs/images/um_000013.png)
![image_2](/runs/images/um_000061.png)
![image_3](/runs/images/um_000090.png)
 
 
