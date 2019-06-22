# YouTube Filter Model 
 Computer Vision model to ﬂag unsafe YouTube channels (Alcohol) .
Building a CNN(Resnet50) to flag videos containing Alcoholic content.
Divided into 4 parts:-
1) DATA COLLECTION
    Downloaded data through Imagenet, Google download api, Youtube video frames.
2) REFINING DATA
    Using pretrained weights from Imagenet to segregate images. As imagenet already has classes like wine,whiskey,beer bottle they can be     used to sepaerate high confidence photos from the image dump collected from step1.
3) TRAINING
    Training a CNN- Resnet50,Inception_Resnet etc on the data set created after step2.
4) PREDICTION
    Using this trained model to make predictions.
