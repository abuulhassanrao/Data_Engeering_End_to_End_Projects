# IPL Data Analysis Project

## Overview

This project demonstrates an end-to-end data engineering and analytics pipeline built using Apache Spark on Databricks, processing Indian Premier League (IPL) cricket data stored in Amazon S3. The pipeline includes data ingestion, processing, SQL analytics, and visualization to generate insightful cricket statistics.

---

## Architecture Diagram
<img width="1400" height="788" alt="IPLDataAnalysis" src="https://github.com/user-attachments/assets/d74834d3-8a58-4b2f-975f-bc94093488de" />



The diagram illustrates the workflow:

- IPL raw data is stored in **Amazon S3** as the main data storage.
- Data is processed on the **Databricks** platform leveraging:
  - **Apache Spark** for distributed data transformation and cleaning.
  - **Spark SQL** for complex analytical queries.
  - Visualization libraries for intuitive data representation.

---

## Features

- Data ingestion of various IPL datasets: ball-by-ball, player details, match info, and teams.
- Spark DataFrame and SQL transformations to clean, aggregate, and analyze data.
- Use of window functions and advanced Spark SQL for insightful cricket analytics including player performance, bowling economy, and match outcomes.
- Visualizations to explore trends like top batsmen per season, economical bowlers in powerplays, and impact of toss on match results.
- Built with scalability to handle large datasets on cloud infrastructure.

---

## Technologies Used

- Apache Spark (PySpark) 3.3.2
- Databricks cloud platform
- Amazon S3 for data storage
- Python libraries: Matplotlib, Seaborn for visualizations

---

## Getting Started

### Prerequisites

- Access to Databricks workspace
- Amazon S3 bucket with IPL datasets following the project's folder structure.
- Python environment with required libraries if running locally.

### Setup and Run

1. Clone repository:

git clone <your-repo-url>
cd ipl-data-analysis


2. Upload IPL datasets (CSV files) to your S3 bucket as per project structure.

3. Configure Databricks cluster with Spark 3.3.2.

4. Open and run the project notebook on Databricks, modify the S3 path locations if needed.

5. Explore results and modify queries for custom insights.

---

## Sample Analysis Highlights

- Top scoring batsmen by season
- Economical bowlers during powerplay overs
- Toss impact on match result outcome
- Average runs scored by batsmen in winning matches
- Score distribution by venue and dismissal types
- Team performance after winning toss

---

## Contributing

Contributions are welcome to extend analytics, add new visualizations, or improve pipeline efficiency.


---

## Contact

For any queries or help, please open an issue or contact abuulhassanrao21@gmail.com

---

*By using this pipeline, you gain valuable hands-on experience with distributed data processing, cloud storage, and sports analytics suited for data engineering roles.*

