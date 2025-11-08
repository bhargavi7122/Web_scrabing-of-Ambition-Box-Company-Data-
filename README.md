<h1 align="center">💼 AmbitionBox Web Scraping & Company Insights | Python</h1>
<h3 align="center">Web Scraping | Data Cleaning | Exploratory Data Analysis | Visualization</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Python-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Libraries-BeautifulSoup%20%7C%20Pandas%20%7C%20Seaborn-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Company%20Analysis%20%7C%20EDA-green?style=for-the-badge"/>
</p>

---

### 🧾 *About the Project*
The **AmbitionBox Web Scraping & EDA Project** extracts company-level data such as **ratings, reviews, salaries, and job insights** directly from AmbitionBox.com.  
It converts unstructured HTML data into a clean, structured dataset for in-depth **data visualization and trend analysis**.  
The goal is to uncover how companies perform across industries and locations based on employee perceptions.

---

### 🚀 *Key Objectives*
- 🏢 Extract **company information** (ratings, reviews, jobs, salaries) using **BeautifulSoup**.  
- 🧹 Clean and preprocess unstructured web data into a structured **Pandas DataFrame**.  
- 📊 Perform **univariate, bivariate, and multivariate** analysis to explore company trends.  
- 📈 Visualize key insights on **industry performance, job openings, and satisfaction levels**.  
- 💡 Provide insights useful for **job seekers, HR professionals, and analysts**.

---

### ⚙️ *Project Workflow*
1. **Data Collection (Web Scraping)**  
   - Scraped company data from **AmbitionBox.com** using the *Requests* and *BeautifulSoup* libraries.  
   - Extracted fields: Company Name, Ratings, Reviews, Salaries, Jobs, Benefits, Photos, and Industry Type.  

2. **Data Cleaning & Transformation**  
   - Removed unwanted HTML tags and symbols using regex.  
   - Converted text data like `['1.1L']` → `110000` for numeric analysis.  
   - Filled missing values and standardized columns for consistency.  

3. **Exploratory Data Analysis (EDA)**  
   - **Univariate:** Histograms, boxplots, and KDE plots for numerical data.  
   - **Bivariate:** Scatterplots, regression plots, and countplots for relationships.  
   - **Multivariate:** Correlation heatmap and bubble charts for deeper insights.  

4. **Visualization & Insights**  
   - Created professional Seaborn and Matplotlib visuals.  
   - Highlighted top industries, job openings, and rating trends.  

---

### 🧠 *Key Insights*
- 💼 **IT Services & Consulting** companies dominate with the most listings and reviews.  
- 🏙️ **Bangalore, Pune, and Hyderabad** are the top employment hubs.  
- ⭐ Most companies maintain ratings between **3.5 and 4.5**, showing strong employee satisfaction.  
- 💸 Salaries and job openings show a **positive correlation**, indicating growth potential in well-rated firms.  
- 🧩 Highly rated aspects include *Work Culture*, *Learning Opportunities*, and *Career Growth*.  

---

### 💡 *Recommendations*
- 🧾 Use employee reviews and ratings to improve **employer branding strategies**.  
- 💬 Companies with low ratings should focus on **work-life balance and growth factors**.  
- 📈 Industries can leverage review trends to attract top talent.  
- 🔍 Job seekers can identify **top-performing industries and cities** based on real feedback data.

---

### 🧰 *Tech Stack*
| Tool / Library | Purpose |
|----------------|----------|
| 🐍 Python | Core language used for scraping and analysis |
| 🌐 BeautifulSoup | Extracting data from AmbitionBox HTML pages |
| 📦 Requests | Sending HTTP requests to fetch page data |
| 📊 Pandas | Cleaning, organizing, and analyzing structured data |
| 🎨 Seaborn / Matplotlib | Data visualization and storytelling |

---

### 📂 *Repository Structure*
📁 *AmbitionBox-WebScraping-EDA*  
│  
├── 🕸️ *ambitionbox_scraping.py* → Web scraping script  
├── 🧹 *data_cleaning.py* → Data cleaning and transformation code  
├── 📊 *eda_visualizations.py* → Visualization and insights generation  
├── 📄 *AmbitionBox_Companies.csv* → Raw extracted data  
├── 📄 *AmbitionBox_Cleaned.csv* → Cleaned dataset  
├── 🖼️ *images/* → Folder containing EDA charts and plots  
└── 📘 *README.md* → Project documentation  

---

### 📈 *Sample Visuals*
<p align="center">
  <img src="images/univariate_plots.png" width="45%" style="border-radius:10px; margin-right:10px;">
  <img src="images/bivariate_plots.png" width="45%" style="border-radius:10px;">
</p>

---

### 🏁 *Conclusion*
This project demonstrates how **web scraping and EDA** can turn unstructured online data into **valuable insights**.  
By analyzing AmbitionBox company information, it provides a clear picture of **industry trends, job opportunities, and employee satisfaction**, supporting both organizational strategy and career planning.

---

<h3 align="center">✨ Turning Employee Feedback into Meaningful Insights ✨</h3>

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/data-analysis.png" width="80"/>
</p>
