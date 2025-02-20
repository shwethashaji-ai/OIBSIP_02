# 🏋️ BMI Calculator - README

## 📌 Overview
The `bmi.ipynb` file is a **Graphical BMI (Body Mass Index) Calculator** built using **Python's Tkinter** library. It allows users to enter their weight and height, calculates their BMI, categorizes the result, and stores it in an SQLite database. Additionally, it provides a **visual history** of BMI records using Matplotlib.

---

## 🚀 Features
✅ **User Input:** Enter weight (kg) and height (cm) easily via the GUI.
✅ **BMI Calculation:** Automatically computes BMI with the formula: `BMI = weight / (height^2)`.
✅ **Category Classification:** Displays BMI category (Underweight, Normal, Overweight, Obese).
✅ **Data Storage:** Saves BMI history in an SQLite database for tracking.
✅ **History Visualization:** Generates a graphical plot of past BMI records.
✅ **Graphical Interface:** Simple and interactive Tkinter-based UI.

---

## 🛠️ File Contents
📌 **Code Cells:** Python scripts for BMI calculation, database handling, and GUI functionality.
📌 **Tkinter GUI:** Input fields, buttons, and labels for seamless interaction.
📌 **Matplotlib Graphs:** Visual representation of BMI history.

---

## 🎯 How to Use
1️⃣ Open `bmi.ipynb` in **Jupyter Notebook** or **JupyterLab**.
2️⃣ Run all cells to launch the **BMI Calculator GUI**.
3️⃣ Enter weight & height, then click **"Calculate BMI"**.
4️⃣ View your **calculated BMI & category**.
5️⃣ Click **"Show History"** to see your **past BMI records** visually.

---

## 📌 Requirements
Ensure you have the following Python libraries installed:
📌 `tkinter` - For GUI interface
📌 `sqlite3` - For database storage
📌 `matplotlib` - For visualizing history
📌 `datetime` - For date tracking

🔹 Install missing libraries using:
```bash
pip install matplotlib
```

---

## 💡 Suggested Improvements
✨ Enhance UI design for a more modern look.
✨ Improve error handling for invalid inputs.
✨ Implement user authentication for tracking individual histories.

---

## 📜 License
This project is **open-source** and can be used/modified for **educational and personal purposes**. 

