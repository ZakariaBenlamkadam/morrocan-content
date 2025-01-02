# 📊 Data Analytics Dashboard - Moroccan Content 🇲🇦

Welcome to the **Data Analytics Dashboard**, a comprehensive tool for analyzing survey responses related to social media content consumption, preferences, and engagement patterns, with a special focus on Moroccan content. 🌟

---

## ✨ Overview

The dashboard features **interactive visualizations** with filters for **age group**, **gender**, and **platform**, enabling users to explore specific data segments and gain valuable insights.

---

## 🖼️ Visualizations Structure

### 🧩 **General Structure**

The dashboard is divided into multiple sections, each featuring charts and graphs to summarize key findings:

### **📄 PAGE 1: General Insights**
- **👥 Total Responses by Age Group**:  
  - Donut chart showing age distribution (18-24, 25-34, 35-44, 45+).
  - Percentage of total responses per group.
- **📸 Instagram - Most Popular Platform**:  
  - Highlights Instagram's popularity.
- **🧑‍🤝‍🧑 Total Responses by Gender**:  
  - Donut chart showing gender distribution (Male/Female).
- **📊 Total Responses by Content Type and Age Group**:  
  - Stacked bar chart categorizing responses by content type (e.g., Comedy, Culture) and age group.
- **⏳ Total Responses by Time Frequency**:  
  - Bar graph showing daily social media usage (<1 hr, 1-2 hrs, 2-4 hrs, >4 hrs).
- **📱 Total Responses by Device and Age Group**:  
  - Stacked bar chart grouping devices (Smartphone, Tablet, Laptop) by age group.
- **📈 CountRows by Platform**:  
  - Bar chart of platform-specific responses.

### **📄 PAGE 2: Engagement & Preferences**
- **🎨 Art and Creativity - Most Preferred Content Type**:  
  - Highlights Art as the top choice.
- **🇲🇦 Following Moroccan Content**:  
  - Donut chart showing responses (Yes/No).
- **♻️ Engagement Frequency by Age Group**:  
  - Stacked bar chart of engagement frequency (Often, Occasionally, Never).
- **💬 Engagement Motivators**:  
  - Word cloud summarizing motivators for interaction.
- **📝 CountRows by Content Type**:  
  - Bar chart showing responses by content type (Art, News, Lifestyle, etc.).
- **⭐ Content Quality Perception**:  
  - Pie chart categorizing ratings (Average, Excellent, Poor).
- **📌 Engagement Suggestions**:  
  - Horizontal bar graph with suggestions for improvement.
- **🌍 Language Preferences**:  
  - Horizontal bar chart of preferred languages (Arabic, English, French).

### **📄 PAGE 3: Challenges & Diversity**
- **📚 Topics**:  
  - Horizontal bar graph categorizing responses by topics (Entrepreneurship, Culture, etc.).
- **🛠️ Strengths of Moroccan Creators**:  
  - Horizontal bar graph showing key strengths (e.g., Creativity).
- **🌈 Diversity Representation**:  
  - Pie chart indicating views on Moroccan diversity representation.
- **👗 Trends or Styles by Gender**:  
  - Stacked bar graph categorizing styles by gender.
- **❌ Challenges for Creators**:  
  - Horizontal bar graph outlining challenges (e.g., Limited reach, Monetization issues).
- **📽️ Content Format**:  
  - Donut chart categorizing responses by format (Short-form, Long-form).

### **📄 PAGE 4: Discoveries & Support**
- **🔍 Discovering New Content**:  
  - Pie chart showing discovery methods (e.g., Search engines, Social media).
- **💵 Financial Support**:  
  - Donut chart indicating financial support for creators (Yes/No).
- **🔥 Engagement Frequency by Platform**:  
  - Heatmap visualizing platform-specific engagement.

---

## 🗂️ Data Model

### **Overall Structure**
The **data model** organizes responses into **dimension tables** and a **fact table**, enabling detailed analysis of content consumption, engagement, and perceptions.

### **Dimension Tables**
- **👤 DimConsumer**: Age group, gender, and consumer ID.  
- **📖 DimContent**: Content type, language, format, and trends.  
- **📱 DimDevice**: Device type and ID.  
- **♻️ DimEngagement**: Frequency, discovery source, and motivators.  
- **📊 DimPlatform**: Platform name and ID.  
- **⭐ DimQuality**: Perception of quality, diversity, challenges, and strengths.

### **Fact Table**
- **📋 Moroccan Content**: Central table linking dimensions, with fields like consumer ID, content ID, platform ID, and daily time spent.

### **Relationships**
- One-to-many relationships link dimension tables to the **fact table**.  
  Example: One consumer can engage with multiple pieces of content.

---

## 🎯 Key Analyses Enabled
- **Content Preferences by Demographics**: Insights into age/gender-specific interests.
- **Platform Engagement Patterns**: Understand top-performing platforms.  
- **Content Quality and Diversity Perception**: Explore audience opinions.  
- **Challenges & Opportunities for Creators**: Identify barriers and strengths.  

---

## 🔗 Summary
The **Data Analytics Dashboard** provides powerful tools for understanding Moroccan social media content trends, preferences, and challenges. By combining **interactive visualizations** with a structured **data model**, this dashboard enables data-driven insights into audience behavior and content creation strategies. 🎉


[You can see the visualisations here ](https://app.powerbi.com/view?r=eyJrIjoiZDA3NWEwNDQtNDM4YS00ZDhiLWI4M2QtY2YxMDRhMzg5NzIzIiwidCI6ImMyNzg3OTIyLTExZDktNGNhOC1hYWRmLTVlZjdmZjMxYTEyNyJ9)
