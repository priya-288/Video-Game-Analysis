# Video-Game-Analysis

This project explores video game sales data to identify trends in sales, regional performance, and genre popularity using data analysis and visualization. Built using Python, Pandas, Matplotlib, and Seaborn, it demonstrates key exploratory data analysis techniques on a real-world dataset.

---

##  Problem Statement

This project helps analyze video game sales data to understand market trends, player preferences, and regional performance. It helps identify which genres, consoles, and games are most successful and how critic scores influence sales.

Through this analysis, we can determine:

* Which genres are most popular
* Which regions contribute the most to sales
* Whether critic scores impact game success
* Which games perform differently across regions

---

##  Steps Followed

* Step 1 : Loaded dataset into Python (CSV file).
* Step 2 : Performed data cleaning:

  * Checked missing values
  * Handled null values
  * Verified data types
* Step 3 : Conducted exploratory data analysis (EDA).
* Step 4 : Created new aggregated columns like total sales where required.
* Step 5 : Grouped data by:

  * Genre
  * Console
  * Year
  * Region
* Step 6 : Filtered top 10 games based on total sales for focused analysis.
* Step 7 : Compared regional sales (NA, EU, JP, Others).
* Step 8 : Created multiple visualizations:

  * Bar charts
  * Line plots
  * Scatter plots
* Step 9 : Analyzed relationship between critic score and total sales.
* Step 10 : Interpreted results to extract insights.

---

### Key Analysis Performed

#### 1. Top Games Analysis (Sales by Title)
* Compared total sales across different game titles
* Found that:
  * Grand Theft Auto, Call of Duty: Black Ops, and Call of Duty: Modern Warfare 3 are the highest-selling game titles

<img width="1182" height="805" alt="Image" src="https://github.com/user-attachments/assets/9e3195be-adbc-4ae3-a0fb-2683a4f05173" />

#### 2. Genre Analysis

* Compared total sales across genres
* Found that:

  * Action, Sports, Shooter → highest sales
  * Adventure, Simulation → lowest sales

<img width="1014" height="596" alt="Image" src="https://github.com/user-attachments/assets/fa8ea368-8723-4164-841b-d6ca9ca48af4" />
---

#### 3. Sales Trend Analysis

* Analyzed sales trends over time
Found that:
 * The gaming industry grew steadily from the 1990s    * Reached its peak during 2008–2010
 * Then declined significantly in later years

<img width="1238" height="546" alt="Image" src="https://github.com/user-attachments/assets/4caed4b1-2cae-455c-807f-b3272028059e" />
---

#### 4. Regional Sales Analysis

* Compared top 10 games and there performance across regions
* Found that many top games perform well in Western regions but poorly in Japan

<img width="1238" height="546" alt="Image" src="https://github.com/user-attachments/assets/4caed4b1-2cae-455c-807f-b3272028059e" />
---

#### 5. Console vs Genre Analysis

* Analyzed how consoles perform across genres
* Found that most consoles support multiple genres with slight preferences

<img width="580" height="432" alt="Image" src="https://github.com/user-attachments/assets/355fa63a-1575-4b54-80fb-6a044ca3d257" />
---

### 6. Sales vs Critic Score

* Used scatter plot and correlation
* Found:

  * Weak positive relationship
  * High ratings do not always guarantee high sales

<img width="997" height="728" alt="Image" src="https://github.com/user-attachments/assets/e7671568-62e8-480f-9f58-46b44372e43c" />

---

##  Visualizations Used

* Bar Chart → Genre & regional Sales comparison
* Line Plot → Sales trends over time
* Scatter Plot → Sales vs critic score

##  Conclusion

The video game industry experienced strong growth from the 1990s, peaking around 2008–2010, followed by a decline in recent years.
Sales are dominated by North America and Europe, with many top titles performing well in these regions but less successfully in Japan.
While platforms support a wide range of genres and higher critic scores slightly relate to better sales, neither guarantees success, as multiple factors influence performance.
