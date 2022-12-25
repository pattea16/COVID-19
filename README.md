# COVID-19

library(readxl)

download.file("https://www.michigan.gov/coronavirus/-/media/Project/Websites/coronavirus/Michigan-Data/12-20-2022/Cases-and-Deaths-by-County-and-by-Date-of-Symptom-Onset-or-by-Date-of-Death2022-12-20.xlsx?rev=e9a0f2cb75c84802b0debee77693f3dd&hash=E9B2640B3298C9558274FB3F25581F64", "RAWDATA.xlsx")

myData <- read_excel("RAWDATA.xlsx")
