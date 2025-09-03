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

<img width="200" height="150" alt="Screenshot 2025-09-03 152743" src="https://github.com/user-attachments/assets/0b380b98-e086-4e52-a41d-ae946e460014" />   <img width="200" height="150" alt="Screenshot 2025-09-03 152814" src="https://github.com/user-attachments/assets/4e8fb3ff-2b7e-4f68-be4b-8430da848e82" />   <img width="200" height="150" alt="image" src="https://github.com/user-attachments/assets/8a1faaea-630e-4cef-ab42-d3c2269b66b2" />  <img width="200" height="130" alt="Screenshot 2025-09-03 153520" src="https://github.com/user-attachments/assets/83915c63-d243-4a0d-8eea-b96138a73df0" />


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
