# Sign-Language-Detection Using yolov5l


https://user-images.githubusercontent.com/78307104/132888156-a6c67855-08ab-4815-8a01-30290b99b11e.mp4


#Introduction

why to build sign language detection??
Sign language recognition refers to the conversion of these gestures into words or alphabets of existing formally spoken languages. Thus, conversion of sign language into words by an algorithm or a model can help bridge the gap between people with hearing or speaking impairment and the rest of the world

#what you can use sign language for??

Although signing is used primarily by the deaf and hard of hearing, it is also used by hearing individuals, such as those unable to physically speak, those who have trouble with spoken language due to a disability or condition (augmentative and alternative communication), or those with deaf family members



#Steps
1-First of all i would like to tell in this sign language i have trained my model on only 5 sign That is
#Thank You
![image](https://user-images.githubusercontent.com/78307104/132890836-984a91c0-610c-4335-bb78-15d93bceba93.png)

#Hello
![image](https://user-images.githubusercontent.com/78307104/132891017-8c69e33c-c444-40c7-a290-b56a12820833.png)

#Yes
![image](https://user-images.githubusercontent.com/78307104/132891077-f4e92b46-58b1-4452-969f-940ddc93ae54.png)

#No
![image](https://user-images.githubusercontent.com/78307104/132891123-8acf0e35-d41d-406a-a703-285ef419f61c.png)

#I Love You
![image](https://user-images.githubusercontent.com/78307104/132891201-658aab41-d7ff-4038-83cf-be68b1b3f072.png)

2-I have collected data for these images and then apply data augmentation on that to increase the size of my input images.

3-Then i labeled my images using labellmg for each classes i had 40 images of each classes.

4-Then i trained my yolov5l model on 200 epochs on google colab 

5-At the time for testing i had also set my confidence level at 60% so it will only show me the best accuracy box at the time of prediction













