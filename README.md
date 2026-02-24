# Video Game Sales Analysis

An exploratory data analysis of global video game sales from 1980-2020 using Python, Pandas, and Seaborn.

## Questions Answered
1. What is the highest selling game globally?
2. Which platform sold the most games overall?
3. What year had the highest global sales?
4. What was the highest selling game by region?
5. What are the top selling games by platform?
6. Which genre was most popular by region?
7. How did global game sales trend over time?

## Dataset
Data sourced from [Kaggle — Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales).  
Contains 16,598 records of video game titles with sales data across North America, Europe, Japan, and other regions from 1980-2020.

## Setup

1. Clone the repository
```bash
   git clone https://github.com/PythonPhyfe/Video-Game-Sales-Analysis.git
```
2. Create and activate a virtual environment
```bash
   python -m venv venv
   source venv/Scripts/activate  # Windows
   source venv/bin/activate       # Mac/Linux
```
3. Install dependencies
```bash
   pip install -r requirements.txt
```
4. Open `notebooks/video_game_sales_analysis.ipynb` in VSCode or Jupyter and run all cells

## Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter

## Key Findings
- The traditional video game market peaked in 2008-2009 before declining with the rise of mobile gaming
- The PS2 holds the record for highest total software sales of any platform in history
- Japan represents a distinctly different market, favoring Role-Playing games while every other region favors Action
- Hardware bundles significantly inflate individual title sales. Both Wii Sports and Kinect Adventures were bundled with their respective hardware

## Notes
Sales figures are in millions of copies. Data after 2016 appears incomplete and should be interpreted with caution.