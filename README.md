# Python-Basics-and-Control-Flow

# 📊 Student Grade Tracker

A Python-based student grade tracking system built using Jupyter Notebook. This project demonstrates data cleaning, grade calculation, and class performance analysis using core Python concepts — no external libraries required.

---

## 📁 Project Structure

```
📦 student-grade-tracker
 ┗ 📓 part1_grade_tracker.ipynb
```

---

## 📌 Features

### ✅ Task 1 — Data Cleaning & Validation
- Strips whitespace and normalizes student names to Title Case
- Converts roll numbers from strings to integers
- Parses comma-separated marks strings into lists of integers
- Validates that names contain only alphabetic characters
- Displays a formatted student profile for each record

### ✅ Task 2 — Individual Student Analysis
- Assigns letter grades per subject based on marks:
  | Marks | Grade |
  |-------|-------|
  | ≥ 90  | A+    |
  | ≥ 80  | A     |
  | ≥ 70  | B     |
  | ≥ 60  | C     |
  | < 60  | F     |
- Calculates total marks, average, highest and lowest scoring subjects
- Allows interactive addition of new subjects and marks via user input (with validation)

### ✅ Task 3 — Class Performance Summary
- Computes average marks and Pass/Fail result for each student (pass threshold: 60)
- Displays a neatly formatted results table
- Counts total passed and failed students
- Identifies the class topper with their highest average

---

## 🧑‍🎓 Sample Data

| Name          | Roll | Marks              |
|---------------|------|--------------------|
| Ayesha Sharma | 101  | 88, 72, 95, 60, 78 |
| Rohit Verma   | 102  | 55, 68, 49, 72, 61 |
| Priya Nair    | 103  | 91, 85, 88, 94, 79 |
| Karan Mehta   | 104  | 40, 55, 38, 62, 50 |
| Sneha Pillai  | 105  | 75, 80, 70, 68, 85 |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation & Run

```bash
# Clone the repository
git clone https://github.com/your-username/student-grade-tracker.git

# Navigate into the project folder
cd student-grade-tracker

# Launch Jupyter Notebook
jupyter notebook part1_grade_tracker.ipynb
```

> Run each cell sequentially from top to bottom for correct output.

---

## 🛠️ Built With

- **Python 3** — Core logic and data processing
- **Jupyter Notebook** — Interactive development environment

---

## 👩‍💻 Author

**Your Name**  
[GitHub](https://github.com/your-username) • [LinkedIn](https://linkedin.com/in/your-profile)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).ep
