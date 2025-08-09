
## Features

* **Dataset Upload**

  * Load startup funding datasets in CSV format.
  * Displays column names, data types, null value counts, and a preview of the first rows.

* **Data Cleaning**

  * Standardizes column names.
  * Handles missing values and invalid formats (e.g., dates, amounts).
  * Ensures consistent text formatting for key columns.

* **Analysis**

  * Funding trends by year.
  * Top sectors, cities, and startups.
  * Most active investors.
  * Investment type distribution.

* **Visualization**

  * Funding trends over time.
  * Bar charts for top sectors, cities, startups, and investors.
  * Distribution of investment types.

* **Recommendations**

  * Predefined insights and suggestions based on data trends.

---

## Requirements

* Python 3.7+
* Install dependencies:

```bash
pip install pandas seaborn matplotlib
```

---

## How to Run

1. Save the script as `startup.py`.
2. Run the application:

```bash
python startup.py
```

3. Use the GUI buttons:

   * **Upload Kaggle Dataset** → Select your CSV file.
   * **Show Cleaning Steps** → View potential issues before cleaning.
   * **Clean Data** → Apply standard cleaning.
   * **Analyze Data** → Generate textual insights.
   * **Visualize Insights** → Show plots and graphs.
   * **Recommendations** → See suggested actions.



## Dataset Format

Expected columns (case-insensitive, spaces will be handled automatically):

* `Date`
* `Startup Name`
* `Industry Vertical`
* `City Location`
* `Investors Name`
* `Investment Type`
* `Amount in USD`

---

## Example Dataset Source

You can use datasets from:

* [Kaggle Startup Funding Dataset](https://www.kaggle.com/datasets)


