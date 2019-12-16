# Portfolio Santiago Puertas Puchol
# Dwelling Energy Insights


**DataCamp course**
1. DataCamp Course completion. 
	* I have completed a total of 7 datacamp courses that have helped me to better understand data preprocessing, dataframe 	processing and data visualization
	![Image of datacamp1](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp1.png)
	![Image of datacamp2](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp2.png)
	![Image of datacamp3](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp3.png)

**Reflection and evaluation**
1. Reflection on own contribution to the project.

2. Reflection on own learning objectives.

3. Evaluation on the group project as a whole.


____
**Research project**
1. Task definition
	* Research question: Can we go insight the energy consumption in Netherlands?
	* This project tries to go inside the electrical consumption of the Netherlands houses. We have used the information provided by smartmeters placed in a neighborhood(Mient) of 33 houses in The Hague(Netherlands). The objective is to know what type of heating system the houses have installed, how many people live in a house and how many solar panels have installed. The dataset we have used contains data on electricity consumption and energy delivery to the network. We do not know the exact production of solar panels if a house is using this energy and does not deliver any surplus to the network. The data stored by the smartmeters measure information every 5 minutes and stores it every 15 minutes. The data is basically the total consumption and energy delivery of each house every 15 minutes. This whole study is intended for future policy decisions

2. Evaluation
	* The results obtained by the recurrent neural networks give us the guarantee that it is possible to determine what type of heating installation a house has installed, how many people live in that house or how many solar panels have installed. In the near future, when smartmeters are mandatory in all Netherlands, the models presented here can be trained with a greater variety of data and thus improve predictions

3. Conclusions
	* We have tested 4 different routes in order to predict and classify the data of each house.
	* LSTM (Long short-term memory): This type of recurrent neural network is the one that has provided the best predictions.
	* K-NEAREST (K Nearest Neighbor): 
	* SVM (Support vector machine): 
	* LOGISTIC REGRESSION: 

4. Planning
	* The project has been carried out using the SCRUM work methodology
	* Trello is the web tool we have used to update all the progress as well as its planning


____
**Predictive Analytics**
1. Selecting a Model
	* _HS= **H**eating **S**ystem_
	* _NP= **N**umber of **P**eople_
	* _SP= number of **S**olar **P**anel_
- ### LSTM

	- [Predicting Heating System](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20Heating%20system.ipynb): 95.5% accuracy result when predicting the type of heating system. 
	- [Predicting Number of People](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20People%20v2.ipynb): 87.5% accuracy result when predicting the number of people living in a house. 
  	- [Predicting Number of Solar Panels](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20Solar%20panelsV2.ipynb): 80.5% accuracy result when predicting the number of solar panels installed in a house

- ### K-NEAREST
	
	- [Predicting Heating System](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/K-Nearest%20Neighbors/K-Nearest%20Neighbors.ipynb): 64.5% accuracy result when predicting the type of heating system. 
	- [Predicting Yes or No classification](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/K-Nearest%20Neighbors/K-Nearest%20(Focusing%20on%20one%20Type).ipynb): 
 	- [Predicting HS, NP, SP](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/K-Nearest%20Neighbors/Best%20Results.ipynb): 37.5% accuracy result when predicting the number of people living in a house.  53.5% accuracy result when predicting the number of solar panels installed in a house
 


- ### SVM

	- [Predicting Heating System](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Support%20Vector%20Machine/SVM%20implementation%20for%20Type%20of%20Heating%20System%20with%20KNMI%20data%20(per%20day).ipynb): 61.5% accuracy result when predicting the type of heating system. 
	- [Predicting Number of People](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Support%20Vector%20Machine/SVM%20implementation%20for%20Number%20of%20Persons%20with%20KNMI%20data%20(per%20day).ipynb): 43.5% accuracy result when predicting the number of people living in a house. 
  	- [Predicting Number of Solar Panels](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Support%20Vector%20Machine/SVM%20implementation%20for%20Number%20of%20Solar%20Panels%20with%20KNMI%20data%20(per%20day).ipynb): 38.5% accuracy result when predicting the number of solar panels installed in a house



- ### LOGISTIC REGRESSION

	- [Predicting HS, NP, SP](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Logistic%20Regression/Logistic%20Regression%20Without%20data%20from%205%20houses.ipynb): 55.5% accuracy result when predicting the type of heating system. 27.5% accuracy result when predicting the number of people living in a house. 38.5% accuracy result when predicting the number of solar panels installed in a house


2. Configuring a Model
	* The model that has finally given the best predictions has been the LSTM, with an architecture of an input recurrent layer of 30 neurons, a dropout and a final perceptron simple layer with 3 neurons (the number of outputs neurons depends on each prediction)

3. Training a model
	* The best results have been achieved with a learning rate of 0.003 and between 50 and 60 epochs

4. Evaluating a model

5. Visualizing the outcome of a model (explanatory)
	* Barplot comparing each model with each other
	![Image of results1](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/results1.png)
	
	* Precision comparison
	![Image of results2](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/results2.png)


____
**Domain knowledge**
1. Introduction of the subject field
2. Literature research
3. Explanation of Terminology, jargon and definitions


____
**Data preprocessing**
1. Data exploration
2. Data cleaning
3. Data preparation
4. Data explanation
5. Data visualization (exploratory)


____
**Communication**
1. Presentations 
2. Writing paper
