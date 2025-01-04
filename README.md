# Property Click Prediction

## **Overview**  
This project develops a predictive model to estimate property interactions using NoBroker's dataset. The study explores factors influencing interactions on properties, aiming to forecast user interactions within predefined timeframes.  

## **Datasets**  
1. **`property_data_set.csv`**: Details about properties (e.g., activation date, BHK type, size, rent, etc.).  
2. **`property_photos.tsv`**: Photo metadata requiring JSON correction for extracting photo counts.  
3. **`property_interactions.csv`**: Interaction timestamps indicating user engagement.  

## **Process**  
1. **Data Cleaning**: Resolved missing values and corrected malformed JSON strings for photo metadata.  
2. **Feature Engineering**: Created new variables like photo counts and interaction counts.  
3. **Exploratory Data Analysis**: Visualized relationships between property attributes and interactions.  
4. **Model Building**: Used statistical and machine learning models to predict interactions within 3 and 7 days of activation.  

## **Key Results**  
- **Model Accuracy**: Achieved precise interaction predictions for the 3-day and 7-day windows.  
- **Feature Insights**: Identified key drivers such as the number of rooms available, furnishing type, lease type, and parking.  
- **Enhanced Features**: Successfully extracted photo counts by correcting corrupted JSON data and was used as a feature.  

