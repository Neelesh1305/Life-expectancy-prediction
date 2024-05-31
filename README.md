## Life expectancy predictions based on individual life factors
The following data represents the physical wellbeing, Mortality rates and Life expectancies of all the countries around the world in a span of 16 years. It also soecifies in the Life expectancies in all the countries over the years.
I wish to explore the data and analyze the progress of various diseases in all the countries over the years. And get a model which would find the relation between the diseases and other factors in the data and the Life expectancy in each Country.
ML helps fitting the various factors and the resulting Life Expentancy into a regression model so we can train test and predict the values, which helps a lot in the field of biomedical research and the governments in taking necessary measures in health care sector.

#### Data collection
The following data represents the physical wellbeing, Mortality rates and Life expectancies of all the countries around the world in a span of 16 years. It also soecifies in the Life expectancies in all the countries over the years.
I wish to explore the data and analyze the progress of various diseases in all the countries over the years. And get a model which would find the relation between the diseases and other factors in the data and the Life expectancy in each Country.
ML helps fitting the various factors and the resulting Life Expentancy into a regression model so we can train test and predict the values, which helps a lot in the field of biomedical research and the governments in taking necessary measures in health care sector.

This Data was published by the WHO(World Health Organization), to make a statistical Analysis on factors influencing Life Expectancy, over the period of 15 years. It is found in the following URL https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
There is no restriction for using this data in public environment and hence can be used to perform EDA and ML models.
As I wanted to explore datasets which would give me a better overview in the health care sector over the countries around the world and know about the factors influencing Life Expectancy, I chose this dataset.

#### Features

This dataset contains 2938 rows and 22 columns which help describe the health conditions and distribution of various diseases around the world. The columns of this dataset include

Country: Country name

Year: Year

Status: Developed or Developing status

Life expectancy: Life Expectancy in age

Adult Mortality: Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)

infant deaths: Number of Infant Deaths per 1000 population

Alcohol: Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)

percentage expenditure: Expenditure on health as a percentage of Gross Domestic Product per capita(%)

Hepatitis B: Hepatitis B (HepB) immunization coverage among 1-year-olds (%)

Measles: Measles - number of reported cases per 1000 population

BMI: Average Body Mass Index of entire population

under-five deaths: Number of under-five deaths per 1000 population

Polio: Polio (Pol3) immunization coverage among 1-year-olds (%)

Total expenditure: General government expenditure on health as a percentage of total government expenditure (%)

Diphtheria: Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)

HIV/AIDS: Deaths per 1000 live births HIV/AIDS (0-4 years)

GDP: Gross Domestic Product per capita (in USD)

Population: Population of the country

thinness 1-19 years: Prevalence of thinness among children and adolescents for Age 10 to 19 (% )

thinness 5-9 years: Prevalence of thinness among children for Age 5 to 9(%)

Income composition of resources: Human Development Index in terms of income composition of resources (index ranging from 0 to 1)

Schooling: Number of years of Schooling(years)

#### Modeling

A linear regression model is used to predict the Life expectancy, which yields an rmse error of 16.42%. A logistic regression is used to predict if a country is Developed/Developing with an accuracy of 0.88.

#### Observations and Conclusion
The highest correlation with Life expectancy exists with Schooling in a Country
The health conditions in Developed countries are better than that of the Developing country
The maximum Life Expectancy with less Adult mortality and less infant deaths, existed in Sweden in 2007
Life expectancy mean over the years by each country has a maximum in France
Maximum Adult mortality mean over the years by each country occurs in Zimbabwe
Belarus has the highest Alcohol consmption

All the factors given aid to the Life expectancy of a country in some way based on the data in correlation, also gives an overview of the health conditions in each country based on financial status of the country, Adult Mortality, infant deatha and various other factors. The Exploratory data analysis for the given data of Life expectancy analytics is performed along with fitting the data into suitable regression models to predict desired outputs.
