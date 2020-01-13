# Portfolio Santiago Puertas Puchol
# Dwelling Energy Insights

**Introduction**



**DataCamp course**
1. DataCamp Course completion. 
	* I have completed a total of 7 datacamp courses that have helped me to better understand data preprocessing, dataframe 	processing and data visualization
	![Image of datacamp1](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp1.png)
	![Image of datacamp2](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp2.png)
	![Image of datacamp3](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/datacamp3.png)

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

	* Visual clasification of consumption and delivery of each house.



* [Kohonen](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonen.ipynb)

	* Kohonen map to classify each house in an unsupervised way and to establish the first patterns between houses with the same type of heating, number of people and number of solar panels


* [Kohonen visualitations](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonenen%20visualitation.ipynb)

	* Kohonen visualitations 3D map to get acces to the entire data plot



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

	* We have tested 4 different routes in order to predict and classify the data of each house.
		* LSTM (Long short-term memory): This type of recurrent neural network is the one that has provided the best predictions.
		* K-NEAREST (K Nearest Neighbor)
		* SVM (Support vector machine)
		* LOGISTIC REGRESSION
	
	
	* In this part of the chapter the results of the relevant algorithms used are discussed.  

	* By using Logistic Regression (LG), Support Vector Machine (SVM) and K-Nearest Neighbour (K-NN) algorithms we managed to get around a 65% accuracy on predictions. So, when presenting (a part of) the dataset, the algorithms can tell us about 65% for sure which heating system is used, the amount of people living in the dwelling and the number of solar panels used by that dwelling. This means is it only partly possible to gain energy insights of the characteristics of the dwellings and the people using the data from smart meters. 


	* These results have been obtained for the classification of the type of heating, which have been the highest. Sorting number of people and number of solar panels in a house I have obtained an accuracy of 87.5% and 80% respectively. It is therefore expected values, since the consumption patterns of one person can be very different than those of another, however the way of heating the house (painted on a graph), as well as the energy expenditure of each heating system is particular of each type making it easier to find patterns between systems of the same type.
	
	* The answer is yes, we can. With the RNN algorithm we can find the answer to the characteristics of the dwelling like what kind of heating system is used, the amount of people living in the dwelling and the number of solar panels used by that dwelling.
	

4. Planning

	* The project has been carried out using the SCRUM work methodology
	* Trello is the web tool we have used to update all the progress as well as its planning
	* During the project we used an agile approach using Scrum. For doing so we created an environment in Trello online. Every sprint had a duration of two weeks. Every day we had a daily stand-up to discuss what is done and what will be worked on that day. At the end of every sprint a new backlog is defined and added to the list ‘To Refine’. The beginning of the next sprint a meeting decides what will be worked on during the sprint and moved to the list ‘To Do’. The tasks in the To Do list will be assigned to certain persons in the team. When working on it the task will be moved to the list ‘In Progress’ and when done to the list ‘Done’.
	
![Image of trelloBoard](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/trello.png)
	

	
	

____
**Predictive Analytics**



After the data cleaning process, I used different Machine Learning algorithms to predict the classes.

I have used several techniques and algorithms to make these predictions and / or classifications. I have made models based on the consumption and production data set, using a data point every 15 minutes (one row of data). The results were not too good, so I used different dummy variables, such as day of the week, week, season and time. The KNMI data set has also been implemented in the data set, such as temperature, global radiation and sunshine hours. The results have improved considerably, and the one that has improved the most has been the LSTM model, because the higher the number of features, the better predictions it made.

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
### LSTM
The model selected for this project has finally been LSTM. It is the model with which we have achieved better results.

The architecture we have used has been:

	- Recurrent layer of 40 nodes with a dropout of 0.2 (20% of the connections are randomly removed so that the network is able to learn a pattern in different ways)
	
	- Simple 20-node MLP layer with RELU activation
	
	- Dropout of 0.25
	
	- Simple 3-node MLP layer with SOFTMAX activation (The number of outputs depends on the number of categories we want to find)



![Image of HeatingSystem](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/HeatingSystem.png)

![Image of People](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/People.png)

![Image of SolarPanels](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/SolarPanels.png)



The output of the neural network is 3 or 4 nodes for the following reason. We have converted each possible class into an array of 3 elements ([1,0,0], [0,1,0], [0,0,1]) or 4 elemens ([1,0,0,0], [0,1,0,0], [0,0,1,0], [0,0,0,1])

By this way each final node has to be activated or not, depending on the category to be found. This has been done in this way because we found better results in this way than simply adding a final node that has to differentiate between the 3 or 4 possible classes.

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

The training has been carried out with 60 epochs and a learning rate of 0.003.




____

**Final Results Comparison**


![Image of ResultsTable](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/TotalResults.png)



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

**Open presentations** have a similar point of view, but they have the particularity that they should not be made so technically. This is because these presentations are focussed to show the progress avhieve so far of the project to the entire university community, so anyone who is interested can came to them. On the other hand, we have the presentations of specific models such as TSNE by our group, Markov models by Saab group or genetic algorithms by Danone group. This last type of presentations helps us to have a broader view of the work that our colleagues do and thus be able to help each other as well. 

We have also made **presentations in external locations**; they have been in Groene mient and TU Delft. The presentation of Groene mient has been carried out to present the progress of the project to the community of neighbours where the data we are using in our project have been collected. In this presentation the neighbours taught us the distribution of the houses as well as the solar panels position to have more knowledge about the data we are using and thus use them with a better perspective. 

The presentation of TU Delf has not been as technical as one would expect, because there were attendees of all levels, this is why some questions from the attendees were intended to better understand the scope of the project and others more focused on how the algorithms that we are using works. 

Finally, every week we have had an average of **2 meetings per week with the product owner** (Monday and Friday) to keep a close eye on the project. This has allowed us to move along the recommended line by him and thus be able to move faster in the development of algorithms and not get lost in other methods that are not useful for the project. 

For the correct management of individual or group tasks we have used the Trello as a scrum website tool, which has allowed us to have an accurate record of the tasks to be performed in each sprint. 


1. Presentations 

	* Closed: Weekly presentations in which only the students of the minor and teachers participate to show the progress made in that week. They have a more technical format than other presentations.
	* Open: Weekly presentations in which anyone who is interested in going can participate, to show them progress made in that week. They have a less technical format and are based more on trying to show people who do not know so much about the field that they know and understand as much as possible.
	* TSNE: Presentation made to explain TSNE. Each group has the possibility of presenting an algorithm or technique that they have used in their project to show it to classmates.
	* Groene mient: Presentation made in the neighborhood where the information of the Smart meters has been extracted. The objective of this presentation is to show the neighbors the progress we were taking so far and what kind of information, as well as patterns we have taken out after performing the data processing.
	* TU Delft: Presentation made at the University of TU Delft to show the project as well as its progress.
	


2. Writing paper






