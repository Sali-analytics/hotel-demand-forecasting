 
# **Hotel Demand Forecasting Project**

This project analyzes hotel booking data to understand demand patterns, pricing behavior, cancellations, and revenue trends. It also uses Facebook Prophet to forecast future hotel demand and visualize seasonality components.

The goal is to build a clear, reproducible workflow from raw data → cleaning → feature engineering → modeling → visualization → insights.

---

## **📁 Project Structure**

```
hotel-demand-forecasting/
│
├── data/
│   └── hotel_bookings_demand.csv
│
├── notebooks/
│   └── forecasting_model.ipynb
│
├── scripts/
│   └── data_preprocessing.py
│   └── visualization.py
│
├── Hotel_Demand_Forecasting_Workflow.pdf
├── README.md
```

---

## **📌 Objectives**

- Clean and prepare hotel booking data  
- Engineer key features (total nights, revenue, daily metrics)  
- Visualize demand, ADR, cancellations, and revenue  
- Build a Prophet forecasting model  
- Interpret seasonality and trends  
- Provide insights for hotel revenue management  

---

## **🛠️ Tools & Libraries**

- Python  
- Pandas  
- Matplotlib  
- Prophet  
- Jupyter Notebook  

---

## **📊 Visualizations Included**

This project includes the following visualizations:

### **1. Daily Hotel Demand**  
Shows fluctuations and seasonal booking patterns.

### **2. Daily ADR (Average Daily Rate)**  
Corrected visualization showing pricing trends over time.

### **3. Daily Cancellations**  
Daily count of canceled bookings.

### **4. Daily Revenue**  
Total revenue generated per day.

### **5. Prophet Forecast**  
90‑day demand forecast with uncertainty intervals.

### **6. Prophet Components**  
Weekly and yearly seasonality patterns.

### **7. Combined Demand, ADR, and Cancellations Over Time**  
A multi‑metric operational view.

---

## **📈 Forecasting Model**

Prophet is used to model:

- Trend  
- Weekly seasonality  
- Yearly seasonality  

The model predicts future demand and helps hotels plan staffing, pricing, and inventory.

---

## **📄 Documentation**

The full workflow is documented in:

**Hotel_Demand_Forecasting_Workflow.pdf**

This includes:

- Data preparation  
- Feature engineering  
- Modeling  
- Visualizations  
- Insights & interpretation  

---

## **🔍 Dataset**

Source: Kaggle — *Hotel Bookings Demand Dataset*  
Contains:

- arrival dates  
- ADR  
- cancellations  
- nights stayed  
- customer types  
- booking channels  
- revenue-related fields  

---

## **🚀 How to Run the Project**

1. Clone the repository  
2. Install required libraries  
3. Open the Jupyter notebook  
4. Run all cells to reproduce the workflow  

---

## **📬 Author**

**Hosea Ngo Sali**  
Hotel Revenue Analyst & Data Analytics Enthusiast  
Germany

---

 
