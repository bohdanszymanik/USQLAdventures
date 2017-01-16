# USQLAdventures
Learning a bit of U-SQL

Using the US Fatality Analysis Reporting System as a source of sample data: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315 .

There are a number of useful analyses that have already been produced on the Kaggle site using a mix of Python and R: https://www.kaggle.com/nhtsa/2015-traffic-fatalities .

Idea here is basically, load up the data into Azure Data Lake - do some transforms, extract a reduced data set and make it available for Azure ML. See if we can a repeat of some of the simple tasks eg a classification or regression task etc...

I noticed that you can also just load up the Accord stats libraries within Azure Data Lake Store as well - http://www.slideshare.net/JasonLBrugger/handson-with-usql-and-azure-data-lake-analytics-adla/38?src=clipshare .
