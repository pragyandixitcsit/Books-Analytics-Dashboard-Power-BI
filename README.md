# 📚 Books Analytics Dashboard | Power BI

## Project Title

**Books Analytics Dashboard using Power BI**

## Project Description

The Books Analytics Dashboard is an interactive Business Intelligence project developed using Microsoft Power BI to analyze book prices, ratings, stock levels, and inventory value.

The dashboard transforms raw book data into meaningful insights using KPI cards, interactive charts, slicers, detailed tables, and a decomposition tree.

## Project Objective

The main objective of this project is to develop an interactive dashboard that provides insights into:

- Total number of books
- Average book rating
- Average book price
- Total inventory value
- Price category distribution
- Rating distribution
- Stock and inventory levels
- Book-wise performance
- Relationship between price, rating, and inventory

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning & Transformation
- Data Visualization
- Business Intelligence

## Dashboard Features

### 1. Executive Overview

The dashboard provides key performance indicators including:

- Total Titles
- Average Rating
- Average Price
- Total Inventory Value

### 2. Price Category Analysis

Analyzes the distribution of books across different price categories using interactive visualizations.

### 3. Rating Analysis

Visualizes book ratings to understand the overall rating distribution within the dataset.

### 4. Price & Inventory Analysis

Analyzes the relationship between:

- Book Price
- Rating
- Stock Units
- Inventory Value

### 5. Decomposition Tree

The decomposition tree provides detailed analysis of Inventory Value based on different dimensions such as price category, rating, and inventory cluster.

### 6. Book Details

A detailed table provides:

- Book Title
- Price
- Rating
- Stock Units
- Inventory Value

Interactive slicers allow users to filter the dashboard and explore the data.

## Key KPIs

| KPI | Description |
|---|---|
| Total Titles | Total number of books in the dataset |
| Average Rating | Average rating of books |
| Average Price | Average price of books |
| Total Inventory Value | Total value of available inventory |

## Data Preparation

The dataset was prepared using Power BI and Power Query.

The data preparation process included:

1. Importing the book dataset
2. Cleaning and transforming the data
3. Checking and correcting data types
4. Creating calculated fields
5. Categorizing books based on price
6. Preparing inventory-related fields
7. Creating DAX measures
8. Building interactive visualizations

## DAX Measures

Example measures used in the dashboard:

```DAX
Total Titles = DISTINCTCOUNT(clean_books_data[title])
