# EV Charging Demand Prediction (Java Version)

This project simulates a basic EV charging demand prediction using a custom formula in Java.
It reads input from a file, applies a basic estimation rule, and prints the result.

## 💡 Logic
Estimated_Demand = (Previous_Day_Demand * 0.9) + (Temperature * 0.8)

## 📁 Files
- `EVDemandPrediction.java`: Java code file
- `EV_Demand_Input.txt`: Sample input data (prev_day_demand and temperature)
- `README.md`: Documentation

## 🔧 Run Instructions
1. Navigate to `src` folder
2. Compile: `javac EVDemandPrediction.java`
3. Run: `java EVDemandPrediction`

## 👨‍💻 Author
Akshit Chauhan
