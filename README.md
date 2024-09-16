# Nguyen Thuy Hien's portfolio

## [1. Classification – Customer Segmentation - CDNOW](https://github.com/HienThNg/CDNOW)
The file CDNOW_master.txt contains the entire purchase history up to the end of June 1998 of the cohort of 23,570 individuals who made their first-ever purchase at CDNOW in the first quarter of 1997. This CDNOW dataset was first used by Fader and Hardie (2001).

Each record in this file, 69,659 in total, comprises four fields: the customer's ID, the date of the transaction, the number of CDs purchased, and the dollar value of the transaction.
See "Notes on the CDNOW Master Data Set" (http://brucehardie.com/notes/026/) for details of how the 1/10th systematic sample (http://brucehardie.com/datasets/CDNOW_sample.zip) used in many papers was created.

Reference: Fader, Peter S. and Bruce G.,S. Hardie, (2001), "Forecasting Repeat Sales at CDNOW: A Case Study," Interfaces, 31 (May-June), Part 2 of 2, S94-S107.

#### This project used **RFM analysis, RFM + Kmeans (ML),  RFM + Hierarchical Clustering (ML) and RFM + Kmeans (Big Data)** to classify CDNOW customers.

### [Streamlit GUI for this project](https://datascienceproject-mvbfmah86b8dgzdu67yxps.streamlit.app/)

## [2. Preprocessing and Visualization Tool with Streamlit](https://prep-viz-tool.streamlit.app/)
The tool is designed to address the challenges of data cleansing and analysis quickly, timely, and accurately. Additionally, it integrates several applications to enhance data visualization, serving reporting or meeting purposes.

The tool is built on a user-friendly platform for users without programming experience in Python. The goal of the tool is to help users conveniently and efficiently handle data errors and deficiencies and perform quick analysis steps. The tool currently integrates the following applications:

A. Data cleansing:
1. Identify and clean outliers.
2. Clean text containing special characters.
3. Filter "Other" responses outside of the available options for multiple-choice questions.
4. Delete any specific phrases within a paragraph while preserving the rest if they stand alone.
5. Filter and calculate ranking questions in surveys.
6. Filter and count unique values.
7. Count the frequency of any word/phrase/sentence.

B. Data visualization:
1. Generate QR codes and insert logos/images.
2. Create word clouds based on frequency.

## 3. Recommender System – E-commerce
Create a Recommender System for an E-commerce website.
Model include: Content based filtering (Cosine, Gensim) and Collaborative filtering (ALS).


