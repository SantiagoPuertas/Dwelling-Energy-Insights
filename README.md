# Portfolio Santiago Puertas Puchol
# Dwelling Energy Insights

**DataCamp course**
1. DataCamp Course completion. 
	* I have completed a total of 7 datacamp courses and 31 chapters that have helped me to better understand data preprocessing, dataframe 	processing and data visualization
	![Image of datacamp1](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp1.png)
	![Image of datacamp2](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp2.png)
	![Image of datacamp3](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp3.png)
	![Image of datacamp4](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp4.png)
	

**Reflection and evaluation**
1. Reflection on own contribution to the project.

* [TSNE](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Visualizations/TSNE%20Kmeans%20K-Nearest.ipynb) 

	* I have created the TSNE script with the purpose of being able to have a clearer view of the data and possible patterns before starting to create machine learning models, as well as neural networks. In the same way, within the script itself I have created a preliminary version to the final of kmeans and k-nearest in order to be able to better adjust the values and have a better approach to this type of technique.



* [Outliers by maximuns](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Cleaning%20data/outliers%20by%20maximuns.ipynb)

	* On the other hand, I have also done cleaning scripts to be able to have a list of outliers in order to have a list of ouliers and thus be able to analyze them in order to better understand the dataset. 

	* Using the following formula: max_production = (75 * 230) / 4000 I have been able to find outliers. 
75 amps * 230 volts divided by 4 (because each row of data is every 15 minutes) and multiplied by 1000 to convert it to KW




* [Maximun electricity](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Visualizations/Maximun%20electricity%20current.ipynb)

	* Maximum electricity current (amps) that enter and exit each house, as well as in total have also been carried out independently. The objective of making these graphs is to understand if the houses between them would be able to be self-sufficient by connecting with each other and thus be able to create a network between them. In this way we would achieve the almost independence of power plants, that is, when a house produces more than it consumes, instead of pouring it into the grid and losing it, being able to share that energy with other houses.



