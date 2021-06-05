### BigProject_DSC - Exploratory Data Analysis on COVID

#### Required packages to run: 

Plotly, Numpy, Pandas, Datetime

#### ✔️ GitHub shows static image of the HTML/JavaScript that makes up Plotly Visualisations 
To view the notebook properly use this link: 

https://nbviewer.jupyter.org/github/cph-ap228/DSC_ExploratoryDataAnalysis_On_COVID-Vaccines/blob/master/BigProject_COVID.ipynb
___________________________________
## ✔️ Idea: Exploratory Data Analysis on the severity of COVID parameters and Vaccination statistics.
### Focus of *interest*:
It has been well over a year since the world got shaken up by these fast-spreading microscopic creatures, and has changed everyday life for the majority of people all around the world. This pandemic has been the result of plenty conspiracy theories surfacing, questioning many governments and approaches to how to deal with the virus. This has also led to a huge shift in the medical sector that is working day and night to try to suffocate the wider spread of the virus, in an attempt to normalize the way we human beings live. This is with no question the most discussed topic in the recent decade, where everyone is eager for answers.
### Why is it *interesting?*:
It's first and foremost extremely relevant. An Exploratory Data Analysis on this topic provides valuable knowledge in all the attributes the virus possesses and the outcoming factors from countries all over the world. This research will provide the most seeked after an valuable statistical data on all behavioral states on the virus and human beings. 

### Null Hypothesis: 
Vaccines do not have any effect on decreasing the rate of new infections or death rates. 

### Alternative Hypothesis:
Vaccines do in fact have an effect on slowing down the rate of new infections. 

### Furthermote other questions arise:
Can we really rely on the current data that is available for COVID to be represented correctly? Despite that a common nominator is that a global spike of COVID cases is still present, despite a huge growth of vaccinated people all over the world. 

### Which outcome do you expect from your research?:
A statistical research that can provide answers on the development of the virus since it surfaced. A hypothesis that still stands true based on the results as a proof of the determining factors that the most well-off countries around the world have taken into practise, in an attempt to stop the wide spread of the virus within their borders. Futhermore that all related exploratory data has been data mined, discussed and visualized.

### Who's the target *audience/our users?*:
Health Authorities around the worlds within governments, WHO, Data Analysts, Business Strategists and Analysts, Medical Sector and Vaccine Distributors.

Described as an use case: A Business Strategist or Researcher could supply themselves with the provided analysis and survey data in how economy and businesses have been affected, and create a strategy for current appliable businesses in how to operate their business infrastructure in other means, despite the pandemic. 
___________________________________
# Stage 2: 

#### 1. Find relevant data sources:
## Data
Data, based and used from this Link: 
* 1. https://www.kaggle.com/josephassaker/datasets - The COVID-19 Global Dataset
* 2. https://www.kaggle.com/gpreda/datasets - COVID19 World Vaccination Progress

Data is stored in the folder named: Data

Features of Data Set #1 : 
##### Date, Country, # Cummulative Total Cases, # Daily New Cases, # Active Cases, # Cumulative Total Deaths, # Daily New Deaths. 

Second CSV containing Summary Data includes: 

##### Country, Continent, # Total Confirmed, # Total Deaths, # Total Recovered, # Active Cases, # Serious_or_Critical, # Total Cases Per 1 Million, # Total Deaths per 1 Million, # Total Tests.

Features of Data Set #2 : 
##### Location, Date, Type of Vaccine, Country, ISO Code for Country, Total # Vaccinations, # People Vaccinated (1 Shot), # People Fully Vaccinated, # Daily Vaccinations Raw Data, # Daily Vaccinations, # Total Vaccinations per Hundred. 
___________________________________
#### 2. Integrate the sources by either ETL or an ELT process
Whole solution incl. Data Cleaning, Preprocessing and Visualization is done in the current Notebook file: 

BigProject_COVID.ipynb 
___________________________________
#### 3. Design a Data Story or Data Processing Scenario 
#### Data logistics
The data is collected from Kaggle by Joseph Assaker and Gabriel Preda respectively. 
The data is moved and fetched weekly/daily respectively from https://www.worldometers.info/coronavirus and https://ourworldindata.org/ and their public GitHub repository on COVID statistics https://github.com/owid/covid-19-data 

I then localize the data on my device and utilize various tools available within Python and Jupyter Notebook for loading, cleaning, processing and visualizing the fetched .csv files in the Python environment.

#### Data characteristics
Data types are primarily numerical, categorical, cumulative and aggregate data.
The data size is small and formatted in a compressed .csv format. 

#### Dataset quality
Pre-processing and cleaning of data is bound to be necessary as a matter of comprehension factor for some geographical landmarks. However the majority of the data is already predefined and readily available to be explored, determining that extensive resources on cleaning the data is not needed.
Fortunately the data points available in the data sets are all intertwined and useful for the overall analysis and the proving/disproving of the null hypothesis. However the hypothesis of needing additional data to fulfill the research and analysis is something to take into consideration too, this is mainly due to that the data is cumulative and updated regularly and that some countries are more likely to report their pandemic statistics more openly and frequently. 
The Daily Dataset, is presented in an odd format, so extensive data cleaning measures as: aggregating and sorting unique values into lists are needed to represent the data in a functional state.

#### Preferred tools and languages
The technology stack utilized is as followed: 
- Plotly, a versatile library to generate interactive plots that can be interpreted easily and customized. 
- Numpy, used for array manipulation and vectoring for scientific computing, it's extensively used in this case for analytics. 
- Pandas, a library used extensively for data science as it is just as versatile as Numpy to explore data structures and functions to manipulate structured data, as I am doing in this case. 

Python 3.6.8 within Jupyter Notebook as IDE and Presentational tool. 
___________________________________
# Stage 3: 
## Hypothesis Testing 

#### 1. Visualise and interpret a model to support your null hypothesis.

#### 2. Search for evidence to reject it.
Based on current evidence and data availability, there is at the time of when the data has been explored nothing to reject it at this moment, as the conclusion and argumentation for my null hypothesis states.

#### 3. Assess the significance of the evidence.
Based on the data logistics and sources, the evidence found and concluded is set to be true, but not final as it is a cumulative result.

#### 4. Create the second prototype of your data science story.
The protorype of the data story is uploaded as a PDF on this repository: 

DataStory - EDA of COVID and Vaccine Progression.pdf

__________________________________
# Stage 4
## Immersive Analytics and Visualisation

#### 1. Applying & Elaborating on usability of applying better visualisation techniques.
The project is conducted by using Plotly Graph Objects and Plotly Express, which create immersive hovertext statistics. 
Other measures such as heatmaps and perhaps AR/VR technologies could also be used to spawn in statistics through 3D environments or put in place in the real world to better immersify.
I believe that the data is more convincing in a more explorable and open to conclusions in this way. Statistical hovertext-bar plots have been used, as well as choropleth maps as an example shown here (and are interactive if used in the Jupyter Notebook file): 

![alt text](https://github.com/cph-ap228/DSC_ExploratoryDataAnalysis_On_COVID-Vaccines/blob/master/Image%20Example/Choropleth.png)

#### 2. Elaborate on the compliance of the solution with data science ethical norms and best practices.
I believe being critical and unbiased in data logistics, formatting and data preparation/cleaning will yield better and more correct argumented results.
Knowing the data and where it is sourced is a key part in revealing truth about new data sets. Exploration and formatting is key to get to know your data and apply it better to visualize and argument for your problem statement.
I believe that I have been critical in my approach and that the data is believable and supports my initial hypothesis. 
__________________________________
