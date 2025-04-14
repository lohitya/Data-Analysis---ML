# Used Cars Price Analysis

Project Overview:

This project presents an exploratory data analysis (EDA) of used car prices, aiming to uncover key factors that influence vehicle pricing in the second-hand market. By examining variables such as ownership history, fuel type, transmission, and vehicle age, the analysis provides insights valuable to both buyers and sellers.

Dataset Description:

The dataset comprises detailed information on used cars, including:

    Brand and Model: Identifies the manufacturer and specific model of each vehicle.​
    
    Year: The manufacturing year of the car.​
    
    Driven: Total distance the car has traveled, typically measured in kilometers or miles.​
    
    Fuel Type: Type of fuel the car uses, such as Petrol, Diesel, or Hybrid/CNG.​
    
    Transmission: Indicates whether the car has a manual or automatic transmission.​
    
    Owner Type: Denotes the number of previous owners (e.g., First, Second).
    
    Ask Price: The listed price of the used car


Source : Kaggle


Libraries used:

    Pandas,
    
    seaborn,
    
    matplotlib,
    
    plotly


# Business Insights:

This project explores the factors influencing used car prices, focusing on ownership history and fuel type. The key findings are:

1. Ownership History Impacts Price
  - First Owner Vehicles: Median price ~0.79 million​
  
  - Second Owner Vehicles: Median price ~0.67 million​

Insight: Vehicles with a single owner retain higher value, suggesting that ownership history is a significant determinant of resale price.​

2. Fuel Type Influences Valuation
  - Diesel Vehicles: Highest median price (~0.866 million)​
  
  - Hybrid/CNG Vehicles: Lower median price (~0.63 million) with notable outliers​
  
  - Petrol Vehicles: Median price (~0.70 million) with some high-priced outliers​

Insight: Diesel vehicles command higher prices, possibly due to fuel efficiency and durability. The variability in hybrid/CNG and petrol vehicle prices indicates other factors, such as model year or brand, may also play roles.​

3. Combined Effect of Ownership and Fuel Type
- Second-owner hybrid/CNG vehicles exhibit significantly lower ask prices compared to other combinations.​

Insight: This trend may reflect concerns about battery longevity or maintenance costs in older hybrid models, affecting their resale value.​

4. Correlation Analysis

- Transmission and Ask Price: Negative correlation (-0.28). This suggests that manual transmissions are associated with lower prices, possibly due to consumer preference for automatics.​

- Owner and Ask Price: Negative correlation (-0.24). Indicates that vehicles with more previous owners tend to have lower prices.​

- Age and Ask Price: Negative correlation (-0.55). Highlights that older vehicles are priced lower, aligning with typical depreciation trends.
  



    



