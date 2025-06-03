# Netflix_Data_Insights

## 🚀 Overview

This project delves into my family's Netflix viewing activity to uncover fascinating habits, trends, and patterns. It serves as a practical application of data engineering and data science principles, focusing on building a robust data pipeline to extract, transform, load (ETL), and analyze personal viewing data.

## 🎯 Objectives

* **Simulate an ETL process:** Practice and demonstrate foundational data engineering skills by processing raw Netflix activity data.
* **Analyze viewing patterns:** Uncover insights into content preferences, peak viewing times, and duration trends across different profiles.
* **Visualize data insights:** Create clear and **interactive** visualizations to present findings, making complex data easily understandable.

## 🛠️ Technologies & Tools

* **Python:** The core programming language for data manipulation and analysis.
* **Pandas:** Essential for efficient data loading, cleaning, and transformation.
* **NumPy:** For numerical operations within data analysis.
* **Matplotlib & Seaborn:** For static data visualizations.

## 📊 Key Insights

This project summarizes approximately four years of Netflix activity, from early 2022 to mid-2025.

### Movies & TV Shows

* **Total watch time:** Over 2250 hours of content watched, with a strong preference for TV shows.
* **Content preference:** My family generally watches more TV shows than movies.
* **My personal top content:**
    * **Longest (re)watched movie:** "The Patriot"
    * **Longest (re)watched TV shows:** "Love, Death & Robots" and "Turning Point: The Bomb and the Cold War"
* **Family favorites:** "All Quiet on the Western Front" is the most (re)watched movie across the family.
* **Viewing habits:** The analysis reveals popular viewing times for different family members and their content preferences (movies & mobile games).
* **Unusual activity explained:** Insights into peculiar viewing patterns, such as the mysterious early morning activity for one profile, suggest potential background playback or accidental starts rather than active viewing.

### Mobile Games

* **Favorite games:** "Cats & Soup" is a family favorite, while "Dead Cells" (my preferred game) boasts over 25 hours of gameplay.
* **Peak gaming times:** Most game sessions occur in the morning, evening, and during lunchtime.

## 📈 Visualizations

Below are some of the visualizations generated in this project, showcasing various aspects of the Netflix viewing data.

### Movies & TV Shows visualizations

* **Most (re)watched films (hours) across family**
    ![Most (re)watched films (hours) across family](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/most_rewatched_films.png)


* **Netflix viewing sessions by day of week**
    ![Netflix Viewing Sessions by day of week](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/day_of_week_sessions.png)


* **Total Netflix watching time (hours) by year and month**
    ![Total Netflix watching time (hours) by year and month](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/year_month_watching_time.png)


* **Netflix viewing sessions per year**
    ![Netflix Viewing Sessions per year](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/per_year_sessions.png)


* **Netflix viewing sessions by hour of day (by profile)**
    ![Netflix Viewing Sessions by Hour of Day (by Profile)](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/hour_of_day_sessions.png)

### Top TV Shows per profile

This section presents the top 5 most-watched TV shows for each family member by total watch time, providing detailed insights into individual preferences.

```
Top 5 Most Watched TV Shows for Each User Profile (by total time):
================================================================================
Profile: Denis
--------------
  - Turning Point: 10h 18m
  - Love, Death & Robots: 06h 55m
  - The Gentlemen: 06h 32m
  - BLUE EYE SAMURAI: 06h 26m
  - Arcane: 06h 03m
================================================================================
Profile: Parker
------------
  - Sprzątaczka: 08h 38m
  - Żmijowisko: 06h 01m
  - Heartstopper: 03h 26m
  - Johnny English: 01h 24m
  - Przeznaczenie: 00h 12m
================================================================================
Profile: Pelikan
---------------
  - Wikingowie: 26h 21m
  - Sex Education: 20h 47m
  - Stranger Things: 13h 55m
  - House of Cards: 09h 16m
  - Wednesday: 08h 58m
================================================================================
Profile: Pilot
----------------
  - Orange Is the New Black: 86h 07m
  - Outlander: 77h 27m
  - The 100: 68h 23m
  - Kochane kłopoty: 63h 10m
  - Sześć stóp pod ziemią: 53h 33m
================================================================================
```
### Games Visualizations

* **Total Netflix game time per profile**
    ![Total Netflix Game Time Per Profile](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/game_time_per_profile.png)

* **Top 10 games by total play time**
    ![Top 10 Games by Total Play Time](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/total_play_time.png)

* **Netflix game sessions by hour of day**
    ![Netflix Game Sessions by Hour of Day](https://github.com/Denis2999/Netflix_Data_Insights/blob/main/img/sessions_in_a_day.png)

## 📦 How to replicate

To run this analysis and generate the insights yourself, follow these steps:

1.  **Download Your Netflix Data:**
    * Log in to your Netflix account and go to the "Account" page or directly follow this address: [https://www.netflix.com/account/security](https://www.netflix.com/account/security).
    * In the "Access and Privacy" section, click on "Personal info access."
    * Click the "Submit request" button at the bottom of the page. You will receive an email from Netflix to accept the terms for downloading personal information.
    * After some time (it can take up to half a day), you will receive another email with a link to download your data.
    * Locate the `ViewingActivity.csv` file within the downloaded data archive.

2.  **Project Setup:**
    * Clone this GitHub repository to your local machine.
    * Place the `ViewingActivity.csv` file (and potentially `Games.csv` if available) into the main project directory.
    * **Create a virtual environment** (highly recommended) for dependency management:
        ```bash
        python -m venv venv
        source venv/bin/activate  # On Windows: venv\Scripts\activate
        ```
    * **Install required packages** from `requirements.txt`:
        ```bash
        pip install -r requirements.txt
        ```

3.  **Run the Analysis:**
    * Open the Jupyter Notebook (e.g., `Netflix_Data_Insights.ipynb`) in your preferred environment.
    * Run all cells to execute the data processing, analysis, and visualization steps.
