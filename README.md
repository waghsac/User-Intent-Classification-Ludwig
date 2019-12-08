# User-Intent-Classification-Ludwig
This repository contains ipython notebook and associated files to demonstrate how to classify user intent using machine learning. The model is trained on a curated dataset using deep learning using Uber's Ludwig.

<b>Background on the intent classification use case</b>:

Most businesses in recent times have online presence as more and more people search and buy products  or services through  online  channels.  With  steep  competition  it has  not only  become
mandatory to  have  online  content but also to  optimize  it in  a way that it reaches the target customers/buyers and ensures that all the desired market segments are reached out.
In order to achieve this, understanding the science behind why is a user searching for a particular keyword or in other words understanding the user intent is utmost critical.

Let us also understand the lifecycle journey of a buyer to understand user search intent better.

![alt text](https://github.com/waghsac/User-Intent-Classification-Ludwig/blob/master/02.PNG)

<b> Why Ludwig? </b>

![alt text](https://github.com/waghsac/User-Intent-Classification-Ludwig/blob/master/03.PNG)

<b> The dataset sample and yaml config file </b>

Ludwig only requires yaml config file to be configured correctly alongwith the dataset for building the model. For this exercise I have used Google colab as it provides us with GPUs without any cost. GPUs are required for LUdwig as it uses TensorFlow underneath.

![alt text](https://github.com/waghsac/User-Intent-Classification-Ludwig/blob/master/04.PNG)

<b> Output Sample and Observations </b>

![alt text](https://github.com/waghsac/User-Intent-Classification-Ludwig/blob/master/05.PNG)

<b> Conclusion </b>

Ludwig is a really good tool to carry out quick experiments to ensure that the use case is feasable and enables us to focus on data quality more wihtout spending too much time on model building. It is not suitable for simplistic use cases though as it uses TensorFlow that needs a fairly heavy kit to run with GPUs. 



