![topimage](https://user-images.githubusercontent.com/71023894/115910844-56ba2e80-a43b-11eb-8851-3fc48e0a68bc.png)


# Machine Learning Project: Predicting Airbnb Rental Prices
Our team aimed to predict major US and European cities' rental price based on US Airbnb rental price data using supervised learning methods. The main questions of interest are:

  1. Will the model trained on US data generalize to European cities? 
  2. What are the important features in predicting Airbnb prices? 

This model could be helpful to home and apartment owners trying to determine a good price for their listing, by offering an estimate of what similar units in the area are priced at, it helps to establish a baseline. On the renters end, having a price prediction can help them determine whether or not the apartment they are considering is a good deal or not. 

We see the benefits of this project reaching beyond just Airbnb, the same principles used in this project can be applied to a wide variety of real estate tech companies. Our model will likely be fairly easy to translate to companies like Zillow, traditional real estate agencies, and the countless real estate tech companies popping up working to improve the refinance of the mortgage industry. In a more general sense building an effective revenue boosting Machine Learning algorithm is applicable to virtually every company in the world. This will be a good way to integrate the machine learning topics from class to a real dataset.


## I. Data Sources
The final dataset was created by merging four different datasets - US Airbnb data (Washington, Chicago, LA, San Fransisco, New York), population by each city, geographical data to calculate the distance from city center to each Airbnb, and European data (Madrid, London, Paris). The data can be found here: http://insideairbnb.com/get-the-data.html


## II. Experimental Design 
![work-flow](https://user-images.githubusercontent.com/71023894/115911394-07c0c900-a43c-11eb-9fe3-1995c22ba37d.png)



## III. Final Model
After testing out five different models (Lasso, Random Forest, XGboost, Neural Net and KNN), we concluded that the best model is Random Forest based on R-squared and Absolute Median Error. 

![result](https://user-images.githubusercontent.com/71023894/115910152-7d2b9a00-a43a-11eb-990e-0504fd89dd65.png)




## IV. Getting Started

**Step 1: Clone the repo:**
```
git clone https://github.com/nikhil-bhargava/ids-705-final-project.git
```

**Step 2: Navigate your way into the repo:**
```
cd ids-705-final-project
```

**Step 3: Create virtual environment for project (pip or conda):**

**Step 4: Then install packages:**

Remember to install packages and add them to requirements.txt as you go along with the proper versions (pandas and numpy are already in there as an example).

```
pip install -r requirements.txt
```

