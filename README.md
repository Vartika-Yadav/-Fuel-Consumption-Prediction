# Fuel Consumption Prediction

This project demonstrates predicting vehicle fuel consumption using **Linear Regression** and **Logistic Regression**.  
It is designed to show how continuous and categorical predictions can be made from the same set of vehicle features.

---

## Features Used

- Engine Capacity (cc)
- Vehicle Weight (kg)
- Mileage (km/l)
- Average Speed (km/h)

---

## Objectives

1. **Linear Regression** – Predict the fuel consumption in L/100 km.
2. **Logistic Regression** – Classify whether a car has high (>8 L/100 km) or low (≤8 L/100 km) fuel consumption.

---

## Dataset

A sample dataset is included in the notebook:

| Engine_CC | Weight_KG | Mileage_KMPL | Avg_Speed_KMPH | Fuel_Consumption_L100KM | High_Consumption |
|-----------|-----------|--------------|----------------|------------------------|-----------------|
| 1000      | 900       | 20           | 50             | 5.0                    | 0               |
| 1200      | 950       | 18           | 55             | 5.5                    | 0               |
| 1500      | 1100      | 15           | 60             | 6.5                    | 0               |
| 1600      | 1200      | 14           | 65             | 7.0                    | 0               |
| 1800      | 1300      | 12           | 70             | 8.0                    | 0               |
| 2000      | 1500      | 10           | 75             | 9.0                    | 1               |
| 2200      | 1600      | 9            | 80             | 10.0                   | 1               |
| 2500      | 1800      | 8            | 85             | 11.0                   | 1               |
