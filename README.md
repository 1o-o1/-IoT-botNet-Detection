# IoT-botNet-Detection
Multi-class Machine Learning classifiers to Detect
IoT botnet attacks

This dataset addresses the lack of public botnet datasets, particularly for the Internet of 
Things. It suggests real-world traffic statistics collected from 9 commercial IoT devices
 infected with Mirai and BASHLITE. Since the dataset consists of CSV files, in pre-processing
stage, first - different types of csv files read. after that, we divided the csv file into 10 attacks
carried by 2 botnets. Next step, shuffle the whole dataset and distinguish outputs from inputs.
Normalization and one-hot encoding have been applied to label multiple classes. After 
finishing the preprocessing, ML classifiers used for multi-class classification. As a matter
 of fact, The dataset can be used for multi-class classification : 10 classes of attacks
 plus one class of benign. Number of Instances of the dataset is 7062606, while the "Real
number of attributes" are 115.
