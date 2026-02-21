# 🚗 Used Cars Market Analysis

<img width="832" height="900" alt="Picture0" src="https://github.com/user-attachments/assets/4ff0eb99-7791-41b5-9786-f322c51427f8" />




## 📖 Project Overview
This project involves a detailed **Exploratory Data Analysis (EDA)** of a used car dataset. The goal is to understand the factors that influence vehicle pricing, such as manufacturer brand, mileage, transmission type, and location. This analysis provides valuable insights for both buyers looking for value and sellers aiming to price their vehicles competitively.
---

## 📂 Dataset Information
* **Source:** [Kaggle](https://www.kaggle.com/)
* **Domain:** Automotive / Secondary Market
* **Data Scale:** Comprehensive listings of used vehicles with detailed specifications.

### 📋 Column Glossary (Data Dictionary)
| Column | Description |
| :--- | :--- |
| **ID** | Unique identifier for each car listing. |
| **Distributor Name** | The entity or dealership selling the vehicle. |
| **Location** | The geographic region/city where the car is located. |
| **Car Name / Model** | The specific model of the vehicle. |
| **Manufacturer Name** | The brand/make of the car (e.g., Toyota, Ford, BMW). |
| **Car Type** | The body style (e.g., Sedan, SUV, Hatchback). |
| **Color** | The exterior color of the vehicle. |
| **Gearbox** | Transmission type (Manual, Automatic, Semi-Auto). |
| **Number of Seats/Doors** | Physical configuration of the vehicle. |
| **Purchased Date** | The date the vehicle was originally bought or listed. |

---

## 📈 Key Analysis Objectives
* **Price Determinants:** Identifying which features (Year, Mileage, Brand) have the strongest correlation with the final sale price.
* **Brand Popularity:** Analyzing the distribution of manufacturers to see which brands dominate the used car market.
* **Geographic Trends:** Comparing car prices and availability across different locations.
* **Feature Impact:** Evaluating how internal specs like "Number of Seats" or "Gearbox" type affect market demand.

---


---

## 🖼️ Analysis Preview
Here are some key visualizations and data structures from the analysis:

<img width="550" height="550" alt="Picture7" src="https://github.com/user-attachments/assets/aa5a806d-fd0c-4c85-b9be-bd7feed6dad3" />
<img width="812" height="488" alt="Picture6" src="https://github.com/user-attachments/assets/845387b7-f138-45aa-863f-0425c9980b20" />
<img width="813" height="488" alt="Picture5" src="https://github.com/user-attachments/assets/c59308fd-056b-4f45-9fa1-1eaadd203313" />
<img width="655" height="394" alt="Picture4" src="https://github.com/user-attachments/assets/038b8fd8-c8b8-45b7-bf98-6ef9fe4a3051" />
<img width="656" height="394" alt="Picture3" src="https://github.com/user-attachments/assets/9742dfc3-e9f6-4414-b784-64620f83aefc" />
<img width="841" height="504" alt="Picture2" src="https://github.com/user-attachments/assets/fc828fae-d1ee-46f8-95c9-708851721a7d" />
<img width="797" height="479" alt="Picture1" src="https://github.com/user-attachments/assets/fd326efb-9780-42c9-8d6c-d6a5af6ac08d" />
<img width="800" height="480" alt="Picture10" src="https://github.com/user-attachments/assets/aea736ab-6741-4d94-9aa2-5e9ddf930dd0" />
<img width="842" height="504" alt="Picture9" src="https://github.com/user-attachments/assets/0e0a6d05-6be2-4f0f-8ca5-54ee35194269" />
<img width="550" height="550" alt="Picture8" src="https://github.com/user-attachments/assets/a384d9d7-6bb0-41e1-982d-c442d6484d08" />


---





## 🛠️ Data Cleaning & Processing
Based on the Jupyter Notebook, the following technical workflows were performed:
* **Data Inspection:** Conducted initial checks for null values and data consistency across columns like `Manufacturer Name` and `Price`.
* **Feature Identification:** Isolated key categorical variables (Color, Gearbox, Car Type) for group-by analysis.
* **Time-Series Preparation:** Processed `Purchased Date` to analyze how vehicle age impacts depreciation.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Library:** Pandas (Core Data Manipulation)
* **Tool:** Jupyter Notebook

