# Advertising Conversion Rate Analysis

## 📌 Project Overview
This project analyzes advertising conversion performance across different audience groups, devices, content formats, and geographic regions. The objective is to identify high-performing customer segments and determine the key factors driving conversion rates. Both descriptive analytics and predictive modeling were applied to generate actionable recommendations for improving marketing efficiency and ROI.

---

## 📊 Executive Summary
Two audience segments stand out as the strongest performers:

- **Fitness Lovers — 8.7% conversion rate (n=187)**
- **Young Adults — 8.4% conversion rate (n=208)**

Their conversion performance varies significantly by device, format, and geography:

- **Fitness Lovers** convert best on **tablet ads** in the **USA**  
- **Young Adults** respond most strongly to **text campaigns** in **India**

A decision-tree model confirms that **audience type**, **location**, and **device type** are the strongest predictors of conversion.

### **Strategic Recommendations**
- Prioritize Fitness Lovers with **tablet-based image/video ads** in USA and Canada  
- Target Young Adults with **text-led campaigns** in India and the UK  
- Reduce budget in underperforming segments and markets  

---

## 🔍 Approach
A three-step analytical framework was used:

### **1️⃣ Segmentation Performance**
Measured conversion rates across five audience groups.

### **2️⃣ Distribution Analysis**
Deep-dive into top segments (Fitness Lovers & Young Adults) by:
- Content type  
- Device type  
- Geography  

### **3️⃣ Predictive Validation**
A decision tree model confirms the importance of:
- Audience type  
- Location  
- Device type  

This combination of descriptive and predictive methods ensures robust insights.

---

## 📈 Key Findings

### **1. Segment Performance**
- Fitness Lovers: **8.7%**  
- Young Adults: **8.4%**  
- Family Oriented: **7.6%**

➡️ Focus should remain on the top two audience groups.

---

### **2. Distribution Insights**

#### **Fitness Lovers**
- **Content:** Images (8.8%) and Videos (8.7%) outperform text  
- **Device:** Tablets achieve the highest conversion (**9.4%**)  
- **Geography:** USA (9.6%) and Canada (9.0%) lead  
**→ Recommendation:** Tablet-based visual ads in USA/Canada  

#### **Young Adults**
- **Content:** Text ads convert best (**8.9%**)  
- **Device:** Tablets lead (**8.6%**)  
- **Geography:** India (9.6%) and UK outperform USA  
**→ Recommendation:** Text-led campaigns in India/UK  

---

### **3. Predictive Model Insights**
- Audience type = strongest predictor  
- Location = second strongest  
- Device type = third  
- Video content shows minimal independent effect  
- Feature importance:
  - Location: **20%**
  - Audience Type: **17%**

---

## 🎯 Strategic Recommendations
- Prioritize Fitness Lovers with tablet-based image/video ads in USA/Canada  
- Target Young Adults with text-led campaigns in India/UK  
- Reduce spend in underperforming markets  
- Shift budget away from low-performing content types/devices  

---

## 📚 Dataset Description
This dataset simulates digital advertising campaign performance, containing user-level engagement data across demographics, device usage, and content interactions.  
It is designed for testing segmentation strategies and ROI optimization.

### **Key Features**
- `user_id` — unique user identifier  
- `timestamp` — interaction time  
- `device_type` — Mobile / Desktop / Tablet  
- `location` — e.g., USA, UK, Canada  
- `age_group` — e.g., 18–24, 25–34  
- `gender`  
- `content_type` — Text / Image / Video  
- `ad_topic`  
- `ad_target_audience`  
- `click_through_rate`  
- `conversion_rate`  
- `engagement_level`  
- `view_time`  
- `cost_per_click`  
- `ROI_Category` — Low / Medium / High  

---
