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

    Pandas, seaborn, matplotlib, plotly

**1. How does ownership history affect resale pricing?**

Insight: First-owner vehicles retain significantly higher value (median ~0.79M) compared to second-owner cars (~0.67M). This suggests that ownership history is a significant determinant of resale price.​

Recommendation: Sellers should highlight first-owner status as a premium feature, while buyers can use ownership history to negotiate value.

**2. Which fuel types offer the highest resale value in the second-hand market?** 

Insight: Diesel vehicles command the highest median price (~0.866M), while hybrid/CNG  (~0.63 million), Petrol vehicles (~0.70 million) show lower and more varied prices. This could be due to possibly due to fuel efficiency and durability diesel vechicles offer. The variability in hybrid/CNG and petrol vehicle prices indicates other factors, such as model year or brand, may also play roles.​

Recommendation: Dealers should consider stocking more diesel models in demand-heavy regions, and clarify hybrid maintenance costs to boost buyer confidence.  

**3. What features most strongly influence price depreciation in used cars?** 

Insight:

- Transmission and Ask Price: Negative correlation (-0.28). This suggests that manual transmissions are associated with lower prices, possibly due to consumer preference for automatics.​

- Owner and Ask Price: Negative correlation (-0.24). Indicates that vehicles with more previous owners tend to have lower prices.​

- Age and Ask Price: Negative correlation (-0.55). Highlights that older vehicles are priced lower, aligning with typical depreciation trends.

- Second-owner hybrid/CNG vehicles exhibit significantly lower ask prices compared to other combinations.​ This trend may reflect concerns about battery longevity or maintenance costs in older hybrid models, affecting their resale value.​


Recommendation: Use these factors in pricing models to create competitive, data-driven listings, especially for budget-sensitive buyers.





    



