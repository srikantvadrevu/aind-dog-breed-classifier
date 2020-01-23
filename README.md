[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

Built an image classifer that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, the classifier has to detect that the image corresponds to a dog and predict the dog's breed. If a human image is submitted, the classifier must detect that the image corresponds to a human! In the case of the image corresponds neither to a dog nor a human, the classifier only has to output that no prediction will be made.  

I worked on this project as part of Udacity Artifical Intelligence Nano degree program. You can find my solution [here](https://nbviewer.jupyter.org/github/srikantvadrevu/dog-breed-classifier/blob/master/mysolution.ipynb).


![Sample Output][image1]

### Instructions

To clone the original project repository - 
```	
git clone https://github.com/udacity/dog-project.git
cd dog-project
```

## Data

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 

* Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

* Download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.
