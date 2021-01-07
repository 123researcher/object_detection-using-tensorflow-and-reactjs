# object_detection-using-tensorflow-and-reactjs

###Building a Object Detection Model with TensorFlow’s Object Detection API

TensorFlow.js, and the Coco SSD model for object detection. load the pre-trained Coco SSD model, 
and how to build a simple implementation to detect objects from a given image. Moreover,
the library initially used to train the model.

TensorFlow.js, a library aimed towards the web and Javascript developers to develop and train machine learning models in Javascript and deploying in the browser.
TensorFlow.js, supports transfer learning, a technique for retraining pre-existing models with custom data,

TensorFlow.js comes with several pre-trained models that serve different purposes like the Coco SSD model, an object detection model that identifies
and localize multiple objects in an image.

##TensorFlow Object Detection API
TensorFlow Object Detection API is TensorFlow's framework dedicated to training and deploying detection models.

##COCO SSD

The model we'll be using , COCO SSD, is one of the "fast-but-less-accurate" side of the spectrum, making it capable of being used in a browser, 
COCO refers to the"Common Objects in Context"  dataset, the data on which the model was trained on. This collection of images is mostly used for object detection, segmentation, and captioning, and it consists of over 200k labeled images belonging to one of 90 different categories, such as "person," "bus," "zebra," and "tennis racket."

SSD or Single Shot Detector is a neural network architecture made of a single feed-forward convolutional neural network that predicts the image's objects labels and their position
##ROI
 The counterpart of this "single-shot" characteristic, is an architecture that uses a "proposal generator," a component whose purpose is to search for regions of interests within an image.
 
 ##Feature extraction
 COCO-SSD default's feature extractor is lite_mobilenet_v2, an extractor based on the MobileNet architecture.
