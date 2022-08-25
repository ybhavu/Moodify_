# Melodify

## About
We all know that the choice of our songs depends on the mood we have! If I have had a rough day, I will be listening to sad songs and if I am in a jolly mood I will listen to happy songs. So instead of searching the songs, we can directly use “Melodify” where songs can be played based on our moods!

## What it does
Melodify is a facial expression recognition-based music suggestion website that cheers up users and saves time while searching for a song that matches their mood.
1.	It recognizes facial expression based on the 7 categories i.e., angry, sad, fear, happy, disgust, surprise and neutral.
2.	Based on the emotion it gives user the choice to play the songs 
3.	When user clicks on the “songs” button, a html page of that mood opens up with different songs on it , when user selects and click on one song poster , they are redirected to Spotify website.

## Tech Stack
**Frontend**:  Javascript, Html ,CSS  <br/>
**Backend**: Python, Flask  <br/>
**Libraries**: OpenCV, NumPy ,Tensorflow

## Prerequisites
To make sure that this project works well on your device, you need to install some libraries/frameworks/modules:
1)opencv (command - pip install opencv-python)
2)numpy
3)tensorflow
4)flask

### Also make sure, that you login to your Spotify account before starting the implementation of the project. This will save time later as after the mood is recognised you won’t be asked to login again to your Spotify account.

## DEMO
1 ) Open main.py file and run it. Click on the link generated.
     You will be able to see the homepage of Melodify website
     
![image](https://user-images.githubusercontent.com/88928334/170862091-1d29b658-6936-4812-b14a-640817d404cb.png)

2) Click on Let’s start button. The web cam will start and you will see a tkinter window showing your mood 
3) The recognised mood will be displayed on the page. Here the mood recognised was “happy”

![image](https://user-images.githubusercontent.com/88928334/170862113-db6e1c05-9e68-4288-ae7d-7f9e875bb858.png)

4) Click on the “Songs” button. This will display songs of the recognised mood . In this case it is “happy”. The below page will show up

![image](https://user-images.githubusercontent.com/88928334/170862127-aa396ec8-71e3-4878-9bf3-9bd22975b05c.png)

5) Click on any song and you will be redirected to Spotify website

![image](https://user-images.githubusercontent.com/88928334/170862144-b3d71423-6617-4d93-9f26-210687a5552b.png)

6) Enjoy the music!


## What's next for Melodify
The next step is to improve the model's accuracy. I will also introduce a login page where the user could capture his/her image and a Cartoonified version of that captured image will be displayed as the user’s profile pic. Also, I will widen the scope of songs that are getting suggested for a particular mood. Currently there are around 12 songs being displayed after a mood is recognised.













