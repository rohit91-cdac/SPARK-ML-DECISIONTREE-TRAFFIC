# SPARK-ML-DECISIONTREE-TRAFFIC
Spark Ml - Decision Tree implementation To predict the the traffic for a particular route. 
The featture values include the day,month,time,minute,origin lat/long,destination lat/long, and Label
It implements Spark ML - Decision Tree Algorithm.
With the simple Decision Tree Alogrithm it was fount to have an error rate of 0.119
Spark Version is 2.0
Input Format is of the followin order:
[('Id', 'double'), ('Day', 'double'), ('Month', 'double'), ('Origin_longitude', 'double'), ('Origin_latitude', 'double'), 
('Destination_Longitude', 'double'), ('Destination_Latitude', 'double'), ('Total Distance', 'double'), ('Hour', 'double'), 
('Minute', 'double'), ('Speed in km/hr', 'double'), ('Label', 'double')]
