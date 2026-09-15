# Power BI Practical Report 1 – Superstore Sales Dashboard

## 📊 Project Overview

This project is a Power BI Practical Report 1 completed using the Sample Superstore Sales Dataset.

The objective of this project is to clean and transform the dataset using Power Query and create an interactive Power BI dashboard containing KPI cards, charts, slicers, filters, and visual interactions.

---

## 📁 Dataset

**Dataset:** Sample Superstore Sales Dataset  
**Source:** Kaggle  
**Rows:** Approximately 9,994 rows

### Dataset Link

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

### Important Columns

- Order Date
- Ship Date
- Ship Mode
- Segment
- Country
- City
- State
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query
- Microsoft Excel / CSV
- GitHub

---

## 🔄 Data Cleaning & Transformation

The following transformations were performed in Power Query:

1. Connected the Superstore dataset to Power BI.
2. Explored the Power Query Editor.
3. Renamed columns for better readability.
4. Changed data types for date and numerical columns.
5. Removed null values from the Profit column.
6. Filtered Segment to keep only:
   - Consumer
   - Corporate
7. Split Order ID using the `-` delimiter.
8. Created an Order Region Code column.
9. Removed unnecessary columns:
   - Row ID
   - Country
   - Postal Code
10. Applied the cleaned data to the Power BI model.

---

## 📈 Dashboard Features

### KPI Cards

The dashboard contains four KPI cards:

- Total Sales
- Total Profit
- Total Quantity
- Average Discount

### Charts

Two main bar charts were created:

- Total Sales by Product Category
- Total Profit by Region

### Slicers

Interactive slicers were added for:

- Region
- Category

### Filters

The following filters were configured:

- Ship Mode:
  - Standard Class
  - Second Class
- Top 5 Sub-Categories by Sales

---

## 🎨 Dashboard Formatting

The dashboard was formatted using:

- 16:9 page layout
- Light grey background
- Red `#CC0000` primary colour
- Charcoal `#4A4A4A` secondary colour
- Formatted data labels
- Formatted KPI cards
- Meaningful visual titles
- Subtitle on the dashboard
- Gridlines and Snap to Grid
- Built-in Power BI theme

---

## 🔗 Visual Interactions

Visual interactions were configured using Power BI's Edit Interactions feature.

The dashboard supports cross-filtering between visuals.

For example, selecting a product category such as **Technology** changes the relevant chart while the KPI cards remain unchanged.

Multiple visual interaction pairs were configured and tested.

---

## 📄 Report Pages

### Page 1 – Dashboard

Contains:

- KPI cards
- Sales by Category chart
- Profit by Region chart
- Region slicer
- Category slicer
- Filters
- Interactive visual elements

### Page 2 – Detailed Order Data

Contains a detailed table with order information including:

- Order ID
- Order Date
- Customer
- Category
- Sub Category
- Sales
- Quantity
- Discount
- Profit

---

## 📸 Screenshots

Screenshots of the completed Power BI dashboard and detailed data page are included in the `screenshots` folder.

### Dashboard

Add your screenshot here:

```markdown
![Power BI Dashboard](screenshots/dashboard.png)
