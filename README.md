# Project: Exploratory and predictive analysis in the Titanic Data Set.
 
* First we will address the relevant variables to classify the survival of a passenger on the Titanic. Then a pre-processing will be done that will be divided into:
 
     * Descriptive analysis.
     * Outliers.
     * New variables.
     * Selection of variables, for the training of our models.
     
 >_**Note:**_ In this readme only the results will be shown, for more details see the code in the code folder of this repo.
 
From the previous post steps, we will show how they are correlated with each other, and to move on to modeling:
 
![1](https://user-images.githubusercontent.com/63415652/103332391-5bdc1380-4a2f-11eb-8dce-d5a2c0df0fcf.PNG)
 
>**_Conclusion:_** Here we can see that the lowest value of the correlation is for the darkest values and the highest for the lowest.
 
---
 
Now since it was done in exploratory analysis, we will move on to **predictive analysis.**
 
For this case we will use 2 models to measure the precision of each one, we are faced with a classification problem, so we will use logistic regression and decision trees.
 
The objective of this classification is to determine the number of survivors and for this we will use all the other remaining variables such as age, the number of relatives, their sex, etc.
 
Now we will see which is the best model to predict our classification:

![6](https://user-images.githubusercontent.com/63415652/105923992-00d41700-6003-11eb-9a40-ae4d830bef16.PNG)

And the model that gained in precision was logistic regression.
 
And finally, some relationships of the variables with which he made the production:
 

![9](https://user-images.githubusercontent.com/63415652/105924018-0f223300-6003-11eb-8e88-5024a47d6b6c.PNG)
![7](https://user-images.githubusercontent.com/63415652/105924007-09c4e880-6003-11eb-8567-f77c635cf0b2.PNG)
![8](https://user-images.githubusercontent.com/63415652/105924010-0c274280-6003-11eb-92df-ff171fe4b3a8.PNG)

 
>**_Conclusion:_** Where you can notice an abysmal difference is in sex, since at the time to board the emergency boats they prioritized a lot "women and children", most of the men, and especially of the third class, were left on the Titanic until its sinking.
