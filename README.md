# Financial-Planning-In-Singapore
Financial planning involves the assessment of the current situation, setting financial goals, and establishing a feasible plan (U.S. Bank, 2021). The goal of financial planning is for individuals and organizations to be in control of their financial situation and prepare for any potential expenses that may arise (Franklin Templeton, n.d.). Financial planning allows individuals to be aware of investment and financing options available to them, allowing them to maximize their finances.

# Proposal
The solution proposed is the Financial Planner, an application that uses time series forecasting to estimate the price of housing and cars for the next 10 years. Three categories of data were considered: HDB flat prices, rental prices, and vehicle prices.

Different regression models were used to forecast the HDB sale prices, rental prices, and vehicle prices respectively (Seek et al., 2023). Vehicle prices were calculated by summing COE prices and the Open Market Value (OMV) of vehicles.

The two methods used are Kernel Ridge Regression (KRR) and Linear Regression (LR) (See Appendix A). KRR is suitable for smaller datasets, as it is too computationally expensive to generate complex models for larger datasets (Unzueta, 2021). LR in comparison generates simpler models which use fewer computational resources. 

# Rationale
Financial planning is highly important in Singapore due to several reasons

* __High Cost of Living__: Effective financial planning helps individuals manage their expenses, save for future needs, and ensure a comfortable lifestyle.

* __Retirement Needs__: Singapore has an aging population, and individuals need to plan for their retirement to maintain their standard of living. With the CPF system and other retirement planning options, it's crucial to 
                    start early and make informed decisions to accumulate sufficient funds for retirement.

* __Volatile Economic Environment__: Singapore's economy is heavily influenced by global factors, making it susceptible to economic fluctuations. Financial planning helps individuals build a resilient financial foundation, 
                                 diversify their investments, and mitigate risks associated with economic uncertainties.

* __Education Expenses__: Education is highly valued in Singapore, and the cost of quality education can be significant. Effective financial planning helps parents save for their children's education and manage the expenses 
                      associated with school fees, tuition, and overseas education.

* __Increasing Life Expectancy__: Financial planning considers the need for long-term care and healthcare expenses in later stages of life, ensuring individuals can maintain their quality of life without straining their 
                              finances.


Hence, financial planning is vital in Singapore for individuals to navigate through unique challenges of the local economy, secure financial well-being, and achieve long-term financial goals. It provides individuals with a roadmap to make informed financial decisions, maximize savings, and protect themselves and their families from unexpected events.

 ![image](https://github.com/alexksh2/8-April-2022-Financial-Planning/assets/138288828/bb742180-b800-43c3-8fda-bd0d2dfda553)


 # Description
The following sections provide more details on the components of the project.

1. Prediction of HDB Housing Price and Rental Price
2. Prediction of Vehicle Price (Car Price / Motorcycle Price + COE Price)
3. Financial Planning Application


# Datasets
The file dependencies can be found in data.zip

__1. Regression of Car Price__
   - carprice.ipynb (File dependency: out.xlsx)

__2. Regression of Motorcycle Price__
   - motorcycle.ipynb (File dependency: BIKE DETAILS.csv)

__3. Regression of HDB flat resale prices__
   - housing.ipynb (File dependency: ALL prices 1990-2021 mar.csv)

__4. Regression of HDB flats rental prices__
   - rental.ipynb  (File dependency: rental price data.csv)


# Contributions 
__Alex Khoo, Anakin Seek, Yih Ming__
