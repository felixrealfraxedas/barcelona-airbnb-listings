# Barcelona Airbnb listings

This project focuses on analyzing Airbnb listings data to gain valuable insights and create an interactive interface for users to explore the findings. The data that is used in this project is provided by the official Airbnb site http://insideairbnb.com/get-the-data/.

The core of the project is done in R and it consists in the following parts:

- Data cleaning and preparation
- Descriptive analysis
- Unsupervised clustering
- Supervised clustering
- Interface creation

## Data cleaning and preparation

In this step, the raw Airbnb listings data will be collected and processed to handle missing values, remove duplicates, and transform the data into a suitable format for analysis. The cleaned dataset will be used for subsequent steps. The data from **listings.csv** is taken, processed with **Data_reading.Rmd** and the output is the more readable **bcn_data_cleansed.csv**.

## Core of the project

The core of the project can be found at **Final_report.Rmd** and its output **Final_report.html**

### Descriptive analysis

Descriptive analysis involves exploring the cleaned Airbnb listings dataset to extract valuable insights and statistics. This analysis will include summary statistics, data visualizations, and other exploratory techniques to understand the distribution and characteristics of the listings.

### Unsupervised clustering

Unsupervised clustering is a technique used to group similar Airbnb listings together based on their features. We will use algorithms like k-means or hierarchical clustering to discover patterns and relationships among the listings without any predefined labels.

### Supervised clustering

Supervised clustering, also known as classification, involves using labeled data to train a model that can categorize new Airbnb listings into predefined classes. In this case, the classes will be price categories (Low, Medium and High, which are pre-defined). We will use machine learning algorithms like decision trees, support vector machines, or random forests to build a predictive model for categorizing listings.

## Interface creation and results

Shiny is an R package that allows the creation of interactive web applications. In this project, we will build a user-friendly interface using Shiny to present the results of our Airbnb listings analysis. Users will be able to interact with the interface by predicting the price of a listing with chosen characteristics using a simplified version of one of the algorithms that are previously used. The creation of the interface can be found at **Interface.Rmd**.

Also, a summary of the results can be found in the presentation **Plantilla Airbnb.pptx**.

## Requirements

- *R* version 4.2.2.
- An IDE to work with *.Rmd*, we used **RStudio**.

## Installation

1. Clone this repository

```

```

