# MITWPU (FY-DSBDA) Mini-Project
# Group Members:
* Rushikesh Goski
* Ranjan Sutradhar
* Vaishnavi Tambe
* Shivam Yadav
* Jaydhaval Madvanna

# [Click Here To See Website](https://rawcdn.githack.com/rushi329/U.S.CoalProductionAnalysis/b0e7c4fe6922c2eb4b8997961c0888d25bc77d71/index.html)

# Introduction
## The U.S Coal Mine Production
According to the U.S energy information administration (EIA), coal was used to generate 51.1 and 50.4 percentage of electricity in 2005 and 2006 respectively. The total coal based power generation was 1,992 & 1969 billion KWh in 2005-2006 respectively. Almost 92% of the coal produced in the U.S was used in power generating plants, while the remaining quantities were used for coke plant and various industrial, residential and commercial sector. Data published by the national mining association indicates that some states in the union almost entirely on a coal to produce electricity. U.S Coal Production has contributed significantly to the collective wellbeing of people by making electricity to society at large and allowing the nation to maintain its high standard of living. It is accepted that the population growth will increase the demand for electricity suggesting that coal will continue to play a vital role in the U.S economy. However, future growth of coal production and usage will likely be link to the development of a national policy on carbon dioxide emissions. To better understand the future implication on the industry, coal reserves will be described and the historical trends will be examined with respect to the number of the mines, coal production and financial data, productivity, the number of employee and safety and environmental records. These description will lead to an understanding of important issues facing the coal industry in the future. Environmental impact, determination of recoverable coal reserves, future mining conditions and demographics.

# Motivation
Coal is America's most abundant energy resource. Coal is essential to the U.S. economy, providing affordable electricity to households, businesses, manufacturing facilities, transportation and communication systems, and services throughout the economy. The intent of this analysis is to gain a clearer understanding of the research presently being undertaken throughout the entire coal cycle, and provide updated and expanded information as the basis for improved prioritization of investment within coal sector. The United States today relies on coal for nearly a quarter of all domestic energy supplies, with most of that coal used to generate more than half of the nation's electricity. To enterprise, how to achieve safety output as much as possible through paying as small as safety guarantee costs is a problem which every  enterprise management especially the coal mine management has to put a high value on and seriously study. To coal mine enterprise, the safety motivation is the economic efficiency which mobilizes employees to value work safety. The benefits of increasing coal mine production will lead increase in energy, economy and employment which can be profitable for United States.

# Problem Statement
The Coal Mining Industry is a vital economic sector for many countries including the United States. Coal is the primary fuel for electricity generation in the U.S and it is the cheapest and the most abundant source of energy. The production of coal had increased significantly from 573 million tonnes in 1978 to nearly 1,171,808,698 short tonnes in 2008 and from then it decreased drastically to 706,309,263 short tonnes.

Analysis: 
	This project shows the insights of coal reserves in the U.S and analysis of coal industry’s historical data with respect to the number of mines, total production, the number of employees and labour hours. It then discuss the issues challenging the coal industry regarding its future including accurate estimation of reserves, regulatory limitations on number of workers and labour hours.

Prediction:
	This project will predict the Production Rate on the basis of Year and State. Here we have also included a model which tells you how much labours we are going to need and how much hours they have to work for the entire year to produce the expected future coal production in the coming years.

# Solution Approach
	
Initially we are started with the data collection that was done from U.S Energy Information Administration and here we got separate data files year wise then we merged all the datasets to a single csv file then firstly to understand the attributes of our dataset and also understand what kind of data we have. We have also manually added the longitude and the latitude of the state and counties. We have done various visualisations through tableau. So after that we pre-processed our data to remove the NaN/Missing Values. After the pre-processing exploratory data analysis (EDA) was performed to achieve insights and statistical measures from the data. With the help of graphical representation in the form of various charts, then after we found the co-relation between various attributes. By using various design models we got to know relation between production and various other attributes.

# Solution Design
![Image of Flowchart](https://github.com/rushi329/U.S.CoalProductionAnalysis/blob/af5d786e10625fbd5d4fcb68e7521f26e4835f68/Blank%20diagram%20(3).png)

# Tableau Visualization

https://public.tableau.com/views/U_SCoalMineAnnualProductionvsLabourHours/Dashboard1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

https://public.tableau.com/views/U_SCoalProductionRegionWise/Dashboard1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

https://public.tableau.com/views/U_SCoalMineProductionAnalysis/U_SCoalMineProductionAnalysis?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

# Machine Learning Algorithms
Decision Tree Classifier:  Decision tree algorithm falls under the category of supervised learning. They can be used to solve both regression and classification problems. Decision tree uses the tree representation to solve the problem in which each leaf node corresponds to a class label and attributes are represented on the internal node of the tree. We can represent any Boolean function on discrete attributes using the decision tree.

Random Forest Regressor:  Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. A Random Forest operates by constructing several decision trees during training time and outputting the mean of the classes as the prediction of all the trees. 
Here in features we kept No of Employees and Production where as in target we kept Labour Hours so that we can predict the total no of labour hours needed to produce a given no of production rate as per the no of employee available to work.
In another model, we kept no of employee and labours hours as a features and production as a target. here our aim is to predict the production rate as per the given no of employee and labour hours.

# Results
* In Decision Tree Classifier were able to predict production of coal mine states annually.
* In Random Forest Regressor were able to predict Labor Hours as per given No of Employees and Production Rate.
* In another model we use random forest regressor we were able to predict Production Rate as per the No of employee and Labour Hours.

# Conclusion
Today's coal mining is a high-technology, mechanized industry with strict standards of engineering design and operation. Historical trends of the coal mining industry show an increase in production and productivity in the face of variable market conditions in the past three decades. Surface mining is the primary method of coal extraction. The coal industry has improved its safety and environmental records substantially. The future challenges the US coal industry faces are potential limitations on CO2 emissions and a more accurate determination of the nation's coal reserve base. More difficult mining conditions are expected in the future, which will require the industry to focus on improved mine worker health and safety, environmental protection and mine productivity and resource optimization.

# Future Work

The future role of coal in the US economy will depend on how well the industry addresses the challenges and issues.
The impact of new technology to generate electric power with coal cost effectively, and particularly with carbon capture and storage, could prove pivotal.
The viability of the industry over time will also depend on the ultimate amount of economic reserves as the price of coal and the cost to produce it fluctuate.
The forecast for coal's role in the U.S remains optimistic over the next few decades, but it is certainly clouded by the issues beyond that time frame.

# References 
* https://www.nap.edu/read/11977/chapter/6#66
* https://www.ifc.org/wps/wcm/connect/15626dca-c683-4d1d-a937-c09f902e9658/coal_PPAH.pdf?MOD=AJPERES&CVID=jkD223U
* https://www.eia.gov/coal/data.php
