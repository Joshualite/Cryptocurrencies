# Cryptocurrencies

This is a fictitious job for a company and it is carried out from unsupervised machine learning models, the main objective is to be able to classify cryptocurrencies as best as possible to be able to make a portfolio of these coins and be able to offer them to clients.

The project is divided into 4 phases, the first basically is the loading of the database with which it is going to work and with this a data cleaning is carried out to be able to apply the model, the database has to be prepared and With this you have to remove some variables, filter the information, remove the null values ​​and normalize the data so that the information can be worked on.

![image](https://user-images.githubusercontent.com/66183125/152703501-0dc0e355-8579-4274-9cf3-37e83b11e76a.png)

The second phase consists of applying the PCA method to be able to reduce the total dimensionality of our database to be able to keep only the 3 most important variables.

![image](https://user-images.githubusercontent.com/66183125/152703443-1f5bfb5d-1efb-4cf3-ae3e-14c2da7de191.png)

For the third phase we can start modeling, the unsupervised model that was chosen was KMeans, which will help us to classify cryptocurrencies, but the question is in how many categories can we classify coins, and to know this we will have to apply the elbow method, which depending on the graph as soon as the improvement ceases to be a curve and shows more of a linear advance, that is where we have to choose how many categories or in this case clusters we must apply the model, as we can see in the graph the best option to choose are 4 clusters, from there we proceed to train the model and we also predict the classification of each cryptocurrency

![image](https://user-images.githubusercontent.com/66183125/152703336-df943415-9bb6-405b-a750-d570b17034e0.png)

![image](https://user-images.githubusercontent.com/66183125/152703620-123e1069-654e-491f-998b-73e12f7bdc5f.png)

In the fourth phase, we basically focused on visualizing the information we already have about cryptocurrencies to see how they were classified in a three-dimensional and two-dimensional way.

![image](https://user-images.githubusercontent.com/66183125/152703798-95882c5a-8569-4748-a43a-10e7f0355a83.png)


![image](https://user-images.githubusercontent.com/66183125/152703420-ce4ef3ef-86ac-49e3-8316-ade073a29664.png)

