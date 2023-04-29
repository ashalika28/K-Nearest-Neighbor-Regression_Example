This is my solution for Kaggle Competition called Spaceship Titanic

# Here are few Sections

**1. Load Libraries**

    In here import relavant libraries and load dataset called 'California Housing'
    
**2. Look Dataset**

   Looking basic data of dataset
   Conduct EDA - Explortary Data Analysis
   

**3. Explotary Data Analysis**

    Conduct using pandas profilling library

**4. Pre Processing**

    Handle missing values
    Drop columns
    Handle outliers

**5. Feature Selection**

    Conduct feature selection with f_classif

**6. Create Model**

   define some functions:
   
   - def splitTrainTest(data,target): split data to train and test
   - def train_model(df, scaling=True,n_neighbors=20): Train Model
   - def lookEval(df): Conduct Evaluations

**7. Evaluations**

    This conduct in Serval manner. (Scaling ,Outliers)
    
    Pairs : Scaling False with outliers and without outliers
            Scaling True with outliers and without outliers
    

**8. Hyper Parameter tuning**

   Mainly used to hyper grids
   
   define some functions:
   
   - def HyperParameterTunig(train_data, train_target, hypergrid): Train model according to hypergrid
   - def printScore(score, params): Print best scores

**9.Get Prediction with best parameters**

    Save model for future use
    
 

