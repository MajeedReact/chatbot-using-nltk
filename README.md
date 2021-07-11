# chatbot-using-nltk
Creating a simple deep learning Arabic chatbot using NLTK libraries and TensorFlow as well as Flask

# Requirements
 - Python v2.7 or version 3.9
 - Miniconda
 - TensorFlow
 - Flask
 - NLTK
 - Pickle
 - Keras

# Installation

1. Install [Python](https://www.python.org/downloads/) with the supported version mentioned in the requirements. 
2. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) make sure python version is compatible. 
3. After installing Miniconda search anaconda prompt from windows search bar. 
4. In Anaconda terminal install TensorFlow by running: `pip install tensorflow`.
5. After that install NLTK library by typing: `pip install NLTK`.
6. In the same terminal install Keras `pip install Keras`.
7. Install pickle `pip install pickle`
8. And finally install flask to host the bot on the web: `pip install flask`



# Training 

1. Open python IDE create a project and git clone this project.
2. Take a look at data.json file and add more intents.
3. Run training.py from python IDE and you should have similar result to this:

![result-of-training-2](https://user-images.githubusercontent.com/53359513/125202399-18831d00-e27c-11eb-84f0-ef9b89aeec8f.jpg)
*Note you can edit the number of Epoch to add more training*

# Running Flask
 
 1. Navigate to app.py and run it from the IDE
 2. Go to your browser and type the following host: http://127.0.0.1:5000/
 3. You will be prompt with a chatbox and the bot.

# Results

![conversation-result](https://user-images.githubusercontent.com/53359513/125202638-1e2d3280-e27d-11eb-8799-607373a660fa.jpg)

