# **Mobile App User Behavior Analysis**

## **Customer**
**Startup:** A mobile app for selling food products.

## **Project Goal**
Analyze customer behavior based on user logs and the results of an A/A/B experiment (changing the font throughout the app).

## **General Conclusion:**
Key events in the app, such as the home screen and the offer screen, occur most frequently, indicating active use of the app's basic functions. A high number of transitions to the cart screen and successful payments shows that a significant portion of users go all the way from selecting products to purchasing them. **Number of users who went from the first step to payment: 47.7%.**

### **Key Insights:**
- **Biggest User Drop:** 
  - 38.1% of users do not go from the home screen to the offer catalog. This is the most significant drop in the funnel, indicating potential problems or shortcomings in the home screen interface or in the offers displayed on it. 
- **User Flow Enhancements:**
  - 19.2% of users proceed from the offer catalog to the product card.
  - 13.5% of users move from the product card to successful payment.
  - 48.0% of users complete payment.

## **A/B Test Conclusion:**
None of the events showed statistically significant differences between the control groups (246 and 247) and the experimental group (248). **This means that the font change did not have a significant impact on user behavior for all tested events.**
## **Project Tools**
- Python
- Pandas
- Seaborn
- Plotly
