
# Python_in_power_BI

## Introduction

This approach demonstrates an alternative way to utilize Python within Power BI, complementing traditional methods. It serves as a valuable tool for tackling challenges in data analysis, offering enhanced flexibility and powerful capabilities for deeper insights. Whether you're looking to expand your analytical toolkit or streamline complex data workflows, this integration bridges the gap between advanced scripting and intuitive visualization.

check report here: [power BI](/Overview/link)

## Background  
As data continues to grow in complexity and volume, combining tools like Power BI and Python has become increasingly valuable for data professionals. Power BI excels at creating interactive dashboards and visualizations, while Python provides advanced analytical capabilities, including statistical modeling, machine learning, and custom visualizations.  

By integrating these two tools, analysts can address limitations in traditional methods, handle more intricate datasets, and develop insights that drive better decision-making. This approach bridges the gap between traditional business intelligence and modern data science, empowering analysts to overcome challenges and deliver impactful results.

## Tools Used  

### **1. Power BI Desktop**  
- A powerful business intelligence tool used for creating interactive dashboards and visualizations.  
- Enables integration of Python scripts for advanced data analysis and transformations.  

### **2. Python**  
- A versatile programming language widely used for data analysis, machine learning, and automation.  
- Libraries used in this project:  
  - **NumPy**: For numerical operations and efficient handling of arrays.  
  - **Pandas**: For data manipulation and preprocessing.  
  - **Matplotlib**: For creating static visualizations.  
  - **Seaborn**: For enhanced statistical data visualization with built-in themes and plots.  

### **3. Command Prompt/Terminal**  
- Used for installing required Python libraries via the `pip` package manager.  

### **4. Power Query Editor**  
- A feature within Power BI for cleaning, reshaping, and preparing data before visualization.  

### **5. Seaborn’s "Tips" Dataset**  
- A sample dataset containing information about restaurant tips, used to demonstrate the integration process.  

### **6. Visual Studio Code (VSCode)**  
- A lightweight and powerful code editor used for writing and testing Python scripts.  
- Provides a rich development environment with extensions for Python and data analysis, enabling efficient coding and debugging.  

### **7. GitHub**  
- A platform for version control and collaboration, allowing users to store and manage their code repositories.  
- Used to manage and track changes in Python scripts, share projects, and collaborate with other developers or data analysts.  



## **Analysis**  

### **Overview**  
The analysis focuses on integrating Python scripting with Power BI to extend traditional data visualization and transformation capabilities. Using the Seaborn "Tips" dataset, we explore the following aspects:  
1. **Dataset Understanding**  
2. **Data Transformation**  
3. **Visualization and Insights**  

![Overview](/Assets/over_view.png) 

---

### **1. Dataset Understanding**  
The dataset contains information on restaurant tips, including:  
- **Columns**:  
  - `total_bill`: Total bill amount.  
  - `tip`: Tip given by the customer.  
  - `sex`: Gender of the customer.  
  - `smoker`: Whether the customer is a smoker.  
  - `day`: Day of the week.  
  - `time`: Time of the meal (Lunch/Dinner).  
  - `size`: Number of people in the party.  
- **Objective**: To analyze the relationship between different variables and derive actionable insights.  

---

### **2. Data Transformation**  
Key transformations performed in Power Query Editor and Python:  
- **Handling Missing Data**: Checked for and addressed any missing or null values in the dataset.  
- **Data Categorization**: Grouped `day` and `time` for ease of visualization.  
- **Calculated Columns**: Added new columns like `tip_percentage` to analyze tipping behavior.  

---

### **3. Visualization and Insights**  
Using Python libraries such as Matplotlib and Seaborn, we created the following visualizations:  
- **Total Bill Distribution**: A histogram showing the frequency distribution of total bills.  
- **Tips by Day**: A clustered bar chart illustrating tipping trends across different days of the week.  
- **Correlation Analysis**: A heatmap displaying relationships between numerical variables like `total_bill`, `tip`, and `size`.  
- **Pie Charts**: Explored categorical data like `sex` and `smoker` with pie charts.  

#### **Key Insights**  
- Customers tend to tip more during dinner compared to lunch.  
- Larger groups (`size > 4`) are associated with higher total bills but not proportionally higher tips.  
- Non-smokers tend to tip slightly more consistently than smokers.  

![Overview](/Assets/over_view%202.png) 
---

## **Conclusion**  
This analysis demonstrates the potential of combining Python with Power BI to uncover deeper insights and improve data-driven decision-making. The integration enhances flexibility, providing tools for statistical analysis, advanced visualizations, and real-time data transformation.  
