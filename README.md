# Automobile Fuel Consumption Prediction

## Domain
**Automobile**

## Context
This project focuses on predicting city-cycle fuel consumption in miles per gallon (mpg). The prediction is based on 3 multi-valued discrete attributes and 5 continuous attributes. 

## Data Description
The dataset contains information regarding city-cycle fuel consumption in miles per gallon. The attributes in the dataset are as follows:

### Attribute Information
- **mpg**: Continuous - Fuel consumption in miles per gallon
- **cylinders (cyl)**: Multi-valued discrete - Number of cylinders in the car
- **displacement (disp)**: Continuous - Engine displacement
- **horsepower (hp)**: Continuous - Engine horsepower
- **weight (wt)**: Continuous - Weight of the car
- **acceleration (acc)**: Continuous - Time to accelerate from 0 to a certain speed
- **model year (yr)**: Multi-valued discrete - Year of the car model
- **origin**: Multi-valued discrete - Origin of the car
- **car name**: String - Unique identifier for each car

## Project Objective
The main goal of this project is to:
1. Cluster the data.
2. Treat each cluster as an individual dataset.
3. Train regression models on each cluster to predict the `mpg`.

## Setup and Installation
To run the code in this repository, you need to have Python installed.

### Steps to Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/devanshisaraf/Corizo-Major-Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Corizo-Major-Project
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Data Preprocessing**: Run the data preprocessing scripts to clean and prepare the data.
2. **Clustering**: Perform clustering on the dataset.
3. **Regression Modeling**: Train regression models on each cluster to predict `mpg`.

## Contributions
Feel free to fork this repository and make contributions. Pull requests are welcome.
