
OBJECTIVE
To develop an efficient Big Data Analytics solution using Hadoop for processing, storing, and analyzing large student admission datasets. The goal is to extract meaningful insights, streamline the data processing
workflow, and leverage machine learning algorithms for predictive analysis

PROBLEM STATEMENT
Handling and analyzing large-scale student admission data from multiple sources presents challenges due to its volume, complexity, and variety (e.g.,PDF formats). Traditional data processing techniques struggle with performance issues, leading to slow processing times, difficulty in real-time analysis, and inefficiency in managing and storing large datasets.

Workflow Explanation:

Data Extraction:
We begin by extracting the CAP allotment data from PDFs, as the admission data is typically provided in this format. The extraction process is critical because it serves as the foundation for the entire analysis workflow.

Data Ingestion with HDFS:
After extraction, the data is ingested into HDFS (Hadoop Distributed File System). HDFS offers distributed storage that can efficiently handle the large volume and complexity of student admission datasets.
By integrating R-Hadoop, we enable the R programming environment to access and process the data within HDFS, facilitating text extraction and further manipulation of the PDF content.

Data Preprocessing:
The next step is data preprocessing. This involves cleaning the extracted data—removing inconsistencies, handling missing values, and converting it into a structured format.
R packages are employed here to format the data and prepare it for further analysis.

Distributed Processing:
Given the size and complexity of the data, we utilize MapReduce for distributed processing. This ensures that the data processing is performed in parallel across multiple nodes, significantly improving the speed and efficiency of handling large datasets.

Exploratory Data Analysis (EDA):
Once the data is preprocessed, we perform Exploratory Data Analysis (EDA) using R tools like ggplot2 and dplyr. EDA allows us to uncover trends, relationships, and patterns within the admission data through visualizations, such as bar graphs and line charts.This step is essential to understanding the dataset and gaining initial insights before applying machine learning models.

Data Analysis and Model Training:
After EDA, we move on to training and validating machine learning models using the cleaned data. These models help us perform predictive analysis, which can be used for identifying trends or forecasting future admission patterns.We leverage Big Data Analytics (BDA) algorithms to analyze the dataset more comprehensively and produce actionable insights.
