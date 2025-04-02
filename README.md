# Water-Quality-Infrastructure-Assessment
### 🌊 Water Quality & Infrastructure Assessment  

## 📌 Project Overview  
This project analyzes water quality, infrastructure improvements, and employee performance for water sources across various locations. Using SQL, we join and filter data across multiple tables to identify problematic sources, track project progress, and generate data-driven recommendations. 

![Water-Quality-Infrastructure-Assessment](images/Community.jpg)

## 🔍 Key Focus Areas  
- Evaluating water sources based on pollution data  
- Identifying infrastructure needs for different water sources  
- Tracking employee performance in improvement efforts  
- Generating recommendations (e.g., installing filters, diagnosing infrastructure issues)  

## 🗂 Database Structure  
The project utilizes the following tables:  
- **visits** – Records water source visits, queue times, and assigned employees  
- **well_pollution** – Tracks pollution levels in well water sources  
- **water_source** – Stores metadata on water sources (type, population served, etc.)  
- **location** – Contains town, province, and address data  
- **project_progress** – Monitors improvement projects, including status and comments  

## ⚡ Key Features  
✔ **Project Tracking** – Automatically updates recommendations based on water quality and queue times  
✔ **Employee Performance** – Monitors discrepancies between auditor and surveyor assessments  
✔ **Infrastructure Recommendations** – Provides improvement suggestions (e.g., adding water taps for long queues)  

## 🚀 How to Run the Project  
1. Import the SQL files from the `/sql` directory  
2. Load sample data using `data_loading.sql`  
3. Run the provided queries to analyze data and track project progress  

## 📖 Documentation  
This project is based on a dataset provided by ALX project documentation.  

📩 **Let’s collaborate to improve water infrastructure through data!** 
