# Google-AI-object-detection
The purpose of this project is to build an algorithm that detects objects automatically using a massive training dataset with more varied 
and complex bounding-box annotations and object classes.
Object detection is the process of finding instances of real-world objects such as faces, buildings, and bicycle in images or videos. 
Object detection algorithms typically use extracted features and learning algorithms to recognize instances of an object category. 
Object detection algorithms act as a combination of image classification and object localization. It takes an image as input and produces 
one or more bounding boxes with the class label attached to each bounding box. These algorithms are capable enough to deal with multi-class 
classification and localization as well as to deal with the objects with multiple occurrences. 

The following procedures shall be followed after building a classifier which will detect objects.
1. Preparing Dataset
2. Labeling the Dataset
3. Generating Records for Training
4. Configuring Training
5. Training the Model
6. Exporting Inference Graph

We will be using datasets from Kaggle (https://www.kaggle.com/c/google-ai-open-images-object-detection-track). 
The Open Images Challenge is based on Open Images dataset. The training set of the Challenge contains:
•	12M bounding-box annotations for 500 object classes on 1.7M training images
•	Images of complex scenes with several objects–an average of 7 boxes per image
•	Highly varied images that contain brand new objects like “fedora” and “snowman”
•	Class hierarchy that reflects the relationships between classes of Open Images.

In this track of the Challenge, we are to build the best performing algorithm for automatically detecting objects and include a 
Visual Relationship Detection track to detect pairs of objects in particular relations, e.g. "woman playing guitar," "beer on table," 
"dog inside car", "man holding coffee", etc.
