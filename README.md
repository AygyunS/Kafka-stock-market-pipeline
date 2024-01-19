# Kafka Stock Market Pipeline

## Introduction

This repository contains an end-to-end data engineering project focused on real-time stock market data using Apache Kafka. The project is divided into two main parts:

### Part 1: CSV File Processing
In the initial phase, the project processes CSV files for stock market data.

### Part 2: Integration with Forex API
The second part involves enhancing the project by incorporating API calls to fetch CSV files from a Forex API.

## Technology Stack

The project is implemented using the following technologies:

- **Programming Language:** Python
- **Amazon Web Services (AWS):**
  - S3 (Simple Storage Service)
  - Athena
  - Glue Crawler
  - Glue Catalog
  - EC2
- **Apache Kafka**

## Architecture

The project utilizes Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL in its architecture. The high-level architecture is illustrated below:

![Architecture Diagram](https://github.com/AygyunS/Kafka-stock-market-pipeline/assets/32463645/b856658a-0087-48a8-b3ec-bc5482265558)

## Getting Started

To run the project locally or deploy it, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/AygyunS/Kafka-stock-market-pipeline.git
