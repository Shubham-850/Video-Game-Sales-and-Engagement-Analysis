# 🎮 Video Game Sales & Engagement Analysis

## 📊 Project Overview
This project analyzes video game performance by combining **sales data** and **user engagement metrics**. The goal is to identify trends in game popularity, platform performance, and player behavior.

The analysis helps answer important business questions such as:
- Which game genres generate the highest sales?
- How do user ratings influence sales?
- Which platforms and publishers dominate the market?
- Do highly wishlisted games perform better commercially?

The project uses **Python, SQL, and Power BI** to clean, analyze, and visualize the data.

---

## 📂 Datasets Used

### 1️⃣ games.csv (Game Engagement Data)

Contains player interaction and engagement metrics.

**Key Columns**
- Title
- Release Date
- Team (Developer)
- Rating
- Genres
- Plays
- Backlogs
- Wishlist
- Number of Reviews

---

### 2️⃣ vgsales.csv (Video Game Sales Data)

Contains global video game sales data.

**Key Columns**
- Name
- Platform
- Year
- Genre
- Publisher
- NA_Sales
- EU_Sales
- JP_Sales
- Other_Sales
- Global_Sales

---

## 🛠 Technologies Used

- **Python**
- **Pandas**
- **SQL (SQLite)**
- **Power BI**
- **Data Visualization**

---

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning
- Removed duplicate records
- Handled missing values
- Standardized genre and platform names
- Converted date formats

### 2️⃣ SQL Database Creation
Structured tables were created to store and manage the datasets.

Tables include:
- `games_metadata`
- `sales_data`
- `merged_games`

### 3️⃣ Data Merging
Both datasets were joined using game titles to analyze **sales and engagement together**.

### 4️⃣ Exploratory Data Analysis (EDA)
Key questions explored:

- Top-rated games by users
- Most popular genres
- Best-selling platforms
- Regional sales comparison
- Relationship between ratings and sales
- Wishlist vs commercial performance

### 5️⃣ Data Visualization
Interactive dashboards were created using **Power BI** including:

- Genre popularity charts
- Platform sales comparison
- Regional sales heatmaps
- Rating vs sales scatter plots
- Wishlist vs sales analysis

---

## 📊 Key Insights

Some important insights discovered from the analysis:

- Action and Sports genres generate the highest global sales.
- North America contributes the largest share of video game sales.
- Higher user ratings often correlate with higher sales.
- Some platforms dominate the gaming market in terms of global sales.
- Games with high wishlist counts often perform better commercially.

---

## 📈 Dashboard Features

The Power BI dashboard includes:

- KPI metrics (Total Sales, Average Rating, Total Plays)
- Genre performance analysis
- Platform market share
- Regional sales breakdown
- User engagement vs sales comparison

---

## 🚀 Project Outcomes

By completing this project:

- A structured **SQL database** was created for video game data.
- Interactive **Power BI dashboards** were developed.
- Key insights were extracted to help understand **consumer behavior and game success factors**.

---

## 👨‍💻 Author

**Shubham Rathore**

Data Analytics Project
