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

* [TSNE](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Visualizations/TSNE%20Kmeans%20K-Nearest.ipynb) 

I have created the TSNE script with the purpose of being able to have a clearer view of the data and possible patterns before starting to create machine learning models, as well as neural networks. In the same way, within the script itself I have created a preliminary version to the final of kmeans and k-nearest in order to be able to better adjust the values and have a better approach to this type of technique.



* [Outliers by maximuns](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Cleaning%20data/outliers%20by%20maximuns.ipynb)

On the other hand, I have also done cleaning scripts to be able to have a list of outliers in order to have a list of ouliers and thus be able to analyze them in order to better understand the dataset. 

Using the following formula: max_production = (75 * 230) / 4000 I have been able to find outliers. 
75 amps * 230 volts divided by 4 (because each row of data is every 15 minutes) and multiplied by 1000 to convert it to KW




* [Maximun electricity](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Visualizations/Maximun%20electricity%20current.ipynb)

Maximum electricity current (amps) that enter and exit each house, as well as in total have also been carried out independently. The objective of making these graphs is to understand if the houses between them would be able to be self-sufficient by connecting with each other and thus be able to create a network between them. In this way we would achieve the almost independence of power plants, that is, when a house produces more than it consumes, instead of pouring it into the grid and losing it, being able to share that energy with other houses.



