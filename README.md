# UCF101-video-dataset-cnn-model
cnn model that predict the category of a video

# steps followed :-
### 1- first of all we discover the dataset , try to understand it
### 2- the processing of the video data is done by capturing each video using(cv2 libraray)
### 3- then we get 10 frames -imgaes- each n-seconds and form a set of images for each video
### 4- then from these images we chose a certain number of images to enter the model
### 5- we create the cnn model 
### 6- test the results using accuracy and val-accuracy

# models performed :- 
                      A cnn parallel model
                      A normal cnn model which got better results 91% val-acc
