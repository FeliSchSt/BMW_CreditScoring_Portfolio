Dear Sir or Madam,                                                                                                


in this project I demonstrate my understanding of

1. Credit Scoring methods
2. Data Science methods (Python libraries: Pandas, NumPy, Seaborn,  Matplotlib, Scikit-learn) 

The overall objective is to create a credit scoring system for sample data. The steps I took follow https://www.investopedia.com/terms/c/credit_score.asp. Note that I did not do in-depth research to verify the assumptions (even though I am aware of general guidelines like https://thedocs.worldbank.org/en/doc/935891585869698451-0130022020/original/CREDITSCORINGAPPROACHESGUIDELINESFINALWEB.pdf. Also note that I had to make a range of assumptions. I am aware that in a 'real-world' context, most of them are not valid. However, this exercise serves to show you my approaches to problem-solving. Therefore, making strong assumptions is deemed acceptable.

There are four sub-projects that build on one another. Please go through them in the order of their names (the first integer is indicative).

The sub-projects are as follows:

1. Create a registry of customers by means of object-oriented programming (OOP):

- I generated 1000 random instances with certain logical limitations. The parent class contains general information on the customers. The child class contains information that is important for credit scoring. This sub-projects not only shows my knowledge in OOP, but also my analytical thinking and making assumptions when simulating bank-related data.
    
2. Visualize the generated customer data:

- I generate visual insights by plotting grouped data. I use the personal information data of the customers and rating data that originates from sub-project 3.

3. Develop a Credit Score ranging from 300 to 850:

- First, I prepare the dataset so that it can be processed, for example encode categorical data and streamline the dataset so that all necessary parameters are present. Then I compute credit scores by scaling the data,  applying weights, calculating the sum of each weighted parameter and scaling it to the range between 300 and 850.

4. Model and validate a predictive Random Forest model:

- I prepare and simplify the data so that it can be easily fit to a Random Forest Classification model.I find the best parameters for the model by means of hyperparameter tuning. I check for performance metrics like accuracy and ROC score. I check the learning curve to understand which train-test-validation split is most appropriate for the data at hand. Lastly, I predict new observations and consider whether the predictions make sense.
    
    
Sincerely,

Felicitas Schulze-Steinen (London, 16.08.2023)

