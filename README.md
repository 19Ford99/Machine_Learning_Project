### Disease Classifier

The raw data behind the story [Some People Are Too Superstitious To Have A Baby On Friday The 13th](http://fivethirtyeight.com/features/some-people-are-too-superstitious-to-have-a-baby-on-friday-the-13th/)

There are two files:

`dataset.csv` This dataset contains 18 columns. It includes a target column (# 1) with the diagnosed disease and the remaining columns are a list of all the symptoms that the patient has experienced. ​

4920 Total rows equating to around 100 cases for each of the 42 diseases.​

Example of diseases such as Drug Allergy, Fungal Infection, AIDS, Diabetes, etc

`US_births_2000-2014_SSA.csv` contains U.S. births data for the years 2000 to 2014, as provided by the Social Security Administration

Both files have the following structure:

Header | Definition
---|---------
`year` | Year
`month` | Month
`date_of_month` | Day number of the month
`day_of_week` | Day of week, where 1 is Monday and 7 is Sunday
`births` | Number of births
