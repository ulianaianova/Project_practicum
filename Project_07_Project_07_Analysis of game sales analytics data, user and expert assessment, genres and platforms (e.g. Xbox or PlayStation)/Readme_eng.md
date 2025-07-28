# Video Game Sales Analysis: Historical Data, User & Critic Ratings, Genres, and Platforms

## Project Objective  
Using historical data on video game sales, user and critic ratings, genres, and platforms (e.g., Xbox, PlayStation), identify key factors contributing to a game's success.  
Based on the analysis, provide recommendations for the 2017 marketing campaign.

---

## Hypothesis Testing

### Hypothesis 1: Average user ratings for **Xbox One** and **PC** are the same  
- **Null Hypothesis (H₀):** µ_Xbox = µ_PC  
- **Alternative Hypothesis (H₁):** µ_Xbox ≠ µ_PC  
- **Result:** p-value > 0.05 → no reason to reject the null hypothesis  
**Conclusion:** User ratings for Xbox One and PC do not significantly differ.

### Hypothesis 2: Average user ratings for **Action** and **Sports** genres are different  
- **Null Hypothesis (H₀):** µ_Action = µ_Sports  
- **Alternative Hypothesis (H₁):** µ_Action ≠ µ_Sports  
- **Result:** p-value < 0.05 → reject the null hypothesis  
**Conclusion:** User ratings for Action and Sports genres significantly differ.

---

## Key Patterns Influencing Game Success

### Platform Preferences:
- **North America:** Most popular platforms are **PS4** and **Xbox One**, especially in **Action**, **Shooter**, and **Sports** genres  
- **Europe:** High popularity for **PC** and PS4, with similar genre preferences  
- **Japan:** Dominated by the **3DS** platform, with strong preference for **RPG**, **Action**, and **Fighting** genres

### Genre Popularity:
- **Action** and **Shooter** are globally dominant  
- **Sports** is especially important in North America  
- **RPG** and **Fighting** are top choices among Japanese audiences

### Role of User Ratings:
- Higher user ratings correlate with better sales  
- Differences in ratings reflect player preferences and game quality

---

## 2017 Marketing Campaign Recommendations

### By Region:

- **Europe:**  
  - Focus on advertising for **PS4** and **PC**  
  - Target genres: **Action**, **Shooter**, **Sports**  
  - Promote both AAA titles and indie games, particularly on PC

- **Japan:**  
  - Prioritize **3DS** platform  
  - Focus genres: **RPG**, **Action**, **Fighting**  
  - Leverage popular local franchises in campaign planning

- **North America:**  
  - Emphasize **PS4** and **Xbox One**  
  - Focus on **Action**, **Shooter**, **Sports**  
  - Consider **ESRB ratings** — critical for purchase decisions in this region

### ESRB Ratings:
- **North America:** High impact (e.g., “M” for mature can reduce sales)  
- **Europe & Japan:** Less influential but still relevant

### Role of Critic & User Reviews:
- Positive critic and user ratings boost sales  
- Especially in the U.S., critic reviews heavily influence purchasing behavior

### Promotion Strategies:
1. **Localized marketing:** Tailor campaigns by region based on platform and genre preferences  
2. **Highlight high ratings:** Use strong reviews to build trust  
3. **Platform-based promos:** Offer exclusives for **PS4** or spotlight **3DS** in Japan  
4. **Influencer marketing:** Partner with local bloggers and streamers

---

## Conclusion

- No statistical difference in user ratings between **Xbox One** and **PC**  
- Statistically significant difference in user ratings between **Action** and **Sports** genres  
- 2017 marketing campaigns should consider:
  - Regional preferences  
  - Genre/platform popularity  
  - ESRB impact  
  - Influence of reviews

---

## Tools Used
- **Python**  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `numpy`  
- `scipy`

---

## 💡 Skills Applied
- **Data preprocessing:** cleaning, transforming, handling missing values  
- **Exploratory Data Analysis (EDA):** visualization and pattern discovery  
- **Descriptive statistics:** mean, median, standard deviation  
- **Statistical hypothesis testing:** t-tests, comparing group differences
