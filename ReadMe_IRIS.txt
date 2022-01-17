Iris_Readme -

In this assignment I took Fischer's Iris data set - 
the data set contained 150 samples of
three different types of Iris flowers (virginica, versicolor,setosa)- 50 of each.
The measured feutres of each sample were length and width of the sepals and petals in centimeters.
with the Jupiter notebook tool and the help of Sklearn library API and examples 
I classified the data set with two different classifiers -
PCA (Principal Components Analysis) and LDA (Linear discriminant analysis) - 
The classification can be seen in the presented plots after running the added Jupiter script.

From the plots we can learn that each method have her own accuracy and it can vary depends on the data set and number of dimensions.
In this case the LDA method is better to use, we can see that the seperability between the plot samples of is more coherent.
(the diffrence can be seen if comparing the versicolor and virginica plot samples of the two methods)
LDA is like PCA but it focuses on maximizing the seperability among known catagories,
while PCA reduces dimensions by focusing on the catagories with the most variation.
clearly for the Iris data set LDA is more suitable than PCA

Yoav Hovev