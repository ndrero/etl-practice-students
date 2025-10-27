# Data Cleaning Project — `bi.csv`

## Overview

This project demonstrates a complete **data cleaning workflow** using Python and pandas, applied to a real-world messy dataset (`bi.csv`).
The dataset contains common issues such as inconsistent text formatting, typos, case variations, and missing values.

Main cleaning tasks include:

* Renaming inconsistent columns
* Replacing country name variations
* Normalizing gender, residence, and education values
* Filling missing exam scores based on business logic (students who missed the exam receive score `0`)

---

## Technologies Used

* **Python 3.x**
* **pandas** for data manipulation
* **re (Regular Expressions)** for text normalization
* **Jupyter Notebook** as the development environment

---

## Clone and Run

1. **Clone the repository**

```bash
git clone https://github.com/ndrero/etl-practice-students.git

cd etl-practice-students
```

2. **Install dependencies**

```bash
pip install pandas jupyter
```

3. **Run the notebook**

```bash
jupyter notebook
```

Then open `transform_students.ipynb` to view and execute the data cleaning steps.

---

## Author

**Andrei Carvalho**
Data Cleaning Challenge — `bi.csv`
Version 1.0

---

Would you like me to add a `requirements.txt` section for dependencies (so it installs everything automatically)?
