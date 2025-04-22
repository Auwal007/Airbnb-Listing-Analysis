# 🏡 Exploring Airbnb Market Trends

This project explores market trends in Airbnb listings using a real-world dataset provided by [DataCamp](https://www.datacamp.com/). The goal is to analyze review activity, room types, and pricing to extract key insights.

## 🔍 What I Did

- Loaded and explored the three `.tsv`, `.csv` and `.xlsx` dataset of Airbnb listings.
- Cleaned the data and converted relevant columns to appropriate data types.
- Identified the **earliest** and **most recent** review dates.
- Counted how many listings are **private rooms**.
- Calculated the **average listing price**, rounding it to two decimal places.
- Combined all insights into a single summary `DataFrame`.

## 📊 Summary Output

| first_reviewed | last_reviewed | nb_private_rooms | avg_price |
|----------------|---------------|------------------|-----------|
| 2019-01-01     | 2019-07-09    | 11356            | 141.78    |

## 📁 Files

- `notebook.ipynb`: Jupyter notebook containing all code and explanations.
- `data`: folder containing all dataset used in the project.
- `image`: folder that contains the New York city image used in the beginning of the notebook.
- `README.md`: Project summary and context.

## 📝 Credits

This project is based on the **"Exploring Airbnb Market Trends"** project on [DataCamp](https://projects.datacamp.com/projects/1589), designed to practice real-world data analysis skills using Pandas in Python.

---

Feel free to edit or expand the analysis to make it your own!
