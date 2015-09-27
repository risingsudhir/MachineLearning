Executive Summary

Human Activity Recognition (HAR) is a research area to identify different activities based on the data recorded by various sensors. There are many potential applications for HAR, like: elderly monitoring, life log systems for monitoring energy expenditure and for supporting weight-loss programs, and digital assistants for weight lifting exercises.

This report is to build the prediction model that can predict the type of activity performed by a person, based on the data collected from sensors. Research data has been collected from here -
http://groupware.les.inf.puc-rio.br/har

The purpose of this investivgation is to identify "how (well)" an activity was performed by a person. The measurements are taken by on-body sensors, with five different set of activities. Participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E). Class A corresponds to the specified execution of the exercise, while the other 4 classes correspond to common mistakes. 

The model was built using random forest algorithm. This model has successfully predicted the correct class of the activties with 97.84% out of sample accuracy and 100% accuracy on the 20 test cases (measured by Coursera Practicle Machine Learning).

Data Analysis
The training data for this project are available here: 

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here: 

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

The data for this project come from this source: http://groupware.les.inf.puc-rio.br/har.