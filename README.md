<div>
<img src="https://octodex.github.com/images/mountietocat.png" width="10%" height="10%" />
<img src="https://octodex.github.com/images/labtocat.png" width="10%" height="10%" />
<!-- <img src="https://octodex.github.com/images/pythocat.png" width="10%" height="10%" /> -->
</div>

# digital-talent

:octocat: Repository for **Digital Talent Scholarship 2018** | Big Data | UGM

**Big Data Analytics** specialization class facilitated by Universitas Gadjah Mada (UGM) 
and event held by Ministry of Communication and Information Technology of the Republic of Indonesia 

## - Tugas BMI
Python Notebook program to calculate **Body mass index (BMI)** is a measure of body fat based on height and weight that applies to adult men and women. Categorize Body Mass Index(BMI) according to the BMI table

## - Tugas List Nilai
Python Notebook program to measure the common **statistical functions**. A statistical function, such as Mean, Median, Variance, standard deviation summarizes a sample of values by a single value. By default, they expect their parameter(s) to be a probabilistic value represented by a random sample of values over the Run index. 

## - Tugas Word Count
**Word Count** is a technique in which a sorted list of words and their frequency from data sources. In this Python Notebook program, Word Count is generated from a sample paragraph that we got from a news description, separate each word, and calculate each word based on their frequency.

## - Analisis Data Siswa SMA
Analysis data from [data.go.id](https://data.go.id/) which determine the percentage of the Senior High School student (SMA). The initial dataset contains the percentage of high school students according to the residence, in each province in Indonesia. Data sourced from Data and Statistics Center of Education and Culture of Indonesia

---

<img src="https://octodex.github.com/images/spidertocat.png" width="10%" height="10%" /> 

# Scrapping
**Web scraping** is a program or algorithm to extract and process large amounts of data from the web. All of the tasks related on the scrapping function are placed in `scrapping` folder.

## - Scrapping Kompas
Scrapping articles from the [kompas.com](https://www.kompas.com/) website. Getting articles data from [kompas.com](https://www.kompas.com/) which related to technology and put the result on `scrapping/scrap-images` data `scrapping/scrap-data` folders.

- All of the images are placed in `scrapping/scrap-images` folder
- All of the data of the article are saved on `scrapping/scrap-data/data_berita.csv` file

## - Scrapping Twitter
Scrapping tweets from [twitter](https://twitter.com/) website. Getting tweets from the [twitter](https://twitter.com/) which related to specific term. All of the tweets are saved in the `scrapping/scrap-data` folder.

- All of the twees are saved on `scrapping/scrap-data/data_twitter.xlsx` file

## - Scrapping Tirto
Scrapping articles from [Tirto.id](https://tirto.id/) website. Trying to get articles from this website and put all of the articles to the `scrapping/scrap-data` folder
- First, Get list articles from **1<sup>st</sup>** index of the website and save on `scrapping/scrap-data/tirto.xlsx` file
- Second, Get list articles from **1<sup>st</sup>** to **14<sup>th</sup>** index of the website and save on `scrapping/scrap-data/tirtoArticles.xlsx` file

---

<img src="https://octodex.github.com/images/Sentrytocat_octodex.jpg" width="10%" height="10%" />

# Data Cleaning
**Data cleaning** is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data. All of the tasks related on the scrapping function are placed in `cleaningData` folder.

- Missing Value
- Encoding Data Category
- Binarizing
- Scaling feature
- Feature Extraction(Count Vectorizer, Vectorizer Dict, TfIdf Vectorizer)


---

<img src="https://octodex.github.com/images/socialite.jpg" width="10%" height="10%" />

# SQL
**SQL (Structured Query Language)** is a standard language for storing, manipulating and retrieving data in databases, SQL lets you access and manipulate database. All of the tasks related on the SQL are placed in `SQL` folder.

Before start this folder notebook, please make sure to complete this following list:
- Install [XAMPP](https://www.apachefriends.org/index.html)
- Start MySQL Database, and Apache Webserver
- Install Package [PyMySQL](https://github.com/PyMySQL/PyMySQL) in this notebook, this package contains a pure-Python MySQL client library
- Import database `SQL/mysqlsampledatabase.sql` to MySQL Database

### SQL List Notebook
- SQL Query 
- SQL Join
- SQL SubQuery

---

<img src="https://octodex.github.com/images/Professortocat_v2.png" width="10%" height="10%" />

# Statistics
**Statistics** is the science of collecting, analyzing and understanding data, and accounting for the relevant uncertainties. As such, it permeates the physical, natural and social sciences; public health; medicine; business; and policy. Statistics is fundamental to ensuring meaningful, accurate information is extracted from Big Data. All of the tasks related on the Statistics are placed in `statistics` folder.

## - Descriptive Statistics
A descriptive statistic is a summary statistic that quantitatively describes or summarizes features of a collection of information, while descriptive statistics in the mass noun sense is the process of using and analyzing those statistics.


---

<img src="https://octodex.github.com/images/setuptocat.jpg" width="10%" height="10%" />

# Installation 

This repository requires [Python 3.7](https://www.python.org/downloads/) or v3+ to run.

Install the [Jupyter Notebook](http://jupyter.org/) to run `.ipynb` file.

```sh
$ git clone https://github.com/t4f1d/digital-talent.git

```
