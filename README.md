# Data_Visualisation
Dashboard creation with PowerBI

# 📊 Google Play Store App Review Analysis (Power BI Dashboard)

This project analyzes and visualizes Google Play Store app data (focused on the **Art & Design** category) to uncover key insights about app popularity, performance, and user engagement using Power BI.

---

## 🔍 Project Objective

To explore and evaluate:
- Which apps are most popular and highly rated?
- What genres drive the most installs and reviews?
- What trends exist across ratings, reviews, and app updates?
- How engagement varies across different apps and genres

---

## 📁 Dataset

The dataset includes the following columns:
- `App`: Name of the application  
- `Category`: App category  
- `Rating`: Average user rating (out of 5)  
- `Reviews`: Number of user reviews  
- `Size`: App size in MB  
- `Installs`: Number of installs (cleaned for numeric analysis)  
- `Type`: Free or Paid  
- `Price`: App price (for paid apps)  
- `Content Rating`: Audience (Everyone, Teen, etc.)  
- `Genres`: Genre tags (can be multiple per app)  
- `Last Updated`: Last app update date  
- `Current Ver`: Current version  
- `Android Ver`: Minimum Android version required  

---

## 📌 Key KPIs and Metrics

1. **Total Apps**
2. **Average Rating**
3. **Total Installs**
4. **Review Rate** (Reviews / Installs)
5. **Most Popular Genre** (by total installs)
6. **Top 10 Apps by Installs**
7. **Category-wise App Popularity**
8. **Update Recency Distribution**

---

## 📊 Dashboard Visuals

- **Card Visuals**: High-level KPIs  
- **Bar Chart**: Top 10 Apps by Installs  
- **Treemap**: App categories based on popularity  
- **Matrix Table**: Ratings, reviews, installs, and update dates for all apps  
- **Scatter Plot**: Reviews vs Installs (bubble size = Rating)  
- **Column Chart**: Frequency of app updates (recency trend)  
- **Card (Custom DAX)**: Most Popular Genre based on total installs  

---

## 🛠️ Tools Used

- Microsoft Power BI
- DAX for custom measures
- Power Query for data cleaning and transformation

---

## 📌 Future Enhancements
Integrate sentiment analysis from app reviews (text data)

Compare performance of free vs paid apps

Include app age and update frequency as KPIs

--- 
## 🙌 Acknowledgements
Google Play Store dataset

Power BI DAX community for formula inspiration

---  
