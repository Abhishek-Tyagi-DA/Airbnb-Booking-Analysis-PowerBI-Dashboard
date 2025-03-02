# Airbnb-Booking-Analysis-PowerBI-Dashboard
## Overview
This project analyzes hotel booking cancellations using a dataset provided by Airbnb. The goal of the project is to provide insights into various factors that influence booking cancellations across city and resort hotels. The project utilizes Excel for data preprocessing and Tableau for visualization and dashboard creation.

## Dataset
The dataset consists of Airbnb booking information including:
- **Customer demographics**: Age, nationality, etc.
- **Booking details**: Check-in/check-out dates, length of stay, and total cost.
- **Room features**: Type of property, number of rooms, amenities.
- 
![Image](https://github.com/user-attachments/assets/e7b609cd-d7fc-4402-adac-0af141075f6a)

## **Tools Used**
**Excel:** Used for data cleaning, preprocessing, and ensuring data quality.
**PowerBI:** Used for creating interactive visualizations and dashboards to analyze hotel bookings and cancellations.

## **Project Workflow**
### **1. Data Preprocessing (Excel)**

a. Removed duplicate rows, reducing the dataset size from 119,000 rows to 87,396 rows.

b. Checked for and confirmed there were no null values in the dataset.

c. The dataset contained various columns like reservation date, customer type, market segment, hotel type, booking status (booked/canceled), etc.

### **2. Visualization and Dashboard Creation (PowerBI)**
**Booking vs. Cancellation Over Time:** A line graph showing booking and cancellation trends from 2015 to 2017.

**City vs. Resort Analysis:** Pie charts visualizing the distribution of bookings and cancellations between city hotels and resort hotels.

**Customer Type Analysis:** Bar charts analyzing bookings and cancellations by customer types (Transient, Transient-Party, Contract, Group).

**Market Segment Analysis:** A bar chart analyzing the market segments (Online TA, Offline TA, Direct, Groups, Corporate, Complementary, etc.) for bookings and cancellations.


## **Key Metrics**

**Total Bookings:** 87,396

**Total Cancellations:** 24,025 (27.49% cancellation rate)

**Current Year (CY) Bookings:** 29,910

**CY Cancellations:** 8,005 (26.76% cancellation rate)

**Previous Year (PY) Bookings:** 43,927

**PY Cancellations:** 12,779 (29.08% cancellation rate)

![Image](https://github.com/user-attachments/assets/5587d11d-1bbf-42fc-b61c-dcc7f9bc7ac4)

### **Booking Distribution:**

**City Hotels:** 61.13% of bookings

**Resort Hotels:** 38.87% of bookings

### **Cancellation Distribution:**

**City Hotels:** 66.80% of cancellations

**Resort Hotels:** 33.20% of cancellations

## **Insights**

### **Booking vs. Cancellation Trends:**

  Cancellations and bookings both showed peaks and troughs around 2016. Towards the end of the analyzed period, bookings and cancellations declined.

### **City vs. Resort Hotels:**

  The majority of bookings (61.13%) are in city hotels, but city hotels also account for a higher share of cancellations (66.80%).

### **Customer Type Analysis:**

1. The largest customer segment, Transient, has the highest number of bookings (71,986) and cancellations (21,672).

2. Group and Contract segments have relatively fewer cancellations, indicating more committed bookings.

### **Market Segment Analysis:**

1. Online Travel Agencies (OTAs) dominate the bookings (51,618) and cancellations (18,245).

2. Offline TA/TO also showed significant bookings, followed by Direct bookings.

## **Future Enhancements**

**Predictive Modeling:**
1. Use machine learning techniques to predict future cancellations based on historical data.

2. Deeper Customer Segmentation: Analyze the cancellation behavior of different customer segments in more detail.

3. Actionable Insights: Recommend strategies for hotels to reduce cancellations, such as offering special incentives for certain customer types or market segments.

![Image](https://github.com/user-attachments/assets/8198fc18-1cc7-44a8-ab42-faee795e0f71)

## **Conclusion**

This project successfully visualizes booking and cancellation trends, providing actionable insights that can help hotel management optimize their strategies and reduce cancellation rates. The interactive Tableau dashboard allows users to explore the data through filters and slicers, making it easy to understand the relationship between bookings and cancellations across different segments.

## Installation

To run this project locally, open this link:

https://app.powerbi.com/view?r=eyJrIjoiYzE0NjBlNDQtOWJiOS00Yjk0LTk2N2QtYTRjNTA2MDNmYzBiIiwidCI6ImE3OGQ1M2IzLTNiMGYtNDIzMy1iMGYyLTRkYjhlNGJkMWQ4MCJ9&pageName=ReportSection