* [Visual clasification](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Visualizations/DOOR'S%20Visual%20Clasification.ipynb)

	* Visual clasification of consumption and delivery of each house to detect possible patterns.



* [Kohonen](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonen.ipynb)

	* Kohonen map to classify each house in an unsupervised way and to establish the first patterns between houses with the same type of heating, number of people or number of solar panels


* [Kohonen visualitations](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonenen%20visualitation.ipynb)

	* 3D Kohonen visualitations to get acces to the entire data plot



* [MLP](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/MLP_FINAL.ipynb)

	* MLP (multi layer perceptron) used in the first versions of the algorithms to try to predict the possible classes of houses (heating system, number of solar pannels, number of people)


* [LSTM](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/RNN_old_version.ipynb)

	* The first version of LSTM (long short term memory) to predict the type of heating system type that each house has is this. Subsequently it has been improved and the [final script](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20Heating%20system.ipynb) has been reached with which we have reached an accuracy of 96%



2. Reflection on own learning objectives.

	I have greatly improved my knowledge of machine learning algorithms, as well as Deep learning. I already had a knowledge base about machine learning, but recurrent neural networks have been a challenge for me. The way to train them, as well as to feed them (3D data shape) has been quite complicated, but I have learned how they work and how this type of neural networks behaves. As well as improve my knowledge about self-organizing maps (Kohonen Map) and take a lot of ease with handling large amounts of data, for cleaning and processing.
	
	



3. Evaluation on the group project as a whole.
	
	On the other hand, having worked with the Scrum methodology we have been able to follow the project day by day. The daily standup has been a task that we have done methodologically every day. At the beginning it could have been a useless task, but over time and as we have been closing sprints with the objectives met, it has become a main task for the correct development of the project.
	
	Having worked on a real project with meetings with a product owner has given us a much more real vision of it. It has not been a mere job for the university. We had deadlines to meet, as well as expectations of the neighbors of the neighborhood where the information (Smart meters) and the product owner have been collected.



____
**Research project**
1. Task definition
	* Research question: Can we go insight the energy consumption in Netherlands?
	
	* The research project was set up by Salcedo Rahola who introduced the project to The Hague University. The Hague University introduced the project to the students that enrolled into the minor program of September 2019 to January 2020. The six of us decided to join this project as a choice between 7 projects in total.  

Salcedo Rahola set up the project because he wanted to gain insight from the data that he is working with. The goal of the project is to set up policies for dwellings based on the characteristics of the dwelling using only data from smart meters. To reach this goal we have analysed the data from the smart meters and trained machine learning and deep learning algorithms for clustering the data using Python. 

This way we should be able to answer the research question: “Can we gain energy insights of the characteristics of the dwellings and the people using the data from smart meters?”. 

However, the main goal is to reduce the fossil gas use for heating a building in The Netherlands. 87% of the build environment is using fossil gas to heat up the building. Many buildings will (have to) become CO-neutral in the future and this project will prepare companies and government organizations for this change by setting up policies faster or improving them. 

We define the characteristics of a dwelling as type of heating system, number of solar panels and number of people living in the dwelling. In total there are 33 dwellings that provided us with smart meter data, located in Groene Mient. They are all build with the same materials, structure and are localized in the same area.  

The data of the smart meters consists of the delivery, all the power that is not used going back to the net, and the consumption, all the power needed from the net, summed up every 15 minutes. The data is of a timespan from July 2017 till June 2019.

2. Evaluation

	* The results obtained by the recurrent neural networks give us the guarantee that it is possible to determine what type of heating installation a house has installed, how many people live in that house or how many solar panels have installed. In the near future, when smartmeters are mandatory in all Netherlands, the models presented here can be trained with a greater variety of data and thus improve predictions

3. Conclusions

	* My group has worked on other algorithms in parallel (Logistic Regression, Support Vector Machine, and K-Nearest Neighbour) while I developed the LSTM model. This model has finally become the best model to solve our research question.
	

	* By using Logistic Regression (LG), Support Vector Machine (SVM) and K-Nearest Neighbour (K-NN) algorithms we managed to get around a 65% accuracy on predictions. So, when presenting (a part of) the dataset, the algorithms can tell us about 65% for sure which heating system is used, the amount of people living in the dwelling and the number of solar panels used by that dwelling. This means is it only partly possible to gain energy insights of the characteristics of the dwellings and the people using the data from smart meters. 


	* LSTM (Long short-term memory): This type of recurrent neural network is the one that has provided the best predictions (96% accuracy) because its training and operation is based on long time series. That is why it has been the best option, ahead of simple RNN, for the large amount of data we handled (3 years of data, stored every 15 minutes)

	* These results have been obtained for the classification of the type of heating, which have been the highest. Predicting number of people and number of solar panels in a house I have obtained an accuracy of 87.5% and 80% respectively. It is therefore expected values, since the consumption patterns of one person can be very different than those of another, however the way of heating the house (painted on a graph), as well as the energy expenditure of each heating system is particular of each type making it easier to find patterns between heating systems of the same type.
	
	* The answer is yes, we can. With the RNN algorithm (LSTM) we can find the answer to the characteristics of the dwelling like what kind of heating system is used, the amount of people living in the dwelling and the number of solar panels used by that dwelling.
	

4. Planning

	* The project has been carried out using the SCRUM work methodology
	* Trello is the web tool we have used to update all the progress as well as its planning
	* During the project we used an agile approach using Scrum. For doing so we created an environment in Trello online. Every sprint had a duration of two weeks. Every day we had a daily stand-up to discuss what is done and what will be worked on that day. At the end of every sprint a new backlog is defined and added to the list ‘To Refine’. The beginning of the next sprint a meeting decides what will be worked on during the sprint and moved to the list ‘To Do’. The tasks in the To Do list will be assigned to certain persons in the team. When working on it the task will be moved to the list ‘In Progress’ and when done to the list ‘Done’.
	
![Image of trelloBoard](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/trello.png)
	

	
	

____
**Predictive Analytics**

My teammates have made other algorithms in which very good accuracys have not been achieved, so the lstm model has finally been chosen.

- K-NEAREST
	
	- [Predicting Heating System](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/K-Nearest%20Neighbors/K-Nearest%20Neighbors.ipynb): 64.5% accuracy result when predicting the type of heating system. 
	- [Predicting Yes or No classification](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/K-Nearest%20Neighbors/K-Nearest%20(Focusing%20on%20one%20Type).ipynb): 
 	- [Predicting HS, NP, SP](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/K-Nearest%20Neighbors/Best%20Results.ipynb): 37.5% accuracy result when predicting the number of people living in a house.  53.5% accuracy result when predicting the number of solar panels installed in a house
	
- SVM

	- [Predicting Heating System](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Support%20Vector%20Machine/SVM%20implementation%20for%20Type%20of%20Heating%20System%20with%20KNMI%20data%20(per%20day).ipynb): 61.5% accuracy result when predicting the type of heating system. 
	- [Predicting Number of People](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Support%20Vector%20Machine/SVM%20implementation%20for%20Number%20of%20Persons%20with%20KNMI%20data%20(per%20day).ipynb): 43.5% accuracy result when predicting the number of people living in a house. 
  	- [Predicting Number of Solar Panels](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Support%20Vector%20Machine/SVM%20implementation%20for%20Number%20of%20Solar%20Panels%20with%20KNMI%20data%20(per%20day).ipynb): 38.5% accuracy result when predicting the number of solar panels installed in a house
	

- LOGISTIC REGRESSION

	- [Predicting HS, NP, SP](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/Logistic%20Regression/Logistic%20Regression%20Without%20data%20from%205%20houses.ipynb): 55.5% accuracy result when predicting the type of heating system. 27.5% accuracy result when predicting the number of people living in a house. 38.5% accuracy result when predicting the number of solar panels installed in a house
 



After the data cleaning process, I used different Machine Learning algorithms to predict and classify the classes.

I have made models based on the consumption and production data set, using a data point every 15 minutes (one row of data). The results were not too good, so I used different dummy variables, such as day of the week, week, season and time. The KNMI data set has also been implemented in the data set, such as temperature, global radiation and sunshine hours. The results have improved considerably, and the one that has improved the most has been the LSTM model, because the higher the number of features, the better predictions it made.

1. Selecting a Model


- ### [Kohonen](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonen.ipynb)
	
	* classification of the house number according to its type of heating:
	
	![Image of kohonen2d](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/kohonen2d.png)
	
		-green: Heat pump (WP)
		-blue: Thermal solar panels (ZON)
		-yellow: Electricity (E)
		
	* Three-dimensional matrix to show how many times the same pattern is repeated for different dwellings
	
	![Image of kohonen3d](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/kohonen3d.png)
	
		-the higher the bar is, more activations have been occur in that neuron (same pattern)


Self-organizing maps have been a good classification tool for this project, but I have not been able to obtain more information about these classifications. That is why I decided to make class predictions based on the historical consumption and delivery data.

- ### LSTM

	- [Predicting Heating System](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20Heating%20system.ipynb): 95.5% accuracy predicting the type of heating system. 
	- [Predicting Number of People](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20People%20v2.ipynb): 87.5% accuracy predicting the number of people living in a house. 
  	- [Predicting Number of Solar Panels](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/LSTM%20-%20Solar%20panelsV2.ipynb): 80.5% accuracy predicting the number of solar panels installed in a house


The model selected for this project has finally been LSTM. It is the model with which we have achieved better results.


The output of the neural network is 3 or 4 nodes for the following reason. We have converted each possible class into an array of 3 elements ([1,0,0], [0,1,0], [0,0,1]) or 4 elemens ([1,0,0,0], [0,1,0,0], [0,0,1,0], [0,0,0,1])

By this way each final node has to be activated or not, depending on the category to be found. This has been done in this way because we found better results in this way than simply adding a final node that has to differentiate between the 3 or 4 possible classes.




Recurrent neural networks and specifically LSTM have been the best option, since these neural networks are designed to be trained with a large amount of data based on time series, which is perfect for the purpose of our project.
	


2. Configuring a Model
	
The general architecture I have used has been:

![Image of HeatingSystem](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/HeatingSystem.png)

	- Recurrent layer of 40 nodes with a dropout of 0.2 (20% of the connections are randomly removed so that the network is able to learn a pattern in different ways)
	
	- Simple 20-node MLP layer with RELU activation
	
	- Dropout of 0.25
	
	- Simple 3-node MLP layer with SOFTMAX activation (The number of outputs depends on the number of categories we want to find)
	
I add a layer of simple perceptron (dense) at the output of the recurrent layer to improve the output and that it is able to learn the patterns of recurrent network output. Then a dropout to reinforce learning. Finally, the layer of three simple nodes (simple mlp) is intended to give a value to each class to predict (this layer will have the same number of nodes as classes)


For the other two predictions I have made small modifications to the base architecture to improve the final result.


![Image of People](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/People.png)

![Image of SolarPanels](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/SolarPanels.png)


3. Training a model

The model has been trained with an input array of 92 elements per iteration. This has allowed us to train the network by separate days. The input has 10 variables, 2 of them from the dataset (consumption and delivery) and the other 8 variables added later to achieve better results. The 8 new variables that we have added, 3 of them are from the KNMI meteorological institute (T: temperature, SQ: radiation per square meter , Q: radiation ). The other 5 are dummy variables created by us in order to add more information to the dataset.

	- delivery: delivery energy to the net in Kw/h
	- consumption: energy usage from the net in Kw/h
	- T: Temperature (in 0.1 degrees Celsius) at 1.50 m height during the observation;
	- SQ: Duration of sunshine (in 0.1 hours) per hour, calculated from global radiation (-1 for <0.05 hours);
	- Q: Global radiation (in J / cm2) per hour section;
	- week: Dummy varibale of the week of the year (1-52)
	- month: Dummy varibale of the month of the year (1-12)
	- season: Dummy varibale of the season of the year (1-4)
	- day: Dummy varibale of the day of the month (1-31)
	- hour: Dummy varibale of the hour of the day (0-23)



For training I used the cross validation technique to divide the dataset into three parts. Test, Validation and Training.
	
I have printed the loss and accuracy graphs to be able to detect if I was performing overfitting or underfitting.
	
* The best configuration predicting **heating system** has been:
	
		- epochs = 60
		- validation_split = 0.2
		- learning rate = 0.003
		- loss = 'mean_squared_error'
		
* The best configuration predicting **number of solar panels** has been:
	
		- epochs = 50
		- validation_split = 0.2
		- learning rate = 0.01
		- loss = 'categorical_crossentropy'
		
* The best configuration predicting **number of people** has been:
		
		- epochs = 100
		- validation_split = 0.2
		- learning rate = 0.01
		- loss = 'binary_crossentropy'
	

4. Evaluating a model


![Image of AccLoss](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/AccLoss.png)

To evaluate the model I have used the .evaluate() function of keras, which has allowed me to evaluate the training with the test dataset. It has returned a result of 81%.This percentage is not what we had previously said of 96% and that is because the values of the network output have not yet been processed.

![Image of OutputLSTM](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/OutputLSTM.png)

The output of the network provides us with a prediction of each class with a percentage (0-1), which is why every time it reduces the probability of two classes and increases what it thinks it is. In order to compare the test data with those of the network output I have rounded the highest value of each output array to 1. In this way the classes are binarized and thus the accuracy of the model is increased to 96%


5. Visualizing the outcome of a model (explanatory)
	

Confusion matrix in which we can see with better quality the output values of the neural network:
 ![Image of ConfusionMatrix](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/ConfusionMatrix.png)


An example of the output of the neural network with predictions and real outputs:
 ![Image of PredictionsLSTM](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/PredictionsLSTM.png)




____



____

**Final Results Comparison**


![Image of ResultsTable](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/TotalResults.png)

* Barplot comparing each model with each other
	![Image of results1](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/results1.png)
	


____
**Domain knowledge**

1. Introduction of the subject field
	* In the last few years, the European Commission has set various ambitious targets in order to reduce CO2 emissions. As a result of this, the Dutch government has been regulating the energy sector to move towards the use of green energy in order to avoid the use of natural gasses by the end of 2050. By avoiding the use of natural gasses, CO2 emissions can be ceased, and earthquakes can be disposed. Accordingly, the importance of reducing the use of natural gasses in dwellings is growing strongly. Although most energy is used by industry, the build environment is responsible for 28% of the energy usage. Approximately 61% of these buildings still use natural gas for heating. The technologies that currently exist which could help us reduce the use of natural gasses, are most suitable for the build environment rather that the industry. 
 
	The build environment forms the subject field of the project. We are focussing on 33 ecological dwellings in The Netherlands (Groene Mient). In each house there is a smart meter installed, which measures the energy delivery and consumption. By using this data, in combination with publicly available information, it is possible to determine dwelling characteristics and the energy use behaviour of its residents. This information could be used to optimize the current dwellings energy system and to propose possible improvements to it with the goal to reduce CO2 emissions related to energy use. 
 
	The objective of this research is to look at what methods can be used in order to obtain as much insight as possible on the dwelling characteristics and the energy use behaviour of its residents by analysing energy use data


2. Literature research
	* During the first week of our project, we started with exploring the domain by doing literature research (see 1.4.1). We have looked at previously published papers that were available at well-known platforms such as ScienceDirect and TU Delft.  
 
	We looked at researches that were previously done on subject field, as well as researches that were done on smart meters. We did this to get more insights in previously researched topics that could have helped us to get more understanding about our subject field.   
 
We have found several papers that were on the topic of energy usage in dwellings, such as: 

	- Energy-efficient houses built according to the energy performance requirements introduced in Denmark in 2006
	- Household electricity consumption and CO2 emissions in the Netherlands: A model-based analysis
	- Embodied CO2 Emissions in Building Construction Materials of Hellenic Dwellings
	- Theoretical vs. actual energy consumption of labelled dwellings in the Netherlands: Discrepancies and policy implications
 

Next to that, we have also found a paper on smart meters (Smart metering in the Netherlands: What, how, and why [5]). This paper helped us to get more understanding about smart meters.  
 

Bibliography: 

	- H. Tommerup, J. Rose, S. Svendsen, Energy-efficient houses built according to the energy performance requirements introduced in Denmark in 2006, (2006) 
	- George Papachristos, Household electricity consumption and CO2 emissions in the Netherlands: A model-based analysis, (2014) 
	- Georgios Syngrosa, Constantinos A. Balaras, Dimitrios G. Koubogiannis, Embodied CO2 Emissions in Building Construction Materials of Hellenic Dwellings, (2017) 
	- D. Majcen, L.C.M. Itard, H. Visscher, Theoretical vs. actual energy consumption of labelled dwellings in the Netherlands: Discrepancies and policy implications, (2012) 
	- Pol Van Aubel & Erik Poll, Smart metering in the Netherlands: What, how, and why, (2019) 

3. Explanation of Terminology, jargon and definitions

	* _HS= **H**eating **S**ystem_
	* _NP= **N**umber of **P**eople_
	* _SP= number of **S**olar **P**anel_
	* LG = Logistic Regression
	* SVM = Support Vector Machine
	* K-NN = K-Nearest Neighbour
	* E = Electricity
	* ZON = Thermal solar panels
	* WP = Heat Pump
	* Cross validation technique = Statistical technique which involves partitioning the data into subsets, training the data on a subset and use the other subset to evaluate the model’s performance.


____
**Data preprocessing**


1. Data exploration

In order to explore the data, we plotted the energy delivery and energy consumption of one dwelling. From these plots we realized that the smart meters sometimes malfunctioned and did not save the data correctly, instead, what it did was to sum up all the values since it stopped working until it started again. Apart from that, there were also some dwellings where the smart meter was installed later and, therefore, there were a lot of missing data.

2. Data cleaning

The data was cleaned by removing those dwellings which had less data than the others and those rows where there were blank spaces or outliers for any dwelling. 

3. Data preparation

Once we cleaned it, we added the weather data to the dataset, which comes from the KNMI (Koninklijk Nederlands Meteorologisch Instituut) and some dummy variables as well (month, season...). Eventually we placed all the houses one below each other to feed the models. 

Finally, the data has been placed in a certain way to feed our models. We have put all the data vertically, one below the other, that is, the columns of each house have all been placed in the same column in the same order that they had horizontally in the original dataset. This has allowed us to have all the dataset information in a 2-dimensional array (821100 x 10)

Once we have the data in the correct way they have normalized to be able to have them all on the same scale and better train the network


4. Data explanation

Original Dataset

![Image of Dataset](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/dataset.png)

	ID-nummer: house identifier
	Concept: type of heating system the house has (E = Electricity, WP = Heat Pump, ZON = Thermal Solar Panel)
	PV-aantal: number of solar panels installed
	Personen: people living in that house




5. Data visualization (exploratory)

Cleaned dataset

![Image of CleanDataset](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/CleanDataset.png)


Clean normalized data set

![Image of CleanDataset](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/NormalizedDataset.png)




____
**Communication**

Communication has been a large part of our project, greatly influencing its correct development. We have made an Excel file to keep track of all the presentations made and still to be done. Next, I show a screenshot of the content of the file. 


![Image of comunication](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/comunication.png)


We decided to make this file to make an equitable distribution of the presentation tasks. The type of presentations we have made have been of 4 types: closed, open, external, and lectures. 

The **closed presentations** consist of a summary of the progress made in the last week sprint. We have two closed presentations for each sprint, these presentations are more technical than others,so we are being able to explain precisely the methods we have been using, we can explain more information about neural networks, preprocessing or data normalization.  

**Open presentations** have a similar point of view, but they have the particularity that they should not be made so technically. This is because these presentations are focussed to show the progress avhieve so far of the project to the entire university community, so anyone who is interested can came to them. On the other hand, we have the presentations of specific models such as TSNE by our group, Markov models by Saab group or genetic algorithms by Danone group.

We have also made **presentations in external locations**; they have been in Groene mient and TU Delft. The presentation of Groene mient has been carried out to present the progress of the project to the community of neighbours where the data we are using in our project have been collected. In this presentation the neighbours taught us the distribution of the houses as well as the solar panels position to have more knowledge about the data we are using and thus use them with a better perspective. 

The presentation of TU Delf has not been as technical as one would expect, because there were attendees of all levels, this is why some questions from the attendees were intended to better understand the scope of the project and others more focused on how the algorithms that we are using works. 

Finally, every week we have had an average of **2 meetings per week with the product owner** (Monday and Friday) to keep a close eye on the project.

For the correct management of individual or group tasks we have used the Trello as a scrum website tool, which has allowed us to have an accurate record of the tasks to be performed in each sprint. 


1. Presentations 

	* I have made 4 closed presentations and 1 in an external location (Groene mient)
	


2. Writing paper

	* I have done the recurrent networks part (RNN and LSTM) of the reseach paper
	* The conclusion of the research paper I have also done in collaboration with my teammate [Emilio Caba Batuecas](https://github.com/ecabab).
	
	





