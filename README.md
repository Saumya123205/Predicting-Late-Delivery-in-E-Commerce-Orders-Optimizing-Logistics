# Predicting-Late-Delivery-in-E-Commerce-Orders-Optimizing-Logistics
## 🔍 Objective:
 ### To identify operational bottlenecks, understand delay patterns, and build a predictive model to forecast late deliveries in e-commerce.

## 📌 Key Insights from Exploratory Data Analysis (EDA):

 ### 📊 1. Delivery Delays Distribution:

 #### • Most orders were delivered on time or earlier than expected.
 #### • However, a right-skewed distribution revealed a significant number of late deliveries.

### 📍 2. Seller State Impact:

 #### • States like Mato Grosso do Sul (MS) and Paraíba (PB) performed exceptionally, delivering ~25 days early.
 #### • States like Distrito Federal (DF) and Maranhão (MA) showed minimal early delivery, indicating inefficiencies.

### 📦 3. Product Category Performance:

 #### • Fastest delivery: fashion_roupa_infanto_juvenil, dvds_blu_ray
 #### • Slower delivery: flores, tablets_impressao_imagem

### 💰 4. Freight Value & Delay:

 #### • Higher freight costs were often associated with lower delays, suggesting that investment in logistics positively impacts timeliness.

### 📅 5. Order Day Trends:

 #### • Orders placed mid-week (Wed–Fri) tended to have lower average delays compared to those placed earlier in the week.

### 🔁 6. Actual vs. Estimated Delivery Days:

 #### • A strong correlation was observed, but variability highlighted that estimates often deviate from actual delivery times.

### 🔥 Top Delay Causes Identified:

 #### • Seller states with logistics challenges
 #### • Specific product categories
 #### • Underestimated delivery durations
 #### • Product weight and dimensions

## 🧠 Machine Learning Implementation:

 ### I built and evaluated three classification models to predict whether an order would be delivered late:

## 🏆 Random Forest (Best Performing Model)
 ### • Accuracy: 94.1%
 ### • F1 Score: 0.42
 ### • ROC AUC: 0.64

## 📈 Feature Importance:

 ### Top predictive factors:

 #### • Estimated Delivery Days
 #### • Freight Value
 #### • Product Price
 #### • Product Weight & Dimensions

## 💡 Recommendations:

 ### 🔹 Investigate and mitigate delay patterns in specific seller regions and product categories
 ### 🔹 Optimize freight strategies to improve delivery consistency
 ### 🔹 Adjust delivery time estimates based on past data
 ### 🔹 Deploy the Random Forest model in logistics systems for proactive intervention

## 🛠️ Tools & Technologies:

 ### Python | pandas | seaborn | matplotlib | scikit-learn | Random Forest | 

## About Me:

## I’m an aspiring Data Analyst / Data Scientist open to opportunities in analytics and machine learning.

## 💼 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/saumyasuteshnu-behera-50a478209/)