* [Visual clasification](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Visualizations/DOOR'S%20Visual%20Clasification.ipynb)

Visual clasification of consumption and delivery of each house.



* [Kohonen](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonen.ipynb)

Kohonen map to classify each house in an unsupervised way and to establish the first patterns between houses with the same type of heating, number of people and number of solar panels


* [Kohonen visualitations](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Kohonen/Kohonenen%20visualitation.ipynb)

Kohonen visualitations 3D map to get acces to the entire data plot



* [MLP](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Supervised%20Machine%20Learning%20Algorithms/MLP_FINAL.ipynb)

MLP (multi layer perceptron) used in the first versions of the algorithms to try to predict the possible classes of houses (heating system, number of solar pannels, number of people)


* [LSTM](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Recurrent%20Neural%20Network/RNN_old_version.ipynb)

The first version of LSTM (long short term memory) to predict the type of heating system type that each house has is this. Subsequently it has been improved and the final script has been reached with which we have reached an accuracy of 96%





2. Reflection on own learning objectives.





3. Evaluation on the group project as a whole.





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

	* We decided to use Recurrent Neural Network (RNN) algorithm to see if results are any different. Here we managed to get an accuracy of 96%. Considered that companies search for a minimum of 95% accuracy, we can now answer the research question. The answer is yes, we can. With the RNN algorithm we can find the answer to the characteristics of the dwelling like what kind of heating system is used, the amount of people living in the dwelling and the number of solar panels used by that dwelling. Therefore, we can gain energy insights of the characteristics of the dwellings and the people using the data from smart meters. 

4. Planning

	* The project has been carried out using the SCRUM work methodology
	* Trello is the web tool we have used to update all the progress as well as its planning
	* During the project we used an agile approach using Scrum. For doing so we created an environment in Trello [1] online. Every sprint had a duration of two weeks. Every day we had a daily stand-up to discuss what is done and what will be worked on that day. At the end of every sprint a new backlog is defined and added to the list ‘To Refine’. The beginning of the next sprint a meeting decides what will be worked on during the sprint and moved to the list ‘To Do’. The tasks in the To Do list will be assigned to certain persons in the team. When working on it the task will be moved to the list ‘In Progress’ and when done to the list ‘Done’.
	
	* Sprint 1: 
	
		* 09-09-2019 closed presentation and 16-09-2019 closed presentation. 

			* Our project owner (Salcedo Rahola) introduced us to the project in more detail. He gave us some tasks to do and gave us the 	dataset of Groene Mient. The first week we mostly spend time on literature research to see if other papers could provide us with useful information, and learning Python from courses on DataCamp where access was provided by The Hague University. In week two we loaded the given dataset into the data science server of The Hague University. We started making the first visualizations that gave us insight of all the gaps and outliers in the dataset and the maximum usage and consumption per day per household 

			* During the two weeks we also tackled the research question to see if the question is realistic and within our scope.

	* Sprint 2:
	
		* 23-09-2019 and 30-09-2019 closed presentation and 27-09-2019 open presentation. 

			* This sprint we searched for outliers in the dataset and tried to clean them based on the question we needed to answer at that time. For a calculation over the year every datapoint was needed, but for predictions outliers needed to be removed.   

			* We calculated the maximum amount of Ampere that a household delivers and consumes on the original dataset without cleaning. 

			* After discussing the research questions some more we decided to look for more data to be able to answer to questions better. We decided to look into weather data like temperature and sun hours of a weather station near Groene Mient. The variables of that dataset can be used as dummy variables during training of the Machine Learning algorithms. 

			* To reach the deadlines of DataCamp we also spent time working on courses like ‘Python Data Science Toolbox’ and ‘Statistical plots with Seaborn’. 
	
	* Sprint 3: 
	
		* 07-10-2019 closed presentation and 14-10 closed presentation. 

			* This sprint we focused mainly on data analysis. Therefore, we cleaned the data by removed every row of the dataset when it is missing data so that all the columns have the same length. Also, five houses have been deleted from the dataset because of the high number of rows without data. After this cleaning process, 80% of the data was preserved. We reran the Ampere calculation script and all the visualizations with the cleaned dataset. 

			* From there on we started using K-Nearest Neighbours, Support Vector Machine, Logistic Regression and TSNE algorithms to classify groups of residents.  

			* To see if we could improve results on those algorithms, we created dummy variables per day, per day cycle, per hour and per season.  

			* Compared the Machine Learning algorithms on efficiently. 

			* To reach the deadlines of DataCamp we also spent time working on courses like ‘Cleaning data with Python’ and ‘Statistical thinking in Python’.
	
	* Sprint 4: 
	
		* 01-11-2019 t-SNE presentation and open presentation and 08-11-2019 presentation at Groene Mient. 

			* This sprint we also started using Kohonen map (self organizing maps) algorithm to classify groups of residents. 

			* Spent some time on DataCamp to keep our knowledge updated.  
	
	* Sprint 5: 
	
		* 11-11-2019 closed presentation and 18-11-2019 closed presentation. 

			* During this sprint we also mainly focused on data analytics. This time we also started using K-means, Hierarchical clustering, Density Based Scan Clustering and Gaussian Clustering algorithms to classify groups of residents. 

			* Compared these unsupervised leaning algorithms with each other. 

			* Implemented Logistic Regressions, K-Nearest Neighbour, Support Vector Machine and MLP algorithms with the labels from the dataset.  

			* Next to this we also started working on the layout of the research paper and wrote the first chapter, the introduction. 
	
	* Sprint 6:
	
		* 29-11-2019 presentation at TU Delft and 29-11-2019 open presentation. 

	 		* This sprint we applied the KNMI Dataset to the previously used algorithms with variables like temperature and solar radiation.  

	 		* Started using the Recurrent Neural Network algorithm with and without the KNMI dataset.  

	 		* Improved the supervised learning algorithms (LR, SVM, K-NN, RNN) with the one-against-all approach. We compared those algorithms on efficiently using first raw data, second grouped data and third with KNMI data.  

	 		* At this point we decided to start preparing the new dataset with 120 dwellings to feed the existing models.  

	 		* With all these algorithms used the server contained many different maps that needed a clean-up, which we did at the end of this sprint. 

			* For the research paper the introduction was extended and chapter 2, Techniques – Methods, has been set up. 
	
	* Sprint 7: 
	
		* 09/12/2019 - 20/12/2019
	
			* Sprint 7 progress here
	

____
**Predictive Analytics**

After the data cleaning process, we used different Machine Learning algorithms to predict the heating system, the number of people living in the house and the number of solar panels installed. 

We have used several classification models to make these predictions. We have made models based on the consumption and production data set, using a data point of every 15 minutes (one row of data). The results weren’t good, so we used different dummy variables, such as day of the week, week, season and hour. The KNMI dataset has also been implemented in the dataset, such as the temperature, global radiation and sun hours. The results improved a little bit in comparison to only using the consumption and production data. For some models, we used the summed data per day, because one row with data contains an insufficient amount of information to make a good classification.

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

	* Recurrent layer of 40 nodes with a dropout of 0.2 (20% of the connections are randomly removed so that the network is able to learn a pattern in different ways)
	
	* Simple 20-node MLP layer with RELU activation
	
	* Dropout of 0.25
	
	* Simple 3-node MLP layer with SOFTMAX activation (The number of outputs depends on the number of categories we want to find)



![Image of HeatingSystem](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/HeatingSystem.png)

![Image of HeatingSystem](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/People.png)

![Image of HeatingSystem](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/SolarPanels.png)



The output of the neural network is 3 or 4 nodes for the following reason. We have converted each possible class into an array of 3 elements ([1,0,0], [0,1,0], [0,0,1]) or 4 elemens ([1,0,0,0], [0,1,0,0], [0,0,1,0], [0,0,0,1])

By this way each final node has to be activated or not, depending on the category to be found. This has been done in this way because we found better results in this way than simply adding a final node that has to differentiate between the 3 or 4 possible classes.

The model has been trained with an input array of 92 elements per iteration. This has allowed us to train the network by separate days. The input has 10 variables, 2 of them from the dataset (consumption and delivery) and the other 8 variables added later to achieve better results. The 8 new variables that we have added, 3 of them are from the KNMI meteorological institute (T: temperature, SQ: radiation per square meter , Q: radiation ). The other 5 are dummy variables created by us in order to add more information to the dataset.
delivery
consumption
T
SQ
Q
week
month
season
day
hour

The training has been carried out with 60 epochs and a learning rate of 0.003.

INSERT HISTORY GRAPH MODEL



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

	Energy-efficient houses built according to the energy performance requirements introduced in Denmark in 2006 [1] 
	Household electricity consumption and CO2 emissions in the Netherlands: A model-based analysis [2] 
	Embodied CO2 Emissions in Building Construction Materials of Hellenic Dwellings [3] 
	Theoretical vs. actual energy consumption of labelled dwellings in the Netherlands: Discrepancies and policy implications [4] 
 

Next to that, we have also found a paper on smart meters (Smart metering in the Netherlands: What, how, and why [5]). This paper helped us to get more understanding about smart meters.  
 

Bibliography: 

	H. Tommerup, J. Rose, S. Svendsen, Energy-efficient houses built according to the energy performance requirements introduced in Denmark in 2006, (2006) 
	George Papachristos, Household electricity consumption and CO2 emissions in the Netherlands: A model-based analysis, (2014) 
	Georgios Syngrosa, Constantinos A. Balaras, Dimitrios G. Koubogiannis, Embodied CO2 Emissions in Building Construction Materials of Hellenic Dwellings, (2017) 
	D. Majcen, L.C.M. Itard, H. Visscher, Theoretical vs. actual energy consumption of labelled dwellings in the Netherlands: Discrepancies and policy implications, (2012) 
	Pol Van Aubel & Erik Poll, Smart metering in the Netherlands: What, how, and why, (2019) 

3. Explanation of Terminology, jargon and definitions


____
**Data preprocessing**




In order to explore the data, we plotted the energy delivery and energy consumption of one dwelling. From these plots we realized that the smart meters sometimes malfunctioned and did not save the data correctly, instead, what it did was to sum up all the values since it stopped working until it started again. Apart from that, there were also some dwellings where the smart meter was installed later and, therefore, there were a lot of missing data. 

The data was cleaned by removing those dwellings which had less data than the others and those rows where there were blank spaces or outliers for any dwelling. 

Once we cleaned it, we added the weather data to the dataset, which comes from the KNMI (Koninklijk Nederlands Meteorologisch Instituut) and some dummy variables as well (month, season...). Eventually we placed all the houses one below each other to feed the models. 


1. Data exploration
2. Data cleaning
3. Data preparation
4. Data explanation
5. Data visualization (exploratory)


____
**Communication**

Communication has been a large part of our project, greatly influencing its correct development. We have made an Excel file to keep track of all the presentations made and still to be done. Next, I show a screenshot of the content of the file. 


![Image of comunication](https://github.com/SantiagoPuertas/Dwelling-Energy-Insights/blob/master/Images/comunication.png)


We decided to make this file to make an equitable distribution of the presentation tasks. The type of presentations we have made have been of 4 types: closed, open, external, and lectures. The closed presentations consist of a summary of the progress made in the last week sprint. We have two closed presentations for each sprint, these presentations are more technical than others,so we are being able to explain precisely the methods we have been using, we can explain more information about neural networks, preprocessing or data normalization.  

Open presentations have a similar point of view, but they have the particularity that they should not be made so technically. This is because these presentations are focussed to show the progress avhieve so far of the project to the entire university community, so anyone who is interested can came to them. On the other hand, we have the presentations of specific models such as TSNE by our group, Markov models by Saab group or genetic algorithms by Danone group. This last type of presentations helps us to have a broader view of the work that our colleagues do and thus be able to help each other as well. 

We have also made presentations in external locations; they have been in Groene mient and TU Delft. The presentation of Groene mient has been carried out to present the progress of the project to the community of neighbours where the data we are using in our project have been collected. In this presentation the neighbours taught us the distribution of the houses as well as the solar panels position to have more knowledge about the data we are using and thus use them with a better perspective. 

The presentation of TU Delf has not been as technical as one would expect, because there were attendees of all levels, this is why some questions from the attendees were intended to better understand the scope of the project and others more focused on how the algorithms that we are using works. 

Finally, every week we have had an average of 2 meetings per week with the product owner (Monday and Friday) to keep a close eye on the project. This has allowed us to move along the recommended line by him and thus be able to move faster in the development of algorithms and not get lost in other methods that are not useful for the project. 

For the correct management of individual or group tasks we have used the Trello as a scrum website tool, which has allowed us to have an accurate record of the tasks to be performed in each sprint. 


1. Presentations 
2. Writing paper






