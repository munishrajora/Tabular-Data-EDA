# Tabular-Data-EDA


Project Title: <EDA And Model Guide Line>
Date: <10/30/2020>
------------------------------------------------
  
EDA Guidelines
----------------
  1.	Structure of data
  
  2.	Initial Insights
  
      1.	Number of samples	
      2.	Number of attributes	
      3.	Number of attributes of each data-type Float , string int etc.
      4.	Statistics on each attribute (min, max, mean, etc.)
      5.	Categorical/quantitative data fields
      6.	Missing attributes

  3.	Data sample
  
  4.	Data Labels
  
        •	Categorical/Regression
        
        •	if Categorical:
        
          classes : class1 , class2 , class3
          
        •	Distribution 
          Class name | Number of samples | % of data
          -----------|-------------------|---------
          class1 | 150 | 30
          class2 | 100 | 20
          class3 | 250 | 50
          
    
  ML-Model Guidelines
  -----------------------
  
    a)	Train-test split process
    
          -	70%-30% train-test split
          -	Stratified split 

    b)	Other pre-processing
    
        -	Cleaned the col4: how
        -	Modified the col7: clip the values in range [0,1]
        -	Apply min-max normalization
        -	Categorical variable, Col11, is converted to embedding vector for classification.
    
    c)	Evaluation metric (Which performance measurement is used)
    
          o	Classification
              Accuracy 
              AUC/ROC
              Precsion 
              recall 
              F1 
              Kappa

        
         o Regression
            MSE
            RMSE
            MPE
            MAPE
      
      
    
    d)	Model params
    
    -   RF is used with parameters n_estimators = 50, criterion = entropy, rest default
    
    
    f)	Results
    
    -	Confusion matrix
    -	Performance measure (accuracy, f1-score, precision, etc.)





