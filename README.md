# airbnb-booking-prediction-austin
Predicting Airbnb booking trends in Austin using PySpark ML models, EDA, and visualizations for real-time decision insights.

# Real-Time Airbnb Booking Prediction – Austin, TX

This project aims to harness predictive analytics to optimize Airbnb booking experiences in Austin, Texas. Through extensive feature engineering, machine learning models, and data visualizations, the project identifies trends and patterns influencing real-time reservations.

## 📌 Project Overview

The goal of the study is to predict the likelihood of a real-time reservation of a listing. By evaluating various features—such as location, room type, review count, and pricing—we aim to build machine learning models that assist Airbnb in creating a more efficient and personalized booking flow.

## 🧠 Key Objectives

- Build predictive models to estimate real-time booking probability
- Explore how listing features influence customer preferences
- Provide recommendations to enhance Airbnb's customer experience

## 📈 Dataset Information

- **Total Records**: ~13,800 listings
- **Features**: 18 columns including host/customer details, location, room type, pricing, reviews
- **Challenges**: Missing values, inconsistent formats

## 🔍 Data Analysis & Modeling

- **Data Cleaning & EDA**: Jupyter Notebook, handled nulls and outliers
- **Feature Engineering**: Created `booking_rate` classification
- **Models Used**:
  - Logistic Regression (Accuracy: ~42.7%)
  - Random Forest (Accuracy: ~48.9%)
  - SVM with RBF kernel (Best accuracy: ~46.9%)
  - PCA for dimensionality reduction

## 🖼️ Visualizations

- Heatmaps & distribution plots of listings per zip code
- Monthly trend analysis of booking rates vs reviews
- Bar plots of room types and booking behavior

## ⚙️ Tools & Technologies

- **PySpark** (MLlib for modeling)
- **Databricks** (for scalable data processing)
- **Jupyter Notebook** (for EDA & visualization)
- **CSV Dataset**: Airbnb listings (Austin, TX)

## 💡 Key Insight

While the models offered moderate accuracy, the dataset proved more effective for **descriptive analysis** than high-accuracy prediction. Real value lies in the visual exploration of booking patterns, useful for Airbnb’s marketing and operational decisions.

## 👥 Team Members

- Vaeshnavi Reddy Alla  
- Bhargava Devarakonda  
- Dheeraj Akash Dokuparthy  
- Satya Sai Karri  
- Varsha Monala  

**Course**: AIT 614 – Big Data Essentials  
**Instructor**: Dr. Lindi Liao  
**Semester**: Spring 2024 | George Mason University  

---

📌 *This project showcases the power of real-time analytics in optimizing customer experience in the hospitality sector.*  
Contributions and feedback are welcome!
