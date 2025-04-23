![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat&logo=Jupyter&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=Tableau&logoColor=white)
![Geopandas](https://img.shields.io/badge/GeoPandas-1.0.0+-lightgrey?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogIDxwYXRoIGZpbGw9IiMzNzc2RkYiIGQ9Ik00NjAsMTQ0QzQ2MCw2NC40NDg5IDM5NS41NTExLDAsMzE2LDBIMTQ2QzY2LjQ0ODksMCwwLDY0LjQ0ODksMCwxNDRWNDQ3Ljg2QzAsNDk0LjM0MywzNC41NjE0LDUxMiw3Ny4zMzY3LDUxMkgyNjBDMjkyLjQ4Myw1MTIsMzI4LDQ3Ni40ODMsMzI4LDQzNEgyNjhDMjY4LDQ1NC4xMywyNTEuMTMsNDcwLDIzMSw0NzBIMTAwLjY2N1Y0MDBIMzE2QzM5NS41NTExLDQwMCw0NjAsMzM1LjU1MSw0NjAsMjU2VjE0NFoiLz4KPC9zdmc+)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# 🏡 Beyond the Crowd: How to Spot Airbnb Hidden Gems & Set Winning Prices in Bangkok

> 📍 A data-driven exploration to help new Airbnb hosts thrive in Bangkok’s fast-recovering tourism market.

---

## SCQA Framework

### Situation  
Following Bangkok’s full tourism reopening in July 2022, international arrivals surged by **142% year-over-year** in 2023, reviving the city’s Airbnb market. As competition returns, new hosts are often unsure **where to start** and **how to price** effectively in this dynamic environment.

### Complication  
Popular areas are overcrowded, making it hard for new listings to stand out. Meanwhile, many high-potential neighborhoods remain **undervalued** or **underutilized**, but are difficult to identify without proper data. Pricing strategy is also a challenge, most hosts rely on guesswork rather than evidence.

### Question  
How can new Airbnb hosts in Bangkok:  
1. Find **neighborhoods** with high demand but low competition?  
2. Set **competitive prices** backed by real-world market behavior?

### Answer  
This project introduces a two-part strategy:
1. **Discover Hidden Gems**: Neighborhoods with strong demand but low supply  
2. **Set Smart Prices**: Using peer-based benchmarks from similar listings

Explore the full interactive story here:  
📊 **[Tableau Dashboard – Beyond the Crowd](https://public.tableau.com/app/profile/rio.pramana/viz/BeyondtheCrowdHowtoSpotAirbnbHiddenGemsSetWinningPricesinBangkok/BeyondtheCrowdHowtoSpotAirbnbHiddenGemsSetWinningPricesinBangkok)**

You can view the full end-to-end analysis in the original Jupyter Notebook:

👉 **[📓 Click here to open the notebook on GitHub](https://github.com/RioPramana21/Beyond-the-Crowd-How-to-Spot-Airbnb-Hidden-Gems-Set-Winning-Prices-in-Bangkok/blob/main/Beyond%20the%20Crowd%20-%20How%20to%20Spot%20Airbnb%20Hidden%20Gems%20%26%20Set%20Winning%20Prices%20in%20Bangkok.ipynb)**

---

## Business Questions Answered

1. **Which neighborhoods are Hidden Gems?**  
   Lat Krabang, Phasi Charoen, and Chom Thong were identified as high-demand, low-supply areas ideal for new hosts.

2. **How do they compare to popular zones?**  
   Hidden gems offer similar demand but significantly lower competition and prices, making them strong strategic entry points.

3. **What drives price?**  
   Price is positively correlated with demand and negatively correlated with distance to attractions. These factors explain the emergence of pricing hotspots near central landmarks.

4. **How can we set fair and competitive prices?**  
   A peer-based pricing method was built using neighborhoods with similar demand and distance metrics. In cases with few peers, fallback logic was applied using internal price percentiles.

---

## Key Statistical Highlights

- **Mann-Whitney U Tests** confirmed:
  - Pricing hotspots are statistically more expensive  
  - Popular areas are significantly more saturated  
  - Peer groups are comparable in most cases

- **Spearman correlations**:
  - Price ↑ with demand  
  - Price ↓ with distance from tourist attractions

- **Hidden gems had small sample sizes**  
  Visual and logical reasoning still support their strategic potential, even if some group comparisons weren’t statistically significant

---

## Methodology Summary

- Data aggregated by neighborhood using cleaned Airbnb listings (Bangkok, late 2022)
- Custom scoring system used to identify **Hidden Gems**
- Peer pricing benchmark created using **demand** and **distance tolerance**
- Statistical tests (Mann-Whitney, Spearman) used to validate insights

---

## 💼 Final Recommendations

1. **List in Hidden Gems**  
   Lat Krabang, Phasi Charoen, and Chom Thong offer favorable market conditions for new hosts.

2. **Prioritize Demand & Proximity to Attractions:**  
   Focus on areas that have strong guest demand and are close to tourist hotspots, these factors are proven drivers of higher pricing.

3. **Avoid Oversaturated Areas (For Now)**  
   Popular areas like Khlong Toei and Wattana are competitive and better suited for experienced hosts.

4. **Use Peer-Based Pricing**  
   Base your price range on demand-distance matched peers:  
   - Phasi Charoen: **THB 988 – 1,072**  
   - Chom Thong: **THB 975 – 1,094**  
   - Lat Krabang: **THB 650 – 1,494** *(fallback range used)*

---

## 🧰 Tools & Technologies Used

- **Python**: `pandas`, `numpy`, `geopandas`, `matplotlib`, `seaborn`, `folium`, `scipy.stats`
- **Tableau**: For interactive storytelling and final visual dashboards
- **Jupyter Notebook**: For exploratory data analysis and statistical testing
- **Git & GitHub**: For version control and project publication

---

## 📎 Credits

**Created by:** Rio Pramana  
Capstone Project Module 2 – Purwadhika Data Science & Machine Learning Bootcamp  
Connect via [LinkedIn](https://www.linkedin.com/in/riopramana/).
