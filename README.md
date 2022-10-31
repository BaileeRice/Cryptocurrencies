# Cryptocurrencies

![image](https://user-images.githubusercontent.com/105184244/198962707-0ef5bfee-50d5-44e4-aa44-11b558aef19d.png)

## OVERVIEW

Creating a cryptocurrency investment report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system using an unsupervised machine learning model.

## PURPOSE

Helping a hypothetical investment bank offer a crypto-focused portfolio for its customers. 

## OUTLINE

Part 1: Preprocessing the Data for PCA

- read in file

- remove columns with unnecessary data for unsupervised learning

- get rid of nulls

- remove untradable coins

![image](https://user-images.githubusercontent.com/105184244/198968149-f3b67ad7-5568-411a-b60d-88b7763fba30.png)



Part 2: Reducing Data Dimensions Using PCA

- assigning the new data to 3 different components

- create a PCA DataFrame

![image](https://user-images.githubusercontent.com/105184244/198968350-9f8439c4-6db3-4364-9e4a-0b51c8df6d46.png)


Part 3: Clustering Cryptocurrencies Using K-means

- use KMeans to cluster the crypto data

- print predictions made by the model

![image](https://user-images.githubusercontent.com/105184244/198969478-4ceb8d58-2bb7-43d2-824a-25168c97c8f8.png)

-add predictions to original data

- create an elbow curve

![image](https://user-images.githubusercontent.com/105184244/198968724-c397ea6f-9b7b-4b27-837b-17e135f14ef0.png)


Part 4: Visualizing Cryptocurrencies Results

- create a 3D and 2D scatter plot

- count all the currently available cryptos

![image](https://user-images.githubusercontent.com/105184244/198970216-53a5b203-ba04-49af-bcc7-456878b466f7.png)

![image](https://user-images.githubusercontent.com/105184244/198970512-e2c52272-754c-423a-8db4-b351f5a17cc8.png)

![image](https://user-images.githubusercontent.com/105184244/198970312-377fba7d-96af-448d-8238-4c081eb69d0a.png)
