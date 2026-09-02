# IPL 2022 Data Analysis 🏏

This project is a simple data analysis of the **IPL 2022 season** using Python. The main goal was to explore the match data, understand team and player performances, and find some interesting patterns from the season.

I worked with the dataset using **Pandas** and used **Matplotlib** and **Seaborn** to visualize the results.

## 📊 About the Dataset

The dataset contains information about **74 IPL 2022 matches** with **20 columns**.

Some of the important columns include:

* Match ID and date
* Venue
* Teams playing the match
* Tournament stage
* Toss winner and toss decision
* First and second innings scores
* Wickets lost
* Match winner
* Winning margin
* Player of the Match
* Top scorer and highest score
* Best bowler and bowling figures

The dataset does not contain missing values in these columns.

## 🔎 What I Explored

In this project, I looked at questions such as:

* Which team won the most matches?
* How did teams perform throughout the season?
* What was the impact of the toss?
* Which players had the highest scores?
* Who performed well with the ball?
* How were matches won — by runs or wickets?
* How did teams perform in the playoffs and final?

The notebook also includes basic dataset inspection and visualizations to make the results easier to understand.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📁 Project Structure

```text
IPL-2022-Data-Analysis/
│
├── IPL-Project.ipynb
├── IPL.csv
└── README.md
```

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/IPL-2022-Data-Analysis.git
```

2. Open the project folder:

```bash
cd IPL-2022-Data-Analysis
```

3. Make sure Python and Jupyter Notebook are installed.

4. Open the notebook:

```bash
jupyter notebook IPL-Project.ipynb
```

5. Run the cells one by one.

Make sure `IPL.csv` is kept in the same folder as the notebook because the notebook reads the dataset using:

```python
pd.read_csv('IPL.csv')
```

## 📌 Project Status

This is a learning-based data analysis project created to practice **Exploratory Data Analysis (EDA), data handling and visualization with Python**.

## 👨‍💻 Author

**Aditya Sharma**

If you found this project useful or have any suggestions, feel free to explore the notebook and share your feedback.
