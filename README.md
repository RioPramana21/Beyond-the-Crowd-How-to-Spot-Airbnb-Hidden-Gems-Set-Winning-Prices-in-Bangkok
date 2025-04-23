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

## 📎 Credits

**Created by:** Rio Pramana  
Capstone Project Module 2 – Purwadhika Data Science & Machine Learning Bootcamp  
Connect via [LinkedIn](https://www.linkedin.com/in/riopramana/).
