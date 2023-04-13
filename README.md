# LDA on pima diabetes data(in R)
Using LDA to help us identify if a particular person has diabetes or not based on the person's medical records.

The Project was executed using R programming language. 

The data can be found in the file 'diabetes.csv' file.
There are values noted down as 0 in some of the columns like - Insulin, BloodPressure... This  is obviously a mistake. So we have to replace those with NA and later impute them. Here we imputed them using the 'missForest' package available in R.
The Report for the analysis along with the code is written down in Rmarkdown and it can be found in the file 'LDAdiabetes.Rmd'. The report was also knitted as a pdf and it's 'document-1.pdf' 
