# Uber Data Analytics | Data Engineering GCP Project

This project was crated by [darshilparmar](https://github.com/darshilparmar). I'm replicating for learning purposes.

# Introduction
The goal of this project is to perform data analytics on Uber data using GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery and Looker Studio.

## Architecture
 - The data will be stored at Google Cloud Storage
 - Mage will support the standard batch pipeline in a Google's Compute Instance
 - Biquery will be used as the data warehouse
 - A dashboard will be develop using Looker

![Architechture](https://github.com/alexandrecardososantos/uber_etl_pipeline_data_engineering_project/blob/main/architecture.jpg)

## Dataset Used

TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

The data can be downloaded in here: [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

The data dictionary can be downloaded here: [https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)
