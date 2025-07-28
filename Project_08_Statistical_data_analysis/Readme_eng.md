# User Behavior Analysis — GoFast Scooter Rental Service

## Project Objective  
Analyze user behavior and test business hypotheses for **GoFast**, a scooter rental service operating via a mobile app.

The data includes users from **8 cities**, with the **highest number of users in Pyatigorsk** and the **lowest in Moscow**.

---

## Key Observations

- There are **more non-subscribers** than **Ultra** subscribers.  
- User age ranges from **12 to 43 years**, with an **average of 24.9 years**.

### Distance per ride:
- **Max:** 7211 m  
- **Min:** 0.85 m  
- **Average:** 3070 m  

A minor peak occurs at ~600 m and the standard deviation is high. Possible reasons:
- Specific routes (e.g., to a metro station or bus stop)  
- Weather conditions  
- Technical issues (low battery, malfunction)  
- Time of day (e.g., rush hours)

### Ride duration:
- **Max:** 40 minutes  
- **Min:** 0.5 minutes  
- **Average:** 17.8 minutes  

A standard deviation ≈ 6 suggests few long-duration rides.  
Most users ride **up to 20 minutes**.

- Among **non-subscribers**, ~100 users annually take rides around **2 minutes**  
  → Possibly trying to complete the ride within the **free first minute**  
  → Explains the short-duration peak

- There appear to be **two user segments** among subscribers:  
  - One group takes **short rides**,  
  - The other takes **longer trips**  
  - Similar pattern observed among non-subscribers

---

## Hypotheses Tested

- **Subscribers spend more time** per ride — **Confirmed**  
- The **average ride distance for subscribers does not exceed 3130 m**  
  → Actual: **3115 m** — **Confirmed**  
- **Monthly revenue per subscriber is higher** than for non-subscribers:  
  → **Subscribers:** 362.79 ₽  
  → **Non-subscribers:** 328.64 ₽ — **Confirmed**

---

## Tools Used

- **Python**  
- `NumPy`  
- `Pandas`  
- `scipy.stats` (binom, poisson, norm)  
- `math` (sqrt, factorial)  
- `IPython.display`
