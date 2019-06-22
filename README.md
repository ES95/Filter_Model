# YouTube Filter Model 
 Computer Vision model to ﬂag unsafe YouTube channels (Alcohol) .
Building a CNN(Resnet50) to flag videos containing Alcoholic content.

Divided into 4 parts:-
1) DATA COLLECTION
    Downloaded data through Imagenet(download_imagenet.ipynb), Google download api(download_google.ipynb), Youtube video frames(download and extract frames.ipynb).
2) REFINING DATA (imagenet_predict.ipynb)
    Using pretrained weights from Imagenet to segregate images. As imagenet already has classes like wine,whiskey,beer bottle they can be     used to sepaerate high confidence photos from the image dump collected from step1.
3) TRAINING
    Training a CNN- Resnet50(train_RESNET50.ipynb),Inception_Resnet(train_InceptionResNetV2.ipynb) etc on the data set created after           step2.
4) PREDICTION (RESNET50_predict.ipynb)
    Using this trained model to make predictions.
