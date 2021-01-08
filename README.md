
### Building an Object Detection Model with TensorFlow’s Object Detection API

## TensorFlow.js 

TensorFlow.js and the Coco SSD model I used for object detection. First step is to load the pre-trained Coco SSD model.
TensorFlow.js is a library aimed towards the web and Javascript developers to develop and train machine learning models in Javascript and deploying in the browser.
TensorFlow.js supports transfer learning, a technique for retraining pre-existing models with custom data,
TensorFlow.js comes with several pre-trained models that serve different purposes like the Coco SSD model, an object detection model that identifies
and localize multiple objects in an image.

## TensorFlow Object Detection API

TensorFlow Object Detection API is TensorFlow's framework dedicated to training and deploying detection models.

## COCO SSD

The model we'll be using is COCO SSD, it is one of the "fast-but-less-accurate" side of the spectrum, making it capable of being used in a browser. 
COCO refers to the"Common Objects in Context"  dataset, the data on which the model was trained on. This collection of images is mostly used for object detection, segmentation, and captioning, and it consists of over 200k labeled images belonging to one of 90 different categories, such as "person," "bus," "zebra," and "tennis racket."

SSD or Single Shot Detector is a neural network architecture made of a single feed-forward convolutional neural network that predicts the image's objects labels and their position

## Usage
There are two main ways to get this model in your JavaScript project: via script tags or by installing it from NPM and using a build tool like Parcel, WebPack, or Rollup.

## ROI

The counterpart of this "single-shot" characteristic, is an architecture that uses a "proposal generator," a component whose purpose is to search for regions of interests within an image.

 
## Feature extraction
 
 COCO-SSD default's feature extractor is lite_mobilenet_v2, an extractor based on the MobileNet architecture.
## Labeling Data
With all the pictures gathered, we come to the next step — labeling the data. Labeling is the process of drawing bounding boxes around the desired objects. LabelImg is a great tool for creating an object detection dataset.
LabelImg supports two formats, PascalVOC and Yolo.
 
 ## create a React web app for object_detection
it takes as input your webcam live video feed and sends its frames to a pre-trained COCO SSD model to detect objects on it.
The first step is to load the TensorFlow.js library, the COCO model, and the React library from a CDN (Content Delivery Network).
