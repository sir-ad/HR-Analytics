
### HR-Analytics

#### Problem Statement

  Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

    . They first identify a set of employees based on recommendations/ past performance
    
    . Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
        
    . At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
    
    . For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 

They have provided multiple attributes around Employee's past and current performance along with demographics. 

Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

###### Feature Engineering 
  
  sum_performance = addition of the important factors for the promotion (awards_won;KpIs_met & previous_year_rating).
  
  Total nmber of training hours = avg_training_score * no_of_training
  
  recruitment_channel have no impact on the promotion so removed that.
  
###### Model Applied :
    
   Random Forest
   Adaboost
   Gradient Boosting
   Catboost
   
