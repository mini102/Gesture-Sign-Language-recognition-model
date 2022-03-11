# Gesture-Sign-Language-recognition-model
youtube video as input
It's work on my desktop, But I can't ensure work it on your desktop. 
because these file are uploaded by my hand  
not using git in terminal, I try it of course, but it don't work

## reference
gesture recognition : https://github.com/kairess/gesture-recognition

Youtube video as input : https://github.com/gabguerin/Sign-Language-Recognition--MediaPipe-DTW/

## Data set
1. Read the csv file includes information about youtube video to want to train. 
2. Download youtube video from 1's informations. (using pytube)
3. Save the videos in specified path 
![image](https://user-images.githubusercontent.com/73246476/154867451-8fc3645c-f674-4827-bdf1-f6d9bbbf8a13.png)
![image](https://user-images.githubusercontent.com/73246476/154867458-37268e56-35f5-41b8-b82b-927edcb055e2.png)

## **Algorithm structure**
![image](https://user-images.githubusercontent.com/73246476/154867620-4fa433b8-c332-40c9-ab88-24d38dc5a7de.png)

## library
MediaPipe's hand landmark model

![image](https://user-images.githubusercontent.com/73246476/154867644-249e4bb7-5ec3-485f-9848-f0f2e8e9a6b4.png)
-> ![image](https://user-images.githubusercontent.com/73246476/154867654-b08dcad2-364c-4bb8-b54a-7ff3fa857233.png)
-> ![image](https://user-images.githubusercontent.com/73246476/154867668-6b2a8de8-8983-4336-97c3-185a667e3441.png)

Pytube
![image](https://user-images.githubusercontent.com/73246476/154867703-ec5f1654-c64c-463f-ae3f-0c02af307cc6.png)

## gesture recognition model's training accuracy
![image](https://user-images.githubusercontent.com/73246476/154867739-95c7565b-95d7-4de0-bfca-ffc6e848e112.png)

-> tensorboard visualization
http://localhost:6006/#scalars&run=train

