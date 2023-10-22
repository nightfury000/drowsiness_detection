# Drowsiness Detection

The model is trained to work on the eye-state and tell if the eyes are open or closed.
There are three steps in this
1) Data preparation - The database consisted of both open and closed images in single folder so we automated to split them using the naming index given to the images.
2) Model training - Here we trained the model and also tested the accuracy with the help of CNN model.
3) Executing to see how it works - So currently the there is a delay as it shows eyes closed and open after a few seconds and the alarm(beep) goes on continously, maybe there is a need to train it using different CNN model.

Update : 
We worked on it and adjusted the threshold value for the model and now not only it stoppped beeping continously but also it monitors for specific intervals according to the threshold value and if the eyes are closed for more than specific amount of time alarm beeps.

Output is as follows:

<div>
<img src='output/open eyes.png' width='300'> <img src='output/closed eyes.png' width='300'> 
</div>


