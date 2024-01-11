# NoSQL Challenge - UK Food Hygiene Ratings Analysis

## Overview
This project involves working with a dataset from the UK Food Standards Agency. The goal is to analyze food hygiene ratings of various establishments across the United Kingdom, aiding the editors of the Eat Safe, Love magazine in their article research.

## Repository Contents
- `NoSQL_setup.ipynb`: Jupyter Notebook for setting up the MongoDB database and initial data import.
- `NoSQL_analysis.ipynb`: Jupyter Notebook for conducting exploratory data analysis.
- `Resources`: Folder containing the `establishments.json` data file.
- `README.md`: This file, provides an overview of the project and instructions.

## Setting Up the Database
1. Clone the repository to your local machine.
2. Import the `establishments.json` data into a MongoDB database named `uk_food` with a collection called `establishments`.

   ```bash
   mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json

## Exploratory Analysis
Use `NoSQL_analysis_starter.ipynb` to explore the dataset. Key questions addressed include:

- Identifying establishments with high hygiene scores.
- Analyzing ratings of establishments in London.
- Locating top-rated establishments near "Penang Flavours".
- Evaluating hygiene scores across different local authorities.

## Requirements
- MongoDB
- Python
- Libraries: PyMongo, Pandas, Pretty Print

## Usage
To use this project, follow these steps:

1. Ensure MongoDB is installed and running on your machine.
2. Open the Jupyter Notebooks and execute the cells in sequence.
