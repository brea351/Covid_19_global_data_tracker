# COVID-19 Global Data Tracker

In this project, we will explore and analyze COVID-19 data to understand global trends related to cases, deaths, and vaccinations. We will:
- Investigate trends over time for various countries.
- Visualize the number of COVID-19 cases, deaths, and vaccinations.
- Identify correlations between vaccination rates and COVID-19 cases/deaths.

The dataset used in this analysis is obtained from [Our World in Data](https://github.com/owid/covid-19-data).


## Step 1: Import Libraries and Load Dataset

In this section, we import the necessary libraries for data manipulation and visualization. We will then load the COVID-19 dataset into a DataFrame.

We are using:
- `pandas` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.

Let's load the dataset and inspect the first few rows.


## Step 2: Data Exploration and Cleaning

Here, we inspect the dataset for missing values, check the structure of the data, and convert the 'date' column to a proper `datetime` type for analysis. We will also filter the data to focus on specific countries or time periods.

The goal of this step is to ensure the data is clean and ready for analysis.


## Step 3: Visualizing the Data

In this section, we visualize the trends of COVID-19 cases, deaths, and vaccinations for selected countries. The plot below shows the number of confirmed COVID-19 cases over time for the top 10 most affected countries.

### Insight:
From the plot, we can observe that the number of cases started rising significantly in early 2020 and peaked around mid-2021 for most countries. Some countries show a second wave of cases towards the end of 2021.


### Step 4: Comparing COVID-19 Deaths and Vaccinations

This plot compares the number of COVID-19 deaths with the vaccination rates in different countries. 

### Insight:
From the plot, it’s evident that countries with higher vaccination rates tend to have lower death rates, indicating a possible correlation between vaccination coverage and reduced mortality.


## Conclusion

This project explored the global trends in COVID-19 cases, deaths, and vaccinations. Our findings suggest that vaccination rates are strongly correlated with reduced death rates in many countries. However, there are exceptions, and further analysis is needed to account for factors like healthcare infrastructure and public health policies.

### Future Steps:
- Investigate the impact of COVID-19 variants on the trends.
- Compare the economic impact of COVID-19 in different regions.
- Explore the relationship between vaccination rates and new COVID-19 cases.


