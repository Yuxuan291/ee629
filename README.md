# IoT Project: Decision Tree Model in Python


This topic is a simple implementation of the decision tree model in machine learning by the use of Python package (sklearn and graphviz). The idea of this project is originated from the experience of modeling and simulation class this semester. So I combine the modeling tool and Python coding of IoT context to implement this project. This is an analysis of the survivors in Titanic accident, by using the machine learning tools and appilication of decision tree model, the relationship between the probability of survivor and related factors will be obtained. And then, the validation approach will be used to optimize the result of the decision tree model, the model will be also verified by the relative accuracy and be tested by the rest of the data. 

In order to collect the useful data, I searched online and find this source https://www.encyclopedia-titanica.org/titanic-passenger-list/. There are the information of 1350 passengers on Titanic, which is saved in the file (Titanic. csv). basing on this source, the characteristics of the victims and the survivors will be further analyzed through machine learning. 

The detail of processes in this project is listed below:

* Select the part of the data that is suitable for machine learning analysis; 

* Remove the meaningless data in each label;

* Divide the data into training data and test data, and import them into the tree_decision tree function to obtain a decision tree model;

* Use cross‐validation to find the best parameter to prune the tree;

* Optimize the model through the above methods, and use the remaining data to test the model;

* Show the final decision tree results and the accuracy of the results after model optimization.

This is the decision tree model.

![image](https://github.com/Yuxuan291/ee629/blob/main/Decision%20tree%20model.png)

This is the optimal tree size chart.

![image](https://github.com/Yuxuan291/ee629/blob/main/Optimal%20tree%20size%20diagram.png)

This is the final result of accuracy of this model.

![image](https://github.com/Yuxuan291/ee629/blob/main/Accuracy.png)

The purpose of this model is to illustate the internal relationship of several parameters to the desired variables. In this case, the decision tree model shows the connection of the class, sex, age, number of offsprings. We can find the clue through those four labels to obtain the possibility of survivor or fatality in specific case. The apply of machine learning helps the analysis to achieve a better fitness in reality.
