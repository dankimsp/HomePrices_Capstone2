# HomePrices_Capstone2

In this scenario, I am working as an analyst at an investment bank.

The team that I am working with wants to understand how it should allocate dollars earmarked for investment into mortgage-backed securities. They've asked me to look into the factors that drive home prices.

The **[raw data is available here](https://tf-assets-prod.s3.amazonaws.com/tf-curric/data-analytics-bootcamp/housing-price-data-04042019.csv)**. This data originally comes **[from Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)**. This project uses Kaggle's `train.csv` file; for a further description of the variables, see `data_description.txt`.

This capstone includeds three deliverables:

1. An Excel workbook containing my data and your analysis
2. A PowerPoint deck where I share my findings
3. A live presentation of my research, delivered to an audience of Thinkful educators and students


# Presentation Prep (Notes)

In this scenario, you're working as an analyst at an investment bank.

The team that you're working with wants to understand how it should allocate dollars earmarked for investment into mortgage-backed securities. They've asked you to look into the **factors that drive home prices.**

# Introduction

Many things influence sale price of house

- Cost of materials, labor costs
- Location of the house (Iowa)
- More Features/Amenities

With these assumptions in mind, I explored the data to prove my hypothesis but found pretty unexpected and surprising results. 

# Hypothesis

H1: Regular shaped lots costs more*

H2: Houses on flat ground cost more*

H3: Better overall quality of material of house will make house costs more

H4: Houses with fireplaces have increased sale price*

H5: Houses without fences costs more*

H6: More basement area increase sale price of house

H7: More garage space increases sale price of house

# Data

From Kaggle: [https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview)

Used the train.csv and data_description.txt files from the website.

csv contains 163 columns and 1460 observations

Based on sample of houses in state of Iowa 

# Methods

1. Conducted independent t-tests of all of the features to see how the sale price of the house is affected. Split the data into control and treatment groups and used Analysis toolpak to see whether there was a significant difference in price between the two groups.
2. Created scatter plots of numerical data. For example, using garage space in square feet for the x axis and the sale price of the house for the y axis
3. In a pivot table, I graphed the average sale price of houses in each neighborhood. I then grouped the neighborhoods using the elbow method. 

# Results

From A/B hypothesis testing, I found these to be the largest factors that drive home prices

- Material quality of house (OverallQual)
- property shape (Lotshape)
- Has a fireplace (Fireplaces)
- Garage space (GarageArea)
- Has a fence(HasFence)
- Basement size (TotalBSMTSF)

I also found that the biggest and clearest correlation of Average house prices was with the location.

- Created frequency table from the house prices in specific neighborhoods.
    - I grouped the neighborhoods using the elbow method to see the distribution of the houses prices in each type of group
