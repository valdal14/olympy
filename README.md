# 🏅 Olympy

> **Mining for gold in Olympic history with Python and pandas.**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)

**Olympy** is a data analysis project that explores the history of the Olympic Games. By leveraging the power of **pandas**, this repository wrangles, cleans, and visualizes historical datasets of athletes, events, and medals to uncover trends in sporting performance over the decades.

---

## 📖 Table of Contents
1. [About the Project](#-about-the-project)
2. [Dataset](#-dataset)
3. [Getting Started](#-getting-started)
4. [Project Structure](#-project-structure)
5. [Technologies Used](#-technologies-used)
6. [Contributing](#-contributing)
7. [License](#-license)

---

## 🧐 About the Project

The modern Olympic Games have generated a massive amount of data regarding athlete demographics, country performance, and event evolution. This project aims to answer questions such as:

* Which countries dominate specific sports?
* How has the participation of women changed over time?
* What is the age distribution of gold medalists?
* How do physical attributes (height/weight) correlate with success in different disciplines?

---

## 📊 Dataset

The analysis is based on historical Olympic data (1896–Present).

* **Source:** [Link to Kaggle dataset or source](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
* **Description:** The dataset typically includes columns for `Name`, `Sex`, `Age`, `Height`, `Weight`, `Team`, `NOC`, `Games`, `Year`, `Season`, `City`, `Sport`, `Event`, and `Medal`.

> **Note:** Due to file size limits, the raw `.csv` data is not included in this repo. Please download it from the source and place it in the `data/` folder.

---

## 🚀 Getting Started

### Prerequisites

* Python 3.x
* Jupyter Notebook or Google Colab

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/valdal14/olympy.git](https://github.com/valdal14/olympy.git)
    cd olympy
    ```

2.  **Install dependencies**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
    *(Or if you have a requirements file)*
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```

---

## 🛠 Technologies Used

This project relies on the following Python libraries:

* **[Pandas](https://pandas.pydata.org/)** – The core library for data manipulation and analysis.
* **[Matplotlib](https://matplotlib.org/)** – Used for creating static, animated, and interactive visualizations.
* **[Seaborn](https://seaborn.pydata.org/)** – A high-level interface for drawing attractive and informative statistical graphics.
* **[NumPy](https://numpy.org/)** – Fundamental package for scientific computing and array operations.
* **[Jupyter Notebook](https://jupyter.org/)** – Interactive environment for running code and documenting the analysis.

---

## 🤝 Contributing

Contributions make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  **Fork the Project**
2.  **Create your Feature Branch**
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3.  **Commit your Changes**
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4.  **Push to the Branch**
    ```bash
    git push origin feature/AmazingFeature
    ```
5.  **Open a Pull Request**
