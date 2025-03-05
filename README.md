# Flight Customer Analysis

## Project Overview
This project aims to segment flight customers based on their travel behavior using clustering techniques. By identifying different customer groups, airlines can tailor marketing strategies to improve customer retention, engagement, and loyalty.

## Dataset
The dataset contains customer flight history and loyalty program details, including:
- **MEMBER_NO**: Member ID  
- **FFP_DATE**: Frequent Flyer Program Join Date  
- **FIRST_FLIGHT_DATE**: Date of First Flight  
- **GENDER**: Gender  
- **FFP_TIER**: Frequent Flyer Program Tier  
- **WORK_CITY**: City of Origin  
- **WORK_PROVINCE**: Province of Origin  
- **WORK_COUNTRY**: Country of Origin  
- **AGE**: Customer’s Age  
- **LOAD_TIME**: Date When Data Was Collected  
- **FLIGHT_COUNT**: Number of Flights Taken by Customer  
- **BP_SUM**: Travel Plan  
- **SUM_YR_1**: Fare Revenue  
- **SUM_YR_2**: Votes Prices  
- **SEG_KM_SUM**: Total Distance (km) Flown  
- **LAST_FLIGHT_DATE**: Date of Last Flight  
- **LAST_TO_END**: Time Gap Between Last Flight and Most Recent Booking  
- **AVG_INTERVAL**: Average Time Gap  
- **MAX_INTERVAL**: Maximum Time Gap  
- **EXCHANGE_COUNT**: Number of Exchanges  
- **avg_discount**: Average Discount Received by Customer  
- **Points_Sum**: Total Points Earned by Customer  
- **Point_NotFlight**: Points Not Used by Members  

## Methodology
1. **Data Preprocessing**
   - Handling missing values (imputation based on distribution)
   - Standardizing numerical features
   - Removing unuseful features
   - Removing outliers based on distribution analysis
   - Encoding categorical data

2. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions and correlations

3. **Clustering Model (K-Means)**
   - Selecting the optimal number of clusters using **Elbow Method**
   - Applying **K-Means** clustering to segment customers

4. **Model Evaluation**
   - Evaluate clustering result using **Silhouette Score** 
   
5. **Cluster Labeling**
   - **Moderate Flyers**: Travel occasionally, low loyalty status, minimal discount usage
   - **VIP Customers & Frequent Flyers**: High-tier members, frequent travelers, frequent discount usage
   - **Inactive/Churned Customers**: Rarely travel, haven’t flown in a long time, minimal discount usage

## Business Recommendations
- **Increase Loyalty for Moderate Flyers**: Offer personalized promotions and provide exclusive offers
- **Back Strategy for Churned Customers**: Implement welcome-back bonus and targeted reactivation campaigns
- **Retention Strategy for VIP Customers**: Early access to deals, give surprising gifts, and corporate travel benefits.

## Tools & Libraries Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- **Jupyter Notebook** for analysis

## Getting Started
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flight-customer-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd flight-customer-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
- Run the Jupyter Notebook to explore the analysis:
  ```bash
  jupyter notebook
  ```
- Modify parameters and rerun clustering analysis as needed.

## Next Steps
- Deploy insights into a **dashboard for real-time monitoring**.

---
**Repository**: [https://github.com/fatimahizah/flightcustomer]

**Contact**: [fatimahizah1@gmail.com]  

**Contributors**: [Fatimah Nurul Azizah]
