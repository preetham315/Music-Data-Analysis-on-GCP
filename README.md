# Top Spotify Songs Analysis
## Introduction

This repository contains all the resources and findings of an exploratory data analysis project on the "Top Spotify Songs" dataset, which encapsulates trending songs across over 73 countries. The project aimed to uncover patterns and gain insights into global music preferences using advanced data analytics tools and techniques.

## Dataset

The dataset includes 127,306 entries, representing individual songs, complete with various musical attributes like danceability, energy, popularity, etc. The data was sourced from Kaggle and is updated daily to reflect the latest trends.

## Methodology

The project follows a systematic approach starting from data procurement to analysis and visualization:

* Plan: Formulating the objective to delve into the world of global music trends.
* Obtain: Acquiring the dataset from Kaggle that reflects global music trends.
* Assure: Setting up the infrastructure on GCP by creating a storage bucket named bucket_spotify.
* Transform: Accessing and preprocessing the data using Google Colab, cleaning and structuring for effective analysis.
* Store: Storing the preprocessed data on GCP for accessibility and further processing.
* Publish: Sharing the cleaned data and scripts in this repository for community use and further exploration.

### Preprocessing Steps
The preprocessing includes:

* Handling missing values, particularly in the 'country' column.
* Normalizing the 'mode' attribute using z-score calculations.
* Conducting correlation analysis to explore relationships between different attributes.
* Performing a detailed analysis of the 'popularity' metric using the Interquartile Range (IQR).
* Generating box plots and histograms for all numerical attributes.
* The transformation process was meticulously documented to ensure that the data was refined and ready for deeper analysis.

## BigQuery Integration and Visualization
The cleaned dataset was uploaded to BigQuery, where various SQL queries were executed to generate insights. Corresponding visualizations were created using Looker Studio and are presented in this repository.

## Contribution
This project is a testament to the power of combining academic knowledge with practical application. It showcases the use of various cloud computing and big data analytics technologies and the importance of data governance in the field of data science.

Feel free to explore the dataset, replicate the analysis, or build upon it for your research or projects.

## Installation and Usage
Please refer to the individual scripts and notebooks for specific instructions on setting up your environment and running the code.

## Contributions
Suggestions and improvements are welcome. Please fork the repository and submit a pull request for any enhancements.

## Contact
For any queries, please reach out to savinn@iu.edu.

## Acknowledgments
Gratitude to Kaggle for providing the dataset and to all the contributors who have made this project possible.
