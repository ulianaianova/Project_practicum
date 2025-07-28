# Mobile App — Identifying User Segments Based on Behavior

## Project Objective  
Based on user behavior data from the **"Unwanted Things"** mobile app, determine:  
- Which user groups are more likely to return to the app  
- Which user groups are more likely to complete the target action (viewing contact details)

---

## Source Data  
- The dataset contains user event logs from the mobile app starting **October 7, 2019**  
- The platform is intended for posting ads to sell unwanted items  
- Each event records user actions such as opening item cards, clicking suggestions, viewing contact details, and more

---

## Tools Used  
Python:  
`pandas`, `numpy`, `math`, `datetime`, `matplotlib`, `seaborn`, `plotly`, `scipy.stats`, `statsmodels` (`proportions_ztest`)

---

## Skills Applied  
- **Data preprocessing**  
- **Data visualization**  
- **Presentation of business insights**

---

## Key Findings

### 1. Google, weekdays — highest conversion (24.26%)  
**Insight:** Users from Google visiting on weekdays demonstrate the highest conversion rate.  
**Recommendation:** Increase advertising investments on Google during weekdays.

---

### 2. Yandex, weekdays — high conversion, slightly lower than Google (23.45%)  
**Insight:** Yandex users are also active on weekdays.  
**Recommendation:** Optimize marketing campaigns for this segment and improve the user experience.

---

### 3. Weekends — low activity and conversion  
**Insight:** Conversion rates drop on weekends, especially for Google (16.22%) and other sources (12.96%).  
**Recommendation:** Launch weekend-specific promotions and offers. Use notifications to boost engagement.

---

### 4. Segment 0 — users spanning multiple groups  
**Insight:** Stable retention and conversion performance.  
**Recommendation:** Conduct further analysis to enable personalization and targeted communication.

---

### 5. Segment E — users from other sources (weekdays)  
**Insight:** Conversion rate is 18.34%, which is below average.  
**Recommendation:** Rework the engagement strategy by enhancing personalization and advertising for this group.

---

## Hypothesis Testing

### Hypothesis 1: Contact view conversion differs between Yandex and Google users  
- **Result:** No significant difference found  
- **Recommendation:** User behavior is similar. Focus on alternative traffic sources for differentiation.

---

### Hypothesis 2: Conversion differs between users who open item cards and those who click on suggestions  
- **Result:** No significant difference observed  
- **Recommendation:** Both actions lead to similar conversions — optimize the overall user experience accordingly.
