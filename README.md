# Will a Customer Accept the Coupon?

## Overview
This project analyzes survey data from the UCI Machine Learning Repository to determine what factors influence whether a driver accepts a coupon. The dataset describes driving scenarios such as destination, current time, weather, passenger, and coupon type, and records whether the customer accepted the coupon.

The goal of this project is to use Python, pandas, Matplotlib, and Seaborn to explore differences between customers who accepted a coupon and those who did not.

## Project Goal
This analysis answers the question:

**Will a customer accept the coupon?**

Using exploratory data analysis and visualization, the notebook identifies patterns in coupon acceptance across customer habits, trip context, demographics, and coupon categories.

## Dataset
The dataset was collected through a survey on Amazon Mechanical Turk and is published through the **UCI Machine Learning Repository**.

The response variable is:

- `Y = 1` → customer accepted the coupon
- `Y = 0` → customer did not accept the coupon

The dataset includes several coupon categories, such as:

- Less expensive restaurants (under $20)
- Coffee House
- Carryout & Takeaway
- Bar
- More expensive restaurants ($20–$50)

## Repository Contents
This repository should include the following files and folders:

```text
project-folder/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └──Practical_Application_1.ipynb
├── data/
│   └── coupons.csv
└── images/
    ├── acceptance_by_type.png
    ├── coffeehouse_frequency.png
    └── bar_frequency.png
    
```


## Setup and Start Instructions

```bash
git clone <your-repository-url>
cd <your-repository-folder>
git pull origin main
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Start notebook:

```bash
jupyter notebook
```