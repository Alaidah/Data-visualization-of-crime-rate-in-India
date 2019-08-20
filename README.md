# Data-visualization-of-crime-rate-in-India

**Storytelling  Data visualization with intensive explanation and exploration. reveal hidden patterns through merging unexpected dataset to find reasonable relationship could find out the solution** 

**Introduction and Motivation**

The main role of visualization is communicating the complex insights that is hidden inside the data. The core driven of this report is my passion of discovering and understanding how can we make our world more peaceful, also analyzing activities related to human behavior. Crime in India is an interesting topic for exploration for many reasons. One is India has an open culture with different demographic characteristic which make crime exploration more challenging. Another reason is the availability of huge publicly available datasets for investigation. The main question of the report is, from 2001 to 2013 in a crime history 

> “what is the unseen pattern that could be discovered and draw out of it a strategy that could be applied by government in order to reduce overall crime rate in India?”.


**Dataset**


The datasets published by government of India on data platform portal from 2001 to 2013. Additionally, more than 75 datasets in csv format collected by Rajanand Ilangovan on kaggle [1], all of these files has been investigated and 7 datasets used to build a visualization:

1-	District wise crimes committed 2001 to 2012
2-	District wise crimes committed 2013
3-	Case reported and value of property taken away by place of occurrence 2011 to 2012
4-	Case reported and value of property taken away by place of occurrence 2013
5-	Juvenile apprehended state
6-	Police strength actual and sanctioned
7-	Property stolen and recovered


**Process**

All 7 datasets has been imported from kaggle and all the graphs drawn with more than one dataset. Python used as a cleaning and visualization tool. For data preparation, some of the data cleansing done in order to merge the datasets such as matching the state names and correcting other typo. In addition, some of the data transformation done such aggregating a rows based in some criteria in order to reduce variables to more meaningful ones, or changing columns type for merging process. For data combining, some of the graphs combine a dataset in order to expand the time frame, other combination was for different sources in order to figure out some of the relationship. For data visualization, _Plotly and Dash library in python used_ in order to build a separate graphs or the dashboard. Each graph type chosen based on the needed massage to be delivered. Mainly, the purpose is to have better understanding of crime nature and draw out of it a conclusion that help a government in reducing major crime, to achieve the goal the report will introduce some of the sub questions that need an answers:



> **1.	From 2001 to 2013 , what is the volume of different crime types in each state and what is the most crime occurred in India?**


![1v](https://user-images.githubusercontent.com/48627041/63384792-491bee00-c3a8-11e9-9505-4674fcabf0d8.png)

The main point is to find the bottleneck of a crime by capturing the highest crime type across all states and to answer the question I got two datasets contain all states with 30 crime types that grouped into 10 types based on their similar nature. The reason of choosing stacked bar chart is the need of comparison and producing a visualization with much less clutter. Also, it significantly reduce the cognitive load and simply showing the number of total crime for all state across 13 years with different crime types. As a powerful long term strategy adopted by government, understanding the major crime and try to figure out the factors affect it will reduce overall crime in the country. Apparently, theft is the highest crime since it capture most of the bars, also when it removed from chart overall range number of crime will reduced by 1.3M which indicate a dramatic effect caused by theft. Next we need to narrow down and make further investigation of theft crime. 



> **2.	 From 2001 to 2013, what are the dangerous places in each state regarding theft accidents?** 



![2v](https://user-images.githubusercontent.com/48627041/63384895-81233100-c3a8-11e9-86cd-a10985144e49.png)

The question answered by merging another two datasets, and merging different type of theft crimes into one category. The reason of choosing Heat map is to show the intensity of crime in each state for particular places. The above graph helps government In drawing a plan by directing police force into most dangers places. Furthermore, some of social awareness will facilitate in reducing theft crime by being more aware and avoid handling or keeping expensive things in these places. We can recognize that commercial establishment and residential premises got highest crime accidents. A surprising result appear in high-way category in Uttar Pradesh state which need more attention about the activities going there. Next we need to understand different factors connected with theft crime in a state perspective.



>  **3.	From 2001 to 2012, what are the factors that could help each state based on its crime history in drawing a plan as a short term strategy contribute to government long plan for reducing theft crime?**



![3v](https://user-images.githubusercontent.com/48627041/63384954-aa43c180-c3a8-11e9-9ee3-de8284e92691.png)


The question answered by developing a dashboard contains 4 graphs that built by using 4 datasets, each dataset filtered and cleaned for merging and to include only the rows that related to theft crime. All graphs are linked with dropdown menu that includes states name. In first chart, line chart used to draw theft crime across 12 years for selected state showing number of crimes. Each state can investigate more in the years that have a significant increase or decrease in crime number, so they can understand more and apply strategy helps in reducing crime that fit particular culture. Also, they can predict the crime in the next year by recognizing crime pattern and take the necessary precaution. In line chart the scale edited to start with zero to show the real change in crime. In second chart, scatter plot used to find relationship between number of police workforce and number of stolen or/and recovered registered cases across 12 years.
 Each state can investigate more in the performance of police force regarding theft crime and figuring out what is the best and worst performance overall 12 years, so this could help in addressing any possible corruption . In third and fourth graph, bar charts used to make comparison between different age groups of boys and girls under 18 years old who did a theft crime. Addressing the younger criminal will help in reducing future crime rate and having more moral society. Each state will have different charts based on its crime history, hence different short term strategies will be developed by each in reducing crime rate over all India.





