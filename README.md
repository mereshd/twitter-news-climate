<h1 align="center" id="title">Twitter Climate Change News</h1>

## Description
This project delves into the vast world of Twitter to determine its reliability and credibility as a source of information on the topic of climate change. Using Apache Spark, approximately 500 GB of tweets were processed and analyzed. The core assumption in gauging the validity of the platform's content was a correlation between Twitter following and engagement with the credibility of information. The entire project was executed within the Google Cloud Platform (GCP) environment.

## Project Breakdown
1) Needed to filter the data and retrieve a sizeable sample for efficient processing. The code for this step is in the following file: `twitter-news-climate/Data_Filter_Partition.ipynb`
2) The preliminary analysis on a smaller test sample was done in the `twitter-news-climate/Data_Analysis_Test.ipynb` file.
3) The final analysis conducted on the original filtered data is done in the `twitter-news-climate/Data_Application.ipynb` notebook.
4) A more detailed description of each step and the analysis insights are captured in the presentation file in this repository (`twitter-news-climate/BDP_Presentation.pdf`). 

## Tech Stack
- Apache Spark(PySpark): data processing and analysis
- Python: matplotlib, seaborn, numpy, pandas, re, os
- Google Cloud Platform (GCP): cloud-based infrastructure
