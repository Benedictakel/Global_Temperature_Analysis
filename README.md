# 🌡️ Global Temperature Analysis

This repository contains a **data analysis and visualization project** that explores how **global average temperatures** have changed over the past **100+ years**. It uses public climate datasets to generate insights and visualizations on historical temperature trends, highlighting global warming patterns.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Objectives](#objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Analysis Overview](#analysis-overview)
* [Visualizations](#visualizations)
* [Key Insights](#key-insights)
* [Project Structure](#project-structure)
* [Future Work](#future-work)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

Climate change is one of the most significant challenges facing humanity today. This project analyzes **historical temperature data** to:

✅ Observe long-term global warming trends

✅ Visualize year-to-year changes in average temperatures

✅ Raise awareness about the impacts of climate change through data-driven insights



## 📚 Dataset

* **Source:** [NASA GISTEMP]()
* **Data Format:** CSV
* **Data Includes:**

  * Year
  * Global mean temperature anomaly (relative to a baseline average)



## 🎯 Objectives

✔️ Load and preprocess global temperature data

✔️ Analyze yearly average temperature anomalies

✔️ Generate line plots showing temperature changes over the past century

✔️ Visualize temperature anomalies as heatmaps or bar charts

✔️ Identify periods of rapid temperature increases



## ✨ Features

* Data cleaning and preprocessing for analysis-ready format
* Calculation of rolling averages to smooth trends
* Visualization of:

  * Yearly temperature anomaly trends
  * Decadal average temperatures
  * Heatmaps showing temperature deviations



## 🛠️ Technologies Used

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Global_Temperature_Analysis.git
cd Global_Temperature_Analysis
```

2. **Create a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook
```



## ▶️ Usage

1. Open `Global_Temperature_Analysis.ipynb` in Jupyter Notebook.
2. Run the notebook cells sequentially to:

   * Load and preprocess data
   * Perform exploratory data analysis (EDA)
   * Visualize temperature trends over time
   * Generate insights on global warming patterns



## 📊 Analysis Overview

* **Data Preprocessing:** Handling missing values and converting units if required
* **Yearly Temperature Trend:** Line plots of annual anomalies over 100+ years
* **Decadal Analysis:** Average temperature changes by decade
* **Heatmap:** Temperature anomaly intensities by year and month (if data includes monthly breakdown)



## 📸 Visualizations

* 📈 **Line Plot:** Annual global temperature anomalies over time
* 🔥 **Heatmap:** Temperature anomalies by decade
* 📊 **Bar Chart:** Comparison of average temperatures across decades

> *(Screenshots coming soon)*



## 🔍 Key Insights

* 🌡️ There is a clear upward trend in global temperature anomalies over the past century.
* ⚠️ The rate of warming has accelerated significantly in the last few decades.
* ❄️ Periods of cooling are short-lived compared to prolonged warming trends.



## 📁 Project Structure

```
Global_Temperature_Analysis/
 ┣ data/
 ┃ ┗ global_temperature.csv
 ┣ Global_Temperature_Analysis.ipynb
 ┣ requirements.txt
 ┗ README.md
```



## 💡 Future Work

* Extend to **regional temperature analysis** (e.g. continents or countries)
* Create **animated visualizations** showing temperature changes over time
* Integrate with **CO2 emission datasets** to explore correlations
* Build a **Streamlit dashboard** to present results interactively



## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio](#)



### ⭐️ If you find this project useful, please give it a star and share with other data science and climate analysis learners!


