### Project Created on May 17,2022


### Title: Lighter Detection using Azure Custom Vision for Automated Passenger Boarding Kiosk


### Description
The project makes use of Azure Custom Vision from Azure Cognitive Services and the Python SDK to detect if a passenger's carry-on items include a lighter or not.

A custom object detection model is built first, and then this model is used to detect if a given image contains a lighter.

### Files

[Labelling](Labelling) The labelling folder contains screenshots taken during the image labelling process on Custom Vision Portal
[training_process.png](training_process.png) The screenshot from the Custom Vision Portal while performing the training process of the object detection model
[precision_and_recall.png](precision_and_recall.png) The Screenshot shows the precision and recall values of the trained custom object detection model
[published_endpoint.png](published_endpoint.png) The Screenshot shows a Python code snippet showing the model deployed to an endpoint
[performing_prediction.png](performing_prediction.png) The Screenshot shows a Python code snippet showing how the model is used for prediction using the endpoint
[lighter_detection_probability.png](lighter_detection_probability.png) The Screenshot shows lighter detection probability using the custom object detection model for every one of the 5 provided test images
