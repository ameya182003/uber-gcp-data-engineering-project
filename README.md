# Scalable Uber Data Analytics ETL Pipeline on Google Cloud Platform

## Introduction

This project builds a scalable end-to-end ETL pipeline on Google Cloud Platform to process and analyze Uber trip data. It performs data ingestion, transformation, and loading into BigQuery, enabling efficient querying and visualization through Looker Studio.

## Architecture 
<img src="Architecture.jpg">

## Data Model
<img src="Data Model.png">

## ETL Pipeline
- **Extract**: Ingested raw CSV data into Google Cloud Storage  
- **Transform**: Cleaned and structured data using Python and Mage  
- **Load**: Loaded transformed data into BigQuery  

## Tech Stack
- Python  
- Google Cloud Platform (GCS, Compute Engine, BigQuery)  
- Mage  
- Looker Studio  

## Dataset Used
TLC Trip Record Data  

Yellow and green taxi trip records include fields capturing:
- Pick-up and drop-off dates/times  
- Pick-up and drop-off locations  
- Trip distances  
- Itemized fares  
- Rate types  
- Payment types  
- Passenger counts  

**Website**:  
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page  

**Data Dictionary**:  
https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Key Learnings
- Built and understood end-to-end ETL pipeline architecture  
- Gained hands-on experience with GCP services (GCS, Compute Engine, BigQuery)  
- Learned workflow orchestration using Mage  
- Improved data cleaning, transformation, and data modeling skills  
