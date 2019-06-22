# Deg-Breed-classifier-using-CNNs
In this project, I have bult a pipeline to process real-world, user supplied images. A pipeline that can be used within a web or mobile app. Given an image of a dog, our algorithm will idenity an estimate of the canine's breed. If supplied an image of a human, the code will identify the resembling dog breed. This project was a part of udacity's deep learning nanodegree.

- The datasets that we are using is of [dogs](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) and [humans](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) to distinguish between them.

- We used OpenCV's implementation of [Haar feature-based cascade classifiers](http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html) to detect human faces in images. OpenCV provides many pre-trained face detectors, stored as XML files on [github](https://github.com/opencv/opencv/tree/master/data/haarcascades). We have downloaded one of these detectors and stored it in the haarcascades directory.

- We used a [pre-trained model](http://pytorch.org/docs/master/torchvision/models.html) to detect dogs in images. Specifically VGG-16 model, along with weights that have been trained on [ImageNet](http://www.image-net.org/), a very large, very popular dataset used for image classification and other vision tasks. ImageNet contains over 10 million URLs, each linking to an image containing an object from one of [1000 categories](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a).


