# 🧪 Exploring Higher-Order Functions in Python with Real Manufacturing Data

This project demonstrates how to use **higher-order functions** in Python, powered by real-world industrial data from an **electroless plating process**.

🔁 Higher-order functions are functions that:
- Take other functions as arguments, or
- Return functions as results

> 📁 Notebook: `EX_higher_order_functions.ipynb`  
> 📦 Dataset: `electroless_plating.pkl`

---

## 📌 What's Inside

The Jupyter notebook walks through:
- Python's built-in higher-order functions: `map()`, `filter()`, `reduce()`, `sorted()`
- Writing custom higher-order functions
- Creating functions that return other functions (closures)
- Using functions as inputs to dynamically apply filtering, transformation, and aggregation
- Real-world functional workflows like chain-of-operations, report generation, conditional filtering, and more

---

## 📊 About the Dataset: `electroless_plating.pkl`

This dataset is a rich source of **industrial quality control data** from an electroless plating facility. Each record contains:

- Batch ID and Operator ID  
- Plating Type (Nickel or Copper)  
- Bath Temperature (°C)  
- pH Level  
- Adhesion Strength (MPa)  
- Surface Roughness (Ra μm)  
- Phosphorus Content (%)  
- Inspection and Test Results  

⚙️ The dataset is ideal for learning higher-order functions because:
- It contains **diverse data types** (strings, floats, Booleans)
- It supports **record-wise operations** as well as **aggregate computations**
- It mirrors **real QA practices** such as pass/fail filtering, metric thresholds, and multi-field reports

---

## 🚀 How to Use

1. Clone the repository or download the files
2. Install dependencies (just Python standard libraries)
3. Launch the notebook:
   ```bash
   jupyter notebook EX_higher_order_functions.ipynb
