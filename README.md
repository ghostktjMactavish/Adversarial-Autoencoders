# Adversarial-Autoencoders
My Summer 2019 research study on Open World Classification under Prof. Nikhil R. Pal, ISI Kolkata.
# Summary of the Study
Most classification models are made by making an assumption that we already know all the classes of the data. This assumption is called the closed set assumption but this assumption does not hold very well in real life. Nature never ceases to amaze us and we may get a data point that does not belong to any of the classes that we have assumed our data falls in. What does our model predict when it encounters a class? It has been found that most classification models do not work well for these type of data and produce highly erratic output. This is the Open World Classification problem. In an ideal case we would like our model to say that it does not know anything about this new data. But how do you make your model say "Don't Know" without having access to this new data? 

In our study we propose an adversarial autoencoder approach to identify this open world data. For more details read the report titled Open World Classification in my repository.
