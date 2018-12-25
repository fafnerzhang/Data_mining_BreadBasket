Group member:徐梓恩 410421251
             張宇宏 610721224
# Introduction
environment: Juptyer notebook.

Code in [Data_nining_BreadBasket.ipynb](https://github.com/fafnerzhang/Data_mining_BreadBasket/blob/master/Data_mining_BreadBasket.ipynb/)

We using pandas and mlxtend to extract the data .
Also using sklearn's naive bayes to solve problem 2. 
# Problem 1
**1. the discussion of the dataset**
In this dataset we have 9684 transaction and 95 different items.
It also shown in the code.
![](https://i.imgur.com/5tcKEE2.png)
But it contain None item(empty item) , we have to remove None item from this dataset.

We actually have 9465 transcation and 94 different item in our dataset.
Also can visualize the most sold item.
![](https://i.imgur.com/NXOwaCv.png)



**2. the method you used to mine the frequent itemsets (in detail)**
We using apriori method to mine the frequent itemsets.

**3. list the frequent itemsets**
It shown in the code.
**4. discussions or comments**


# Problem 2
**1. Explain the idea and method you propose (in detail)**
We using sklearn's naive bayes to extract the dataset 
1. Remove "Bread" from dataset,Transfer it to predict label(y_train)
2. Import bayesian to build the model 
3. Apply dataset(without "Bread") as x_train,"Bread" as y_train to train the model
4. Apply the input , predict whether the customer will buy the "Bread" .

**2. Write an example to illustrate the method**
It shown in the code. 

We made test it can show both buy "bread and not buy "bread"

**3. discussions or comments**
This assignment is very practical.
We spend lots of time to servey how to using the extracting tool.
It also improve our learning of data mining by practicing.
