# Twitter ETL with Apache Airflow 🚀  

## 📌 Overview  
This project implements an **ETL (Extract, Transform, Load) pipeline** for extracting Twitter data using **Tweepy**, processing it with **Pandas**, and automating the workflow with **Apache Airflow**. The ETL process fetches tweets from a specified user, cleans and structures the data, and saves it in a CSV format for further analysis.  

## 🚀 Technologies Used  
- **Tweepy** – Extracts tweets using the Twitter API  
- **Pandas** – Transforms and processes tweet data  
- **Apache Airflow** – Schedules and automates the ETL pipeline  
- **Python** – Core scripting language for the project  

## 📂 Project Structure  
```
📦 Twitter_ETL_Airflow
 ├── 📄 twitter_etl.py       # Extracts tweets and saves them as CSV
 ├── 📄 twitter_dag.py       # Defines and schedules the ETL process in Airflow
 ├── 📄 README.md            # Project documentation

```

## 🔹 Features  
✔️ Extracts real-time tweets from a specific Twitter account  
✔️ Cleans and structures tweet data (user details, retweets, likes, timestamps)  
✔️ Saves processed data into a CSV file for further use  
✔️ Automates the ETL process using **Apache Airflow** to run on a schedule  

This project is ideal for anyone looking to **automate data extraction from Twitter** and store it in a structured format for further analysis or insights. 🚀
