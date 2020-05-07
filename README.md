**Emojinator**  
This code helps you to recognize and classify different hand emojis. 
!(https://imgix.bustle.com/uploads/image/2020/4/8/4bbe41e3-81c4-4660-95de-3c432687af2e-4341da6b-70d4-40bb-aacb-c19e545c1e85-img_9458.jpg?w=970&h=546&fit=crop&crop=faces&auto=format%2Ccompress&cs=srgb&q=70)

**Code Requirements**

You can install Conda for python which resolves all the dependencies for machine learning.

**Description**

Emojis are ideograms and smileys used in electronic messages and web pages. Emoji exist in various genres, including facial expressions, common objects, places and types of weather, and animals. They are much like emoticons, but emoji are actual pictures instead of typographics.

**Functionalities**

Filters to detect hand.
CNN for training the model.
Python Implementation
Network Used- Convolutional Neural Network


**Procedure**

1.First, you have to create a gesture database. For that, run CreateGest.py. Enter the gesture name and you will get 2 frames displayed. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.

2.Repeat this for all the features you want.

3.Run CreateCSV.py for converting the images to a CSV file

4.If you want to train the model, run 'TrainEmojinator.py'

5.Finally, run Emojinator.py for testing your model via webcam.
