Facial Expression Recognition Classifier Model :

Facial expression for emotion detection has always been an easy task for humans, but achieving the same task with a computer algorithm is quite challenging. With the recent advancement in computer vision and machine learning, it is possible to detect emotions from images.In this project,we propose a novel technique called facial emotion recognition using convolutional neural networks,python and flask. Facial expressions are the vital identifiers for human feelings, because it corresponds to the emotions. Most of the times (roughly in 55% cases), the facial expression is a nonverbal way of emotional expression, and it can be considered as concrete evidence to uncover whether an individual is speaking the truth or not.

⛳ Our Facial Expression Recognition Classifier Model can take input via following ways : 👇

sad
![Screenshot 2024-08-23 162251](https://github.com/user-attachments/assets/1b5a27ff-a57f-409b-8730-5b1fa176d18e)

angry
![Screenshot 2024-08-23 162304](https://github.com/user-attachments/assets/1be5cdc9-001b-44a1-875a-bf3f0a15bf19)

happy
![Screenshot 2024-08-23 162317](https://github.com/user-attachments/assets/e7a07588-24be-4c51-91b2-6664c407fb00)

It predicts the Emotion of users and also gives Graphical Visualization of Emotions as shown above.

➿ Tech Stack used 👇

Python

Flask

HTML, CSS

Deep Learning (CNN)

💥 Getting Started: Steps to run the Project in your local device !!

Fork this repository.

Clone the repository to your System using  git clone

Example : git clone https://github.com<your-github-username>/Facial-Expression-Recognition-Classifier-Model
Create a new Virtual Environment with python 3.7.0 version.
Install all the dependencies with pip install -r requirements.txt.
Now run the main.py file.
Once it shows Running on http://127.0.0.1:5000/ go to http://127.0.0.1:5000/ in your browser.

💻 Coding Structure:

Import the required Packages and Libraries.

Data analysis and Creating Training and Validation Batches.

Create a CNN using 4 Convolutional Layers including Batch Normalization, Activation, Max Pooling, Dropout Layers followed by Flatten Layer, 2 Fully Connected dense Layers and finally Dense Layer with SoftMax Activation Function.

Compile the model using Adam Optimizer and categorical cross entropy loss function.

Training the model for 15 epochs and then Evaluating the model as well as saving the model Weights in .h5 Values

Saving the model as JSON string.

Creating a Class in a separate file to reload the model and its weights to make predictions and return the probabilities of each emotion.

Creating one more class in a Separate file which takes in the Real-time Video input and returns frames of Images with a Circle detecting the face and putting text of its emotion on it.

A python script is also created which upon running yields the Graphical Visualization of Emotions present in the Image provided.

Finally creating a file which inherits form all the Classes defined by us and deploys our application using Flask.

![Screenshot 2024-08-23 163059](https://github.com/user-attachments/assets/38ff51f1-1a03-4127-86cd-de0e41588546)

