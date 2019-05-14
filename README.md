# Mexican-Food-Classifier

<img src="https://cdn-images-1.medium.com/max/800/1*NOMqw1SqCxsnFHz_VA0I5w.jpeg">

Mexican cuisine is one of the most popular ones in the world. Being from Mexico, I’ve been lucky to taste, which I consider, one of the best cuisines in the world. You don’t need to go too far away to find a good spot and try different kind of tacos! You can find great food just walking by the streets. You should visit Mexico and enjoy these little things.

Stop by your local Mexican restaurant and you’ll probably find sky-high piles of nachos smothered in cheese and colossal fishbowl margaritas. But true Mexican food couldn’t be more different.

I have the idea to develop an AI app than can classify different types of mexican food and even give you the recipe to make it by your own! The goal of "TeAmole" is to classify 9 types of mexican mexican food by looking a picture.

This project idea came to my mind because it can help to the tourism sector in Mazatlán, Mexico. Tourists can take pictures of the food they are getting and identify what are them and even get a recipe! By doing these, we are promoting the food made in Mexico and helping the tourism sector by bringing more  interested people to visit our beautiful town!

<B> Working on a "Mexican Food Dataset" </B>

I used the Google Images Download library.  A Python Script for 'searching' and 'downloading' hundreds of Google images to the local hard disk!. You can use this library with the following instruction2:

```
pip install google_images_download`

from google_images_download import google_images_download   #importing the library

response = google_images_download.googleimagesdownload()   #class instantiation

arguments = {"keywords":"Polar bears,baloons,Beaches","limit":20,"print_urls":True}   #creating list of arguments
paths = response.download(arguments)   #passing the arguments to the function
print(paths)   #printing absolute paths of the downloaded images
```

I collected images using this library and uploaded a food dataset to Google Drive.

This app will identify 9 different kind of mexican food dishes:

- Aguachile
- Callos de Hacha
- Ceviche de Camarón
- Ceviche de Sierra
- Chilaquiles
- Coctel de Camarón
- Tacos Gobernador
- Pozole
- Pescado Zarandeado

**Aguachile**

![alt text](https://cdn.kiwilimon.com/recetaimagen/28638/th5-640x426-28924.jpg)

If you love ceviche, then Mexico's Shrimp Aguachile is for you. Traditionally made with raw shrimp, lime juice, chilies, cucumber, and onion, it's served immediately while still totally raw, unlike most other ceviche recipes. This dish is very popular in  Sinaloa, México, and it's unbelievably delicious given its simplicity.

**Callos de Hacha**

![alt text](https://media-cdn.tripadvisor.com/media/photo-s/07/bc/af/dd/la-unica.jpg)

Callos de Hacha or scallops is a typical dish of the Pacific coast of Mexico. This delicious dish is very popular in places like Sinaloa, Nayarit, Sonora and Baja California. Some call it a "delicacy of raw seafood lovers". Many also say it’s a great way to get rid of a hangover after a big celebration. The main ingredients are scallops, fresh or dried chilies, lemon and water. There are also versions in which fresh vegetables are added. I hope you enjoy this delicious Mexican dish.

**Ceviche de Camarón**

![alt text](http://3.bp.blogspot.com/-BB3BRzokZcw/VAaI_KBSBZI/AAAAAAAAAgc/678dNCx9cko/s1600/ceviche_camaron.jpg)


Shrimp Ceviche is very popular in the Pacific coast region, especifically, Mazatlán. Ceviche features raw fish and seafood marinated and cured in citrus juices like lemon or lime. This process “cooks” the fish much like preparing it with heat, giving it a firm texture. Other ingredients include fresh cucumbers, tomatoes, celery, onions and corn, seasoned with cilantro, chile or other bold spices. This tasty dish is both filling and pleasing to the palate.

**Ceviche de Sierra**

![alt text](https://mazatleco.com/wp-content/uploads/2014/08/Ceviche-de-sierra-mazatleco.jpg)

This ceviche is typical of Mazatlan, Sinaloa Mexico. It's called Ceviche de Sierra over there; Sierra is just another name for Spanish Mackerel. We prepare this fish by cooking it with the acidity of lime juice. Perfect for hot days!

**Chilaquiles**

<img src="https://www.cocinavital.mx/wp-content/uploads/2017/11/chilaquiles-rojos-paso-a-paso.jpg">

Chilaquiles are a breakfast staple in Mexico. There are red chilaquiles and green chilaquiles, depending on the type of salsa that you decide to make. Chilaquiles start with a bed of freshly made corn tortilla chips, which can be either baked or fried.

**Coctel de Camarón**

<img src="https://cocina-casera.com/mx/wp-content/uploads/2017/11/campechana.jpg">

Coctel de camarones, or Mexican shrimp cocktail. I love this version of shrimp cocktail, it’s sort of like a virgin Bloody Mary with cucumber, celery, red onions, avocados and lots of shrimp. Perfect for dipping, or eating with a spoon. Or picking out the shrimp pieces with a fork, then the avocado pieces, and then eating the rest with a spoon as if it were gazpacho.

**Tacos Gobernador**

![alt text](https://www.cocinavital.mx/wp-content/uploads/2017/08/tacos-gobernador.jpg)

These Tacos Gobernador are the perfect crispy cheesy shrimp tacos you will ever come across. These Tacos Gobernador translates to Governor’s Tacos and they are just hyper-delicious. These are cheesy shrimp tacos folded in between a crispy corn tortilla with all the toppings. I promise these tacos will just make you happy every time you make them. Poblano peppers strips, thinly sliced onions, juicy sweet tomatoes, serrano pepper and garlic cooked with shrimps and then laid on top of deliciously melted cheese in between a corn tortilla that is perfectly pan fried in butter. Oh!  And the serrano pepper offers the perfect hint of spiciness you will love.

**Pozole**

<img src="https://obson.files.wordpress.com/2013/02/receta-pozole.jpg">

Pozole, which means "hominy", is a traditional soup or stew from Mexico. It is made from hominy, with meat, and can be seasoned and garnished with shredded cabbage, chile peppers, onion, garlic, radishes, avocado, salsa or limes. Pozole is typically served on New Year's Eve to celebrate the new year.

**Pescado Zarandeado**

![alt text](https://www.diariohispaniola.com/fotos/1/Pescado-a-la-Talla-Acapulco.jpg)

Mexican Style Grilled Fish (Zarandeado) is a  whole fish, marinated with lime & chilies then grilled over charcoal. It's very popular in Sinaloa.

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
