# second-data-science-project
## first part: Fashion Mnist 
In this part of the project we were required to identify images of clothes by using pixels. 

So in order to reduce the problem we used PCA so that instead of processing 784 pixels it processed only 100.

To predict the clothes in the testing set we used different algorithms:

simple models like KNN , logistic regression, SVC.. 

and some ensemble learning models like voting classifier, random forest and adaBoost.

## second part : hand state recognition

The purpose of the work is to classify between three different situations in the way people communicate with each other. The first is a spontaneous (autonomous) situation in which two people move their hands freely in front of each other. The second is a synchronous movement in which the two people move their hands together and the third is a movement in a single position.

The idea is to look at the patterns of the hands and try to deduce from them whether it is a situation alone, spontaneous or synchronous.

In this part we get multip datasets (each one is a record of one state using a 3D camera ), so first we united the datasets into one. 

for each dataset we took all 5 lines of recording data and combined them into one line and ignored the first 7 second. 
