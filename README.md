# map-reduce-nallavolu
practicing mapping &amp; reducing

# [Nallavolu-piping-map-reduce](https://github.com/TejaswiNallavolu/map-reduce-nallavolu/tree/main/Piping)


# Data set I chose:
## Car insurance claim dataset
- The client is a car insurance company. They want to price their car insurance competitively, which means having a good model for customers at risk of getting into accidents.
- Each row corresponds to a customer, the outcome column records whether the customer made a claim in the previous year or not. The client has informed you that the other columns should be self-explanatory.
 
 [Dataset](https://www.kaggle.com/racholsan/customer-data)
  
## Raw Data Link

https://github.com/TejaswiNallavolu/map-reduce-nallavolu/blob/main/Piping/customer-data.csv

## Data chart
The proportion of people as per their driving experience is clearly demonstrated in the below pie chart.

## Commands
cat customer-data.csv | python 22mapper.py > out.txt

cat customer-data.csv | python 22mapper.py | sort | python 22reducer.py > TejuOut.txt


![chart](https://github.com/TejaswiNallavolu/map-reduce-nallavolu/blob/main/Piping/PieChart.JPG)
