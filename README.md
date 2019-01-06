# Mexican-Food-Classifier

<img src="https://cdn-images-1.medium.com/max/800/1*NOMqw1SqCxsnFHz_VA0I5w.jpeg">

Mexican cuisine is one of the most popular ones in the world. Being from Mexico, I’ve been lucky to taste, which I consider, one of the best cuisines in the world. You don’t need to go too far away to find a good spot and try different kind of tacos! You can find great food just walking by the streets. You should visit Mexico and enjoy these little things.

Stop by your local Mexican restaurant and you’ll probably find sky-high piles of nachos smothered in cheese and colossal fishbowl margaritas. But true Mexican food couldn’t be more different.

I have the idea to develop an AI app than can classify different types of mexican food and even give you the recipe to make it by your own! The goal of "TeAmole" is to classify 9 types of mexican mexican food by looking a picture.

This project idea came to my mind because it can help to the tourism sector in Mazatlán, Mexico. Tourists can take pictures of the food they are getting and identify what are them and even get a recipe! By doing these, we are promoting the food made in Mexico and helping the tourism sector by bringing more  interested people to visit our beautiful town!

I'll train this image classifier to recognize 9 different mexican food dishes given an image.This can be implemented in a phone app that tells you the type of food your camera is looking at.


<B> INSTRUCTIONS </B>

The project is broken down into multiple steps:

* Load and preprocess the image dataset
* Train the image classifier on your dataset
* Use the trained classifier to predict image content

Everything you need to recreate this project is on the jupyter notebook. Everything was coded in Google Colab, because of its GPU. I uploaded the dataset to Google Drive, so you can download it directly (the code to download it is in the notebook). For more details, the notebook includes the instructions to follow.

If you want to load the trained model, the code to download it, is in the notebook, in the "Load the checkpoint" section. I uploaded the model to my Google drive because it's bigger than 200MB.

This project is updated to be compatible with PyTorch 0.4.0

Read more about this project on my blog: https://medium.com/@viritaromero/revolutionizing-the-field-of-dining-in-mexico-teamole-app-e9ae160df4b8


There are already some projects implementing the same idea, using the FOOD-101 dataset, which contains more classes. You can read a paper implementing the same idea here: https://arxiv.org/ftp/arxiv/papers/1612/1612.00983.pdf
