# 📊 User Engagement Analysis for **Restaurant Success**

## 📌 About Yelp  
Yelp is a web and mobile platform that functions as a crowd-sourced local business review site. Users can submit reviews, photos, and tips about businesses, while also browsing ratings and information shared by others.

---

## 🗂️ Agenda  
- Problem Statement  
- Research Objectives  
- Hypothesis  
- Data Overview  
- Analysis and Findings  
- Recommendations

---

## 🔍 Problem Statement  
In a competitive market like the restaurant industry, understanding factors that influence business success is crucial for stakeholders.  
Utilizing the Yelp dataset, this project investigates the relationship between user engagement (reviews, tips, and check-ins) and business success metrics (review count, ratings) for restaurants.

---

## 🎯 Research Objectives  
1. Quantify the correlation between user engagement (reviews, tips, check-ins) and business success indicators (review count, star rating).  
2. Analyze how sentiment influences review count and ratings.  
3. Explore trends in user engagement over time.  
4. Identify regional patterns and user-type differences (elite vs. non-elite).  
5. Determine peak user activity periods for restaurants.
 <img src="screenshots/Screenshot%2010.png" alt="Screenshot 10" width="900" style="float: right; margin-left: 15px;" />

---

## 🧪 Hypotheses  
- Higher levels of user engagement (more reviews, tips, and check-ins) correlate with higher review counts and ratings for restaurants.  
- Positive sentiment expressed in reviews and tips contributes to higher overall ratings and review counts.  
- Consistent engagement over time is positively associated with sustained business success.

---

## 📦 Data Overview  
- Dataset: Subset of Yelp data covering businesses across 8 metropolitan areas in the USA and Canada.  
- Source: Yelp Open Dataset (JSON format)  
- Files:  
  - `business.json`  
  - `review.json`  
  - `user.json`  
  - `tip.json`  
  - `checkin.json`  
- Stored into a SQLite database (`yelp.db`) for efficient querying and analysis.

---

## 📈 Analysis and Findings  

### ✅ General Business Metrics  
- Out of all businesses, ~35,000 are active restaurant businesses.
- Table	showing distribution of business success metrics (review	count and average rating)
 <img src="screenshots/Screenshot%2011.png" alt="Screenshot 11" width="300" style="float: right; margin-left: 15px;" />

---
<img src="screenshots/Screenshot%2012.png" alt="Screenshot 12" width="900" style="float: right; margin-left: 15px;" />
- Ratings and review counts are not directly proportional — higher ratings do not guarantee more reviews and vice versa.  
- Review count reflects user engagement, but not necessarily customer satisfaction or performance.

### ⭐ Do higher ratings mean higher engagement?
- Data shows a general increase in average review (reviews, check-ins, tips) increases up to 4-star rated restaurants.
- Restaurants rated 4 stars exhibit the highest engagement and shows a downward trend for rating above 4.
- 5-star businesses show lower engagement — possibly due to fewer but highly satisfied customers or selective clientele.
                                                   <img src="screenshots/Screenshot%2013.png" alt="Screenshot 13" width="900" style="float: right; margin-left: 15px;" />                                         
### 🔄 Correlation between Reviews, Tips, and Check-ins 
- Strong correlation observed between all three — higher activity in one correlates with higher activity in others.  
- Businesses should focus on driving all types of user engagement simultaneously.As increases in one type of engagement are likely to drive increases in others, enhancing overall visibility and interaction with customers.
<img src="screenshots/Screenshot%2014.png" alt="Screenshot 14" width="300" style="float: right; margin-left: 15px;" />


### 📊 Engagement Difference: High vs. Low-Rated Businesses  
- Data indicates a clear correlation between higher ratings and increased user engagement across reviews, tips, and check-ins.  
- This pattern underscores the importance of maintaining high service and quality standards, as these appear to drive more reviews, check-ins, and tips, which are
critical metrics of customer engagement and satisfaction.
<img src="screenshots/Screenshot%2015.png" alt="Screenshot 15" width="500" style="float: right; margin-left: 15px;" />

### 🗺️ Success Metrics Across Cities  
- **Philadelphia** emerges as the top city with the highest success score. Indicating a combination of high ratings and active user engagement  
- Followed by **Tampa**, **Indianapolis**, and **Tucson** rank amongthe top cities with significant success scores  
- Suggests thriving restaurant cultures in these locations.
<img src="screenshots/Screenshot%2016.png" alt="Screenshot 16" width="500" style="float: right; margin-left: 15px;" />  

### 📅 Time-Based User Engagement Trends  
- Successful businesses, particularly those with higher ratings (above 3.5), exhibit consistent and possibly increasing user engagement over time.
<img src="screenshots/Screenshot%2017.png" alt="Screenshot 17" width="650" style="float: right; margin-left: 15px;" />


- Trend and seasonality analysis reveals periodic spikes in user activity.
<img src="screenshots/Screenshot%2018.png" alt="Screenshot 18" width="900" style="float: right; margin-left: 15px;" />

### 💬 Sentiment Metrics (Useful, Funny, Cool)  
- These labels reflect user feedback on review quality.  
- Higher counts suggest greater satisfaction and are strong success indicators.
<img src="screenshots/Screenshot%2019.png" alt="Screenshot 19" width="400" style="float: right; margin-left: 15px;" />

### 🧑‍💼 Elite vs. Non-Elite Users  
- Yelp’s Elite users, though fewer, contribute a large portion of high-quality reviews.  
- Building strong relationships with elite users can foster loyalty and promote repeat visits.
<img src="screenshots/Screenshot%2020.png" alt="Screenshot 20" width="600" style="float: right; margin-left: 15px;" />

---

### ⏰ Busiest Hours  
<img src="screenshots/Screenshot%2021.png" alt="Screenshot 21" width="600" style="float: right; margin-left: 15px;" />
- Peak hours for user engagement: **4 PM to 1 AM**  
- Suggests focus on optimizing operations, staffing, and promotions during evening hours.

---

## ✅ Recommendations  

- Partner with Elite users to boost promotional efforts and reach.  
- Leverage peak hours for special offers and operational efficiency.  
- Less successful restaurants should work on improving review responses, service quality, and user engagement.  
- Consider expansion or strategic investment in top-performing cities.  

---

## 🙏 Thank You  
This project provides a data-driven foundation for understanding and improving restaurant success through user engagement. Feel free to explore the notebooks and insights further in the repository.
