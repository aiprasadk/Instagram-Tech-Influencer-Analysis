# 📈 Tech Instagram Influencer Analysis – SQL Project

This project analyzes a tech Instagram influencer's performance data using **MySQL** to derive actionable insights on post performance, audience engagement, and content strategy optimization.

---

## 🎯 Objective

Empower a tech influencer to optimize their Instagram strategy by analyzing post performance, follower growth trends, and engagement metrics to identify high-impact content types and posting schedules.

---

## 🗃️ Dataset Structure

The dataset comprises **three core tables**:

| Table Name     | Description |
|----------------|-------------|
| `fact_content` | Post-level metrics (e.g., post type, impressions, likes, reach, comments, saves). |
| `fact_account` | Account-level metrics (e.g., profile visits, new followers, shares). |
| `dim_dates`    | Date dimension table for time-based filtering and analysis (e.g., day, month, quarter). |

---

## ❓ Key Analytical Questions

1. How many unique post types are used?
2. What are the highest and lowest impressions by post type?
3. Which posts were published on weekends in March and April?
4. What are the monthly trends in profile visits and new followers?
5. How many likes did each post category receive in July?
6. What is the monthly distribution of post categories?
7. What is the percentage breakdown of reach by post type?
8. How do comments and saves vary by category across quarters?
9. Which are the top 3 days for follower growth per month?
10. Stored Procedure: Calculate total shares per post type by week number.

---

## 📊 Key Insights & Strategic Recommendations

- **Reels dominate engagement**, accounting for **61.63%** of total reach. **Recommendation**: Prioritize Reels in content planning to maximize visibility.
- **May and June** showed peak follower growth and profile visits. **Recommendation**: Replicate content strategies from these months, focusing on high-engagement post types.
- **Weekend posts** in March and April had strong engagement. **Recommendation**: Schedule high-value content (e.g., Reels, tutorials) on weekends for optimal impact.
- **"Other Gadgets"** category led likes in July. **Recommendation**: Increase posts in this category to sustain audience interest.
- **Q2 (April–June)** was the strongest quarter for comments and saves. **Recommendation**: Analyze Q2 content themes to replicate success in future quarters.
- **Carousel posts underperformed** in engagement metrics. **Recommendation**: Experiment with new carousel formats or reduce their frequency in favor of Reels.

---

## 🧠 Skills Showcased

- **Advanced SQL**: Crafting complex queries with CTEs, aggregations, joins, date functions, and stored procedures.
- **Data-Driven Insights**: Translating raw data into actionable business recommendations.
- **Time-Based Analysis**: Leveraging date dimensions for granular trend analysis (daily, monthly, quarterly).
- **Data Storytelling**: Presenting findings in a clear, compelling narrative for stakeholder impact.

---

## 🛠️ Tools & Technologies

- **MySQL Workbench**: For query development and database management.
- **Python**: For supplementary data processing and visualization.

---

## 📬 Contact

**Prasad Kulkarni**  
🔗 [LinkedIn](https://www.linkedin.com/in/prasad7k)  
📂 [GitHub](https://github.com/aiprasadk/Instagram-Tech-Influencer-Analysis)  
📧 Email: prasad.kulkarni@example.com

---

## 🚀 Next Steps

- **A/B Testing**: Experiment with post timing and formats to further optimize engagement.
- **Sentiment Analysis**: Analyze comments to gauge audience sentiment and refine content tone.
- **Cross-Platform Expansion**: Apply insights to other platforms (e.g., YouTube, TikTok) for broader reach.
