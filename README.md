# Power Query Data Transformation and Visualization

## Overview
This project involved transforming raw student registration data using Power Query Editor in Power BI. The dataset was cleaned, managed, and enhanced to ensure accuracy and meaningful analysis. After transformation, three visualizations were created to represent student registrations and payment status.

![image alt](https://github.com/bbudha77/Power-Query-Editor-Project/blob/3e95b1434bf9977a75abc9b7c462ca1f82f78232/Screenshot%202025-03-19%20204939.png)

## Data Transformation Steps


![image alt]()

### 1. Checking and Clearing Blanks
- Identified and removed blank cells in crucial columns.

### 2. Checking and Removing Duplicates
- Scanned the dataset for duplicate entries.
- Removed exact duplicates to ensure data integrity.

### 3. Creating Unique ID with Name
- Generated a unique ID for each student by combining their first name and first letter of second name together.
- Ensured uniqueness to prevent data inconsistencies.

### 4. Separating Registration Date into New Columns
- Extracted the registration date column.
- Created a new column **Terms** to categorize registrations into February and April terms based on the date.

### 5. Creating a New Payment Status Column
- Defined the payment status based on the amount paid:
  - `500` as **Full Paid**
  - `<500` as **Partial Payment**
  - `Null` as **No Payment**

## Visualizations Created
1. **Bar Chart:** Displays the number of student registrations per course.
2. **Donut Chart:** Represents the distribution of payment statuses (Full Paid, Partial Payment, No Payment).
3. **Line Chart:** Shows the trend of student registrations over the month of december.

## Conclusion
By leveraging Power Query Editor, the dataset was successfully cleaned, structured, and transformed for accurate reporting. The final visualizations provide insights into student registration trends and payment distribution, facilitating better decision-making.

