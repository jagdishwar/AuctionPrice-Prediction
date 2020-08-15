#  AuctionPrice Prediction
Predicting Auction Price for IPL Players 
#### https://en.wikipedia.org/wiki/Ordinary_least_squares

* Multiple Linear Regression

  yi =β0+β1x i1+β2x i2 +...+βp x ip+ϵ


* Libraries
   
     >  numpy
    
     >   matplot
   
     >   pandas
   
     >  seaborn

* Multi-collinearity 

     Rx = R-squared value of this model
     
     VIF = 1/1-Rx^2
     
* HeatMap corr

  <img width="838" alt="Screenshot 2020-08-13 at 6 10 41 PM" src="https://user-images.githubusercontent.com/39494791/90136149-5a1bf700-dd91-11ea-8732-516e262129da.png">
  
  Here, 1.T-RUNS and ODI-RUNS are highly Correlated.
  
        2.ODI-WKTS and T-WKTS are highly Correlated.
        
        3.Batsman Features - RUNS-S,HS,AVE,SIXERS are highly Correlated.
        
        4.Bowler's Features - AVE-BL ,ECON and SR-BL are highly Correlated.

* R- Squared value 0.75 Training Dataset .
* R- Squared value 0.44 validation Dataset .
  
 
     
