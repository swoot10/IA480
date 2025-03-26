### Data Source
The data source, selected from [Data.gov](https://www.data.gov/) and provided by the District of Columbia, reflects **2024 crime incidents in DC**. The dataset includes variables like **type of offense, block, district, neighborhood, time, and method**.  

### Research Question  
The model aims to answer:  
> *What type of crime is likely to happen based on variation of variables (district, neighborhood, time of day, etc.)?*  

### Target Variable & Predictors  
- **Target Variable:** `OFFENSE` (Type of offense committed)  
- **Key Predictor Features:**  
  - `block`  
  - `district`  
  - `time of day`  
  - `neighborhood`  
  - `voting precinct`  

### Data Cleaning  
- Variables containing `'id'` (e.g., `CCN` and `OBJECTID`) were removed.  

### Model Performance  
- **Accuracy:** *57.9%*  
- The model predicted the most likely offense and provided probabilities for each potential offense.  
- Future improvements could involve **more data cleaning** to refine the model and increase accuracy.  
