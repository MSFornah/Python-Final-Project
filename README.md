

# 🦠 COVID-19 Data Tracker

This is a Python project that tracks and analyzes global COVID-19 data. It allows users to explore and visualize up-to-date statistics using data sourced from **Our World in Data**.

## 📊 Features

- Reads real COVID-19 data from a CSV file.
- Displays COVID-19 statistics by country.
- Allows filtering and sorting of data.
- Includes basic data analysis and optional visualizations.

## 📂 Dataset Required

This project depends on a dataset that is **not included in the repository** due to GitHub’s file size limits.

To run the project, **please download the dataset manually**:

👉 [Download owid-covid-data.csv](https://covid.ourworldindata.org/data/owid-covid-data.csv)

Once downloaded, **place the file in the same folder** as `covid19-data-tracker.py`.

## ▶️ How to Run

1. Ensure you have Python 3 installed.
2. Make sure the CSV file is in the same directory as the script.
3. Open a terminal or command prompt in the project folder.
4. Run the script using:

python covid19-data-tracker.py


## 🔧 Requirements

This project uses the following Python libraries:

* `pandas` – for data manipulation
* `matplotlib` – for plotting (if visualization is included)

You can install them using:

pip install pandas matplotlib


## 🧠 How It Works

* The script reads the `owid-covid-data.csv` file using `pandas`.
* It allows users to select a country and view key statistics.
* It can generate summary outputs or plots (depending on your implementation).
* It serves as a basic COVID-19 data explorer for educational purposes.

## 📁 Project Structure
```
Python-Project/
├── covid19-data-tracker.py       # Main Python script
├── README.md                     # Project documentation
└── .gitignore                    # Ensures large dataset is not tracked
```

## 🚫 License

This project is for educational use only and may not be redistributed for commercial purposes.

## 👤 Author
* **Mohamed Shuaib Fornah**

*[(https://github.com/MSFornah)](https://github.com/MSFornah)

```


