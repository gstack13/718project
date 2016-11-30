# 718project

Using an open source NBA shot data set from the 2015-2016 season, I wanted to see if I could make a model that could predict if Lebron James would make his next shot. Programing in Python, using Pandas and Sklearn I made a classifier using Gaussian Naive Bayes and presented the output in a confusion matrix. The model is able to predict at 61% accuracy that Lebron James will make his next shot based on the features I chose. It is far from a perfect model and the rest of my testing proves that. (See code for more testing and descriptive stats).


Using Hadoop's Hive and Zeppelin features I was able to create visualizations of many different interesting statistics. Such as how many field goals LeBron made based on how many dribbles he took or how long he touched the ball. (See the PGN for Zeppelin visualizations). The Zeppelin picture is shots made and missed based off of Lebron's time touching the ball, grouped by the closest defender.
