# **Exploratory Data Analysis on Global Terrorism Dataset**

## About
Terrorism is one of the biggest global challenges faced by humanity, killing and wounding millions of people, and responsible for the long-term destruction of wealth opportunities and the well-being of people. Our project is an attempt to dig deep into data to find out the possible ways to prevent terror attacks, initiatives that can be taken for the short and long term for tackling global terrorism, and changing trends in terror attacks to effectively plan mitigation measures for the future.

## Objective
By the end we will conclude the study with the following Insights:-

- Which countries were most attacked?
- Which regions were affected the most?
- Is there an increase or decrease in recent years?
- Is there an increase or decrease in the number of successful terror operations?
- Who are the most targeted globally and regionally?
- What are the most common types of attacks globally and regionally?
- What are the most used weapon types globally and regionally?
- Which terrorist organization is responsible for the majority number of attacks? 

By analyzing these questions, the end goal is to come up with short-term and long-term solutions to stop and tackle terrorism.

## Workflow

- Understanding problem statements and Raw data
- Data wrangling: cleaning, manipulation
- Exploratory Data Analysis
- Data Visualization
- Analysing and sharing the conclusions

### 1. Understanding problem statements and Raw data
  Firstly very carefully We understand the problem statement and the questions for which we are doing this study. what we want to find out or can find out from the given data set. then we collect data and import it into the system/software. Here we are using "Colab" for this study. Import libraries such as NumPy, pandas, matplotlib, and seaborn. Then load the raw dataset. We read the data and try to understand the minute detail like what information each column gives and how useful it can be for the study. we found out that there are 135 variables/Columns with around 1,81,691 entries/Rows. There were a few columns that we felt were very important to base our study on i.e. Year, Region, Country, State/provinces, City, Target type, Attack type, etc.

### 2. Data wrangling
  Process of cleaning, organizing, and transforming raw data into the desired format for analysts to use for prompt decision-making. Here start finding in the data i.e. Null values, missing values, NaNs, and redundant values of data.

**a. Handling Null Values:**
  Around 106 columns out of 135 columns were having more than 85% null values, by the rule of thumb, we have dropped those columns since we can't make better insights out of them. We left with 47 columns after dropping.
  
**b. Dropping unnecessary columns:**
  The columns with the completely numeric representation i.e, nominal data of textual data available in other columns representing the same fact/data were dropped. The dropped columns are as follows country, region, attacktype1, targtype1, targsubtype1,weaptype1, weapsubtype1, natlty1. Also, the columns deemed unnecessary for our analysis were dropped. Those columns are guncertain1, individual, dbsource, INT_LOG, INT_IDEO, INT_MISC, INT_ANY, specificity, vicinity, crit1, crit2, crit3, eventid, property, weapsubtype1_txt, targsubtype1_txt, doubter, iday, eventid, extended, target1.
  
**c. Data Manipulation:** 
  Creating new variables/columns by combining the other two columns for an effective study i.e.
Victims = No. of Killed + No. of Wounded

### 3. Exploratory Data Analysis
  Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns, spot anomalies, test hypotheses, and check assumptions with the help of summary statistics and graphical representations.
  
**Analysis**

**i) UNIVARIATE ANALYSIS:**
  Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; the distribution of single data, and find patterns in the data.

**ii) BIVARIATE ANALYSIS:**
  Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study analyzed the two variables to understand to what extent the change has occurred.

**iii) MULTIVARIATE ANALYSIS:**
  Multivariate data analysis is the study of relationships among the attributes, classifying the collected samples into homogeneous groups, and making inferences about the underlying populations from the sample.

### 4. Data Visualization

Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. The graphs used here for the study are: -

- Histogram
- Pie Chart
- Bar Plot
- Line Plot
- Sunburst Chart
- Treemap Chart
- WordCloud
- Heatmap Chart
- Scatter Plot
- Geo Mapping

### 5. Inference and Conclusions

**Conclusion:**

1. Terrorist attacks reached a peak during 2014 and then in 2015 started to drop. The Drop in the Number of Terror Attacks is not a sign of improvement in security checks in society as the ability to carry out a successful terror attack has not reduced significantly.
2. If the last 6 years were to be compared i.e. from 2012-2017 with the entire timeline we see an extreme rise in the number of attacks. Necessary action needs to be taken before terrorism poses an insurmountable challenge.
3. The Middle East & North Africa is the most affected region in terms of the number of terror attacks among all the regions followed by South Asia, South America, and Sub-Saharan Africa.
4. Iraq is the most affected nation of all and it has suffered the highest number of attacks followed by Pakistan, Afghanistan, and India.
5. Most attacks were Bombing or Explosion followed by firearms.
6. Most commonly used weapons in terror attacks are Explosives and assault weapons.
7. Most Attacks are Targeted towards Private Citizens & Property, Military, Police, and Government.
8. The Target Types suggest the attacks might be carried out to induce fear and pass on a message to the society by spreading chaos among citizens and reducing morale and confidence in security agencies thereby challenging the legitimacy of the governments.
9. Before 2014 we see a majority of claimed attacks were carried out by insurgency organizations but after 2014 we see 7 out of 10 terror groups are Islamic Radical Terror Organizations suggesting a greater concern towards radicalization.
10. Majority of Terror Attacks are not claimed by any terrorist organization.
11. Taliban and ISIL are the most active Organizations in the world.
12. Afghanistan has been attacked and suffered the most because of the Taliban.
13. ISIL is rapidly increasing its presence in Africa after the Middle East which should be a cause of concern.
14.  Terror Organizations and Attacks are slowly moving to Underdeveloped and Developing Countries with large populations below the poverty level in South Asia and Africa.
15. This creates a cycle of terrorism as poverty and unemployment help radical ideologists lure youth towards terrorism, discouraging investors which in turn affects the earnings of local governments and leads to further poverty and unemployment.

**Possible Steps to Tackle Terrorism:**

1. Defining Terrorism on a global stage and adopting an International Framework to tackle terrorism
2. Creating a joint task force to improve Intelligence Sharing and sharing best practices to combat terrorists.
3. By imposing strict regulations on the access and sale of Dangerous weapons and firearms and tracing sources of such weapons.
4. Adopting a global framework and implementing a tough action plan against terror financers.
5. Education in population control and improving conditions to encourage employment opportunities might reduce terror activities in the long run.
6. Strict policies against disinformation and radicalization need to be adopted in media including the internet.



**Note** : To Access the Google Colab File [Click Here ](https://colab.research.google.com/drive/1NsjG8146AInmJ1EUMqehfH5ibhFNq52Y?usp=sharing)

**Note**: The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.
