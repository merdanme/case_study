# Data Analysis Exercise

In this repository, the visitation of several stores in Germany made by users, given GPS signals of users, and outline of the stores (referred to as polygons) is analyzed. Besides, the demo-behavioural relationship between user affinities and specific stores they have visited is explored. 

All the necessary installations are included in the "code.ipynb" Jupyter notebook file. Once downloaded the datasets, the code could be run on Anaconda or Colab. 

## Unique Store Visits

The visualizations of unique store visits over time, by store name and store id are showed below. 

**Here are some remarks from the graphs:**
- The trend shows that the most visits happen on Sundays, that could be understandable considering that most stores are actually closed on Sundays.
- The most visited store chain is Kaufland, followed by Rewe.
- The least visited store chain is Subway.
- The most visited store is place 214, followed by place 217 - both being Kaufland stores.
- On January 1, which is a public holiday, McDonald's is the most visited store helping hungry, probably hungover users to start the new year.

![Unique Store Visits Over Time colored by Store Name](https://user-images.githubusercontent.com/57150723/110855868-3b45fa80-82b7-11eb-9624-b87bb7061a60.png)
![Unique Store Visits Over Time colored by Store ID](https://user-images.githubusercontent.com/57150723/110855907-4436cc00-82b7-11eb-9505-5f4fb6542828.png)
![Unique Store Visits by Date](https://user-images.githubusercontent.com/57150723/110855914-46008f80-82b7-11eb-972f-1402d8d7a920.png)
![Unique Store Chain Visits by Date](https://user-images.githubusercontent.com/57150723/110855918-47ca5300-82b7-11eb-8c22-c4f05913b6d7.png)

## Visualization of GPS data
The location of GPS signals of users in the sample data is visualized below. It locates around Berlin. The shape of all the GPS signal points makes up a hexagon.

<img width="307" alt="hexagon" src="https://user-images.githubusercontent.com/57150723/110856125-87913a80-82b7-11eb-9155-8b4f066e618a.png">

## Visualization of store data
The shape of the first two stores are drawn below. Both are McDonald's stores of located in different buildings.

<img width="314" alt="place_1" src="https://user-images.githubusercontent.com/57150723/110856268-b90a0600-82b7-11eb-83e9-b2e352814bea.png">
<img width="449" alt="place_2" src="https://user-images.githubusercontent.com/57150723/110856279-bad3c980-82b7-11eb-82a8-55988f09452a.png">

All the stores in the stores dataset are pointed in the coordinates below. 
<img width="631" alt="stores" src="https://user-images.githubusercontent.com/57150723/110856405-e22a9680-82b7-11eb-91f4-202823dcfde1.png">
