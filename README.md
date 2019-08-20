# Udacity_Project_Showcase

# Emotion Based Music player (Implemented in Pytorch) - Emotious

## Collaborators

Name | Slack handle |
--- | --- |
Karan Kishinani | @Karan Kishinani |
Aditya Kumar | @Aditya kumar |

## Project Notebook

Open project notebook : https://github.com/akadidas/Udacity_Project_Showcase/blob/master/Emotion_Based_Music_player_(Implemented_in_Pytorch)_Emotious.ipynb

## The Project

### What is the project about?
Emotion Based Music Player (Emotious) is a Convolutional Neural Network based model able to suggest music on the basis of "Facial Emotion Of User"  adn then play music accordingly.With the idea of using federated learning to make music app like spotify much smarter using emotion recognition and security provided by Federated learning for it making no acta\ual transfer of sensitive data like user photo being transferred and still predicting right song is feat which emotious can do quite easily and efficiently.



### Why?
This project serves as a demonstration of the concepts taught in the *Secure and Private AI Challenge*, by Udacity and Facebook. This is our submission for the Project Showcase Challenge for this program.

### Dataset

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

train.csv contains two columns, "emotion" and "pixels". The "emotion" column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The "pixels" column contains a string surrounded in quotes for each image. The contents of this string a space-separated pixel values in row major order. test.csv contains only the "pixels" column and your task is to predict the emotion column.
The training set consists of 28,709 examples. The public test set used for the leaderboard consists of 3,589 examples. The final test set, which was used to determine the winner of the competition, consists of another 3,589 examples.

This dataset was prepared by Pierre-Luc Carrier and Aaron Courville, as part of an ongoing research project. They have graciously provided the workshop organizers with a preliminary version of their dataset to use for this contest.

### Model
Architecture - CNN(4 convolutional layers used with `relu` activation function and then max pooling in all feature maps from
relu-->convnets, followed by two fully connected layers. And optimizer used is ADAM and loss used is "CrossEntropy_loss"

### Results
Results on the dataset are actually farm much better than the competetion winner (34%) And our model can predict emotions with accuracy of 54% at max.

### Open Issues
Unable to apply Federated Learning using course experience and videos along with openmind tutorials. As the tutorials are just performed on mnist data using common data_loading techniques and Pysyft is giving error on  processing custom data.I trie dto get help from some peers but they aren't also able to solve it and declared it as a bug.

## Final Comments
Emotion Based Music Player (Emotious) is a Convolutional Neural Network based model able to suggest music on the basis of "Facial Emotion Of User"  adn then play music accordingly.With the idea of using federated learning to make music app like spotify much smarter using emotion recognition and security provided by Federated learning for it making no acta\ual transfer of sensitive data like user photo being transferred and still predicting right song is feat which emotious can do quite easily and efficiently.


Please take a look at our project notebook : https://github.com/akadidas/Udacity_Project_Showcase/blob/master/Emotion_Based_Music_player_(Implemented_in_Pytorch)_Emotious.ipynb

