# Computer_Vision_Assignments
Bag of Visual Words (BoVW) is a computer vision technique that represents an image as a collection of unordered image patches, known as visual words. BoVW is inspired by the "Bag of Words" concept of Natural Language Processing. Instead of taking words from the text, BoVW extracts image patches and their feature vectors from an image into a bag. The feature of the image consists of keypoints and descriptors. Keypoints are the unique points in an image that remain the same regardless of rotation, scaling or translation, and descriptors describe the keypoints.

In this project, we aim to build a text classification model to automatically categorize flowers and objects into various classes. We will be using a dataset consisting of flowers and objects categories. Our proposed methodology consists of using a combination of feature extraction techniques, such as Bag-of-Words and SIFT etc, along with various classification algorithms, such as Naive Bayes and SVM, and also Random forest to build a high-performing text classification model.

The BoVW technique for image classification has three steps:

Feature Extraction – Determination of Image features of a given label.
Codebook Construction – Construction of visual vocabulary by clustering, followed by frequency analysis.
Classification – Classification of images based on vocabulary generated using SVM.
In this assignment, the task is to perform image classification on two datasets using BoVW or any other feature detector such as SIFT, FAST, ORB or BRIEF. The two classifiers used are SVM and Random Forest, and the sklearn or OpenCV library functions can be used to compute features. Different parameters can be experimented with, and the results obtained after training both classifiers, including F1 Score, Accuracy, True Positive Rate, False Positive Rates, and qualitative results, will be reported.

The datasets provided for the task are Objects and Flowers, with 50 points allocated for each dataset. The distribution of points for each dataset is 20 points for the report and 30 points for the code. 
