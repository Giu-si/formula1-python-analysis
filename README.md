# Formula 1 – Driver & Team Performance Analysis (Season 2008)

🏎️ This Python project analyzes the 2008 Formula 1 World Championship using real race data. It provides insights into the performance of drivers and constructors throughout the season.

## 📄 Dataset

Dataset used: [`formula1_data.csv`](https://proai-datasets.s3.eu-west-3.amazonaws.com/formula1_data.csv)

It contains:
- `Driver`: name of the driver
- `Team`: constructor/team name
- `Race`: city where the Grand Prix took place
- `Country`: country of the Grand Prix
- `Position`: position reached (0 = no points)

### 🏁 Scoring system
- 1st place: 10 pts  
- 2nd: 8 pts  
- 3rd: 6 pts  
- 4th–8th: from 5 to 1  
- 9th or lower: 0 pts

---

## 🎯 Objectives

The project implements the following:

### 1. **Driver Performance Analysis**
- Function that returns total points, number of victories, and podiums for a given driver.

### 2. **Final Driver Standings**
- Creates a dictionary with total points per driver
- Saves the results to a `.txt` file

### 3. **Constructor Rankings**
- Calculates total points per constructor based on their drivers' results

---

## 🔧 Technologies Used

- **Python 3**
- pandas
- File I/O (`.txt`)
- Dictionary operations, custom functions

---

## 🔗 Author

👩 Giusi Russo – Data Analytics Student  
🎓 Project developed during Data Analytics training – ProfessionAI  
