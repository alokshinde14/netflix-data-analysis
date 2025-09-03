# 🎬 Netflix Data Analysis

## 📌 Overview

This project explores the **Netflix dataset** to uncover trends in movies and TV shows using **Python (Pandas, Matplotlib, Seaborn)**.
The goal is to perform **exploratory data analysis (EDA)**, clean the dataset, visualize patterns, and draw insights about Netflix’s content strategy.

---

## 📂 Dataset

* Source: [Netflix Titles Dataset – Kaggle]
* Columns:

  * `show_id` – Unique ID for every show
  * `type` – Movie / TV Show
  * `title` – Name of the show
  * `director`, `cast`, `country`
  * `date_added`, `release_year`
  * `rating`, `duration`, `listed_in` (genre)
  * `description`

---

## ⚙️ Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 🔎 Analysis Performed

1. **Data Cleaning**

   * Handled missing values in `country`, `rating`, and `date_added`.
   * Converted `date_added` to datetime format.
   * Created new features: `year_added`, `month_added`, `duration_int`.

2. **Exploratory Data Analysis (EDA)**

   * Movies vs TV Shows distribution
   * Top 5 genres and countries
   * Content trends over the years
   * Ratings distribution across types
   * Pre vs Post Pandemic trends
   * Heatmap of content releases by month & year
   * Most frequent directors & actors

---

## 📊 Results & Insights

* Netflix has **more movies than TV shows**, but TV shows are steadily growing.
* The **USA and India** dominate content production.
* Popular genres include **Drama, Comedy, and International TV Shows**.
* Content additions increased rapidly after **2015**, with spikes around **2018–2020**.
* Majority of content is targeted at **teens and adults** (`TV-MA`, `TV-14`).
* A handful of **directors and actors** frequently collaborate with Netflix.

---

## 📌 Visual Summary

(Add screenshots of your best 3–4 charts here – e.g., Movies vs TV Shows, Genre distribution, Release trends, Heatmap)

---

## 🚀 Future Scope

* Perform **sentiment analysis** on descriptions.
* Build a **recommendation system**.
* Compare Netflix with **other OTT platforms** (Prime, Disney+).
* Explore **regional language content trends**.

---

## 🙌 Acknowledgements

* Dataset from Kaggle
* Inspiration: Codebasics, Netflix Data Challenges
