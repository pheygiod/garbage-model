# garbage-model
Training my first Convolutional Neural Network model to predict the material of garbage and improve waste sorting! ♻️ 

# Table of Contents
- General Info
- Setup
- Usage
- Project Status
- Room for Improvement
- Acknowledgements
- Contact

# General Information 
I’m uploading my code of the model I trained as part of a Tech Festival at work!💻 The task was to build an app of an image classifier and come up with a business idea to use it. We chose to build a model to assign the right label to garbage waste!♻️🌎 With this initiative we want to support fast, efficient, and correct decision-making processes when recycling💪. I built the model and my colleagues worked on the user interface of the app and the proposal of the business case. I’m sharing my code here for you to reuse it and train your own model!♻️

The model I trained is based on a Convolutional Neural Network. We extracted the dataset from [Kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification), and it is made up of 2,467 images of 6 labels: cardboard, glass🍷, metal🤘, plastic, paper📰, trash. We trained the model on 80% of it, validated it on 10%, and tested it on the remaining 10%.

# Setup
First off, make sure you have conda🐍👀:

`conda create -n <replace-with-name-you-want> python=3.11`

`conda activate <replace-with-name-you-want>`

Then, pip install these libraries📒🎁:
- torch
- torchvision
- tensorboard
- datasets
- scikit-learn
- matplotlib
- seaborn
- tqdm
- ipywidgets
- jupyterlab

# Usage 
Check out the ipynb files in my repo to see how I've processed the data, built, and trained the model!

- data_processing.ipynb🎰 
- garbage_cls.ipynb📷

# Project Status
The first time we trained the model we got very bad results. Accuracy was scoring at around 0%! So we tried to change the parameters and train the model again to check if we could get better results. After changing our choices of the architecture, the model started improving! The best version of the model is the one where we shrank the size of the images and the model trained with a small learning rate for more epochs. As a result, we went from almost 0% to approximately 62% accuracy! 

# Room for Improvement
Despite making a big jump with our accuracy score, there’s still a lot of room for improvement. Here’s what we could do to increase the model’s level of accuracy. First off, we could train the model on bigger and more diverse dataset. We could also train bigger models with more layers! We were also thinking of training the model with some background noise (e.g., a picture of a hand holding a plastic bottle with a bin in the background, a table, or people walking by).

# Acknowledgements
Big kudos to Vlad Vaculin for rocking the user interface of our app. Seriously, Vlad, you're the UI wizard we didn't know we needed!

A massive thank you to Dagmara Prus for weaving her magic with the business case. Her strategic mind and attention to details gave our project the kickstart it needed!

Last but not least, a special shoutout to Ward Haddadin for being the backbone of our tech journey! Ward, your help in preparing a tutorial to learn how to use convolutional neural networks has been invaluable. 

Working with this crew has been an absolute blast. And guess what? Thanks to our teamwork, we bagged the first prize at the Tech Festival for the best effort and best app! Here's to more victories together!!

# Contact
For any question, drop me a line at giorgiadt14@gmail.com and I'll be happy to help you out! Feel free to message me on [LinkedIn](https://www.linkedin.com/in/giorgia-dim/) too!