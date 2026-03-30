# COVID-19 Global Data Analysis Dashboard

This is a data analysis project I built to explore and visualize COVID-19 data across 188 countries using Python. I wanted to go beyond simple bar charts and actually create something that looks and feels like a real dashboard — with interactive maps, comparison charts, and a country-level deep dive for India.

---

## Why I Built This

I was curious about how the pandemic affected different parts of the world differently. Some countries had very high death rates, others had surprisingly strong recovery rates. I wanted to see that visually, not just read numbers in a table. So I picked up this Kaggle dataset and started exploring.

---

## What the Project Does

- Loads and cleans real COVID-19 data (188 countries)
- Shows a global summary — total confirmed, deaths, recovered, and active cases
- Plots an interactive **world map** where you can hover over any country
- Shows a **bubble map** where bubble size represents the number of cases
- Compares the **top 15 most affected countries** side by side
- Breaks down cases and deaths by **WHO Region**
- Does a focused **India analysis** — how India compares to the world average
- Plots **death rate vs recovery rate** to find patterns
- Ends with a clean printed summary report

---

## Tools & Libraries Used

- Python 3
- Pandas — for loading and cleaning the data
- NumPy — for calculations
- Matplotlib & Seaborn — for static charts
- Plotly — for interactive maps and charts
- Google Colab — where I ran everything

---

## Dataset

Downloaded from Kaggle:
**COVID-19 Dataset by imdevskp**
- File used: `country_wise_latest.csv`
- 188 countries, 15 columns
- Includes confirmed, deaths, recovered, active, new cases, WHO region and more

---

## How to Run It

1. Open [Google Colab](https://colab.research.google.com)
2. Upload the `covid19_dashboard_final.ipynb` file
3. Upload `country_wise_latest.csv` using the folder icon on the left
4. Click **Runtime → Run All**
5. That's it — all charts will appear one by one

---

## Some Interesting Things I Found

- The **USA** had the highest confirmed cases and deaths by a large margin
- **India** actually had a better recovery rate than the global average
- The **Americas region** as a whole was the most severely impacted WHO region
- Some smaller countries had very high death rates, likely due to limited healthcare
- The bubble map makes it really easy to see which regions were hit hardest at a glance

---

## Project Structure

```
covid19-data-analysis/
│
├── covid19_dashboard_final.ipynb   # Main notebook with all code and charts
├── country_wise_latest.csv         # Dataset from Kaggle
└── README.md                       # This file
```

---

## Author

**Lekkala Divakar**  
B.Tech — Computer Science Engineering (AI)  
ABR College of Engineering and Technology  

- GitHub: [github.com/divakarlekkala](https://github.com/divakarlekkala)  
- LinkedIn: [linkedin.com/in/lekkala-divakar-841290292](https://www.linkedin.com/in/lekkala-divakar-841290292)

---

*If you found this project useful or interesting, feel free to star the repo!*
