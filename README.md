# Bank-transaction-EDA-fraud-detection-analysis
This project showcases my expertise in ETL processes, data visualization, exploratory data analysis (EDA), and tools like Power BI and SQL, applied to real-world scenarios like fraud detection.  
## Steps Performed

### Dataset Description and Study
Loaded the dataset and explored its structure using df.head(), df.info(), and df.describe().
Identified missing values, data types, and distributions of key features.
Studied the dataset characteristics to understand transaction behaviors and potential fraud indicators.

### Transaction Data Analysis
Analyzed transaction volumes across various locations using bar plots.
Examined transaction types (debit/credit) using pie charts to understand their distribution by type and location.

### Pattern Analysis by Time and Demographics
Investigated transaction trends based on the day of the week.
Analyzed customer demographics (age, occupation) using count plots and histograms to identify key temporal and demographic patterns.

### Channel Usage Insights
Examined the distribution of transactions across different channels (branch, ATM, online) using pie charts.
Identified preferred transaction channels and highlighted areas for potential fraud detection.

### Correlation Analysis for Fraud Indicators
Explored relationships among numerical features using heatmaps.
Identified potential correlations between transaction amounts, locations, and other variables that may indicate fraudulent activity or irregular patterns.

### Tools and Technologies Used
Utilized Python with libraries like Pandas, Matplotlib, and Seaborn.
Performed data cleaning, transformation, and visualization using bar plots, pie charts, heatmaps, and histograms.

## Dashboard

<img src="Bank%20Transction%20Dashboard.png" alt="Bank Transaction Dashboard" />

## Results and Conclusions:
<b>Average Transaction Amount:</b> The average transaction amount is approximately <b>$297</b>, with the highest transaction recorded at <b>$1919</b>.

<b>Customer Age:</b> The age of customers ranges between <b>18 and 80</b>, highlighting a <b>diverse customer base</b>.

<b>Transaction Channels:</b> The majority of transactions are made through <b>branches</b>, followed by <b>ATMs</b> and <b>online platforms</b>.

<b>Geographic Concentration:</b> Transactions are primarily concentrated in key locations such as <b>Fort Worth</b>, <b>Los Angeles</b>, and <b>Oklahoma City</b>.

<b>Weekday Trends:</b> Higher transaction volumes are observed on specific weekdays, indicating potential <b>day-of-week trends</b>.

<b>Customer Segments:</b> <b>Students</b> and <b>doctors</b> account for a significant proportion of the transaction volume.

<b>Shared IPs:</b> A total of <b>552 instances</b> were found where <b>IPs were shared across multiple accounts</b>, suggesting potential <b>fraud risks</b>. Closer inspection of high-risk accounts may be required.

<b>Geographical Activity:</b> <b>349 accounts</b> have conducted transactions from <b>more than 3 unique locations</b>, which may indicate unusual behavior.

<b>Heatmaps:</b> The heatmaps reveal relationships between <b>Transaction Amount</b>, <b>Account Balance</b>, and other numeric fields, offering valuable insights to <b>refine fraud detection models</b>.



