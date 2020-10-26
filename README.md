# Exploratory data analysis and feature extraction with Python on Titanic dataset

Overview :
Exploratory data analysis is one of the most important step for any data science , 
Machine Learning project. Here, I will do  the analysis of titanic dataset. I am going to 
try to cover most basics of EDA with the help of libraries like pandas, Seaborn and 
matplot library.  The RMS Titanic was a British passenger liner that sank in the North 
Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an 
iceberg during its maiden voyage from Southampton to New York City. There were an 
estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making 
it one of the deadliest commercial peacetime maritime disasters in modern history. 

Data set:
You can download and read about the data set by going through this link https://www.kaggle.com/c/titanic/data
This data set consists Information about the passengers of RMS Titanic ship And also have info about is that particular passenger is survived in that disaster or not. For every individual person we have information about —

1.	Passenger Id- Id number of passenger in data set
2.	Name- Name of the passenger
3.	Survival- Person survived or not ( 0 for No & 1 for Yes)
4.	Pclass- With what class of ticket that passenger was travelling.
5.	sex- Male Or Female
6.	Age- Age of the person in Years
7.	Sibsp- Number of siblings / spouses on the Titanic
8.	parch- Number of parents / children on the Titanic
9.	Ticket- Ticket number
10.	Fare- Amount of money that person paid to travel
11.	Cabin- Cabin Number of Passenger
12.	Embarked- Port of Embarkation ( C = Cherbourg, Q = Queenstown, S = Southampton)


Content of EDA :
 1. Loading the data
   2. Describe the data
   3. Feature Extraction (Countplot, Histograms , PDF & CDF)
         1. Feature 1: Survived
         2. Feture 2 : Sex
         3. Feature 3: Pclass
         4. Feature 4: Age
         5. Feature 5: Parch
         6. Feature 6: Fare
         7. Feature 7 :Embarked
   4.Graphical Bi-variate Analysis  
   5. Mean,Median,  Percentile, Quantile, IQR, MAD and Std-dev(Only three features)
         5.1. Age
             5.1.1.Box plot and Whiskers 
             5.1.2.Violin plot 
         5.2. Fare
             5.2.1.Box plot and Whiskers 
             5.2.2.Violin plot
         5.3  Pclass
             5.3.1.Box plot and Whiskers  
             5.3.2.Violin plot
   6. Correlation Matrix
