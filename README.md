# Wine-Quality--Assignment
A machine learning model which uses regression techniques to predict the quality of wine based on various factors  

The data set contains the following attributes:  
-fixed acidity  
-volatile acidity  
-citric acid  
-residual sugar  
-chlorides  
-free sulfur dioxide  
-total sulfur dioxide  
-density  
-pH  
-sulphates  
-alcohol  
-quality  
We consider quality to be the independent variable and the rest to be dependent  
Box plots were drawn for the dependent variables which showed the extent of outliers which were later removed through winsorization.
First a simple linear regression model was built which had very less accuracy. The other models had slightly better accuracy but were lesser than 90%.
Then using the concept of multiple regression we were able to achieve 98% accuracy.
