# 🏠 AUSTISIGHT — Housing Market Insights Dashboard  

> A full-scale real estate analytics solution built in Power BI to uncover pricing drivers, geo-clusters, school impact, and structural housing trends across Austin, Texas.

---

## 📌 Table of Contents  

- [Overview](#-overview)  
- [Business Problem](#-business-problem)  
- [Dataset](#-dataset)  
- [Tech Stack](#-tech-stack)  
- [Project Structure](#-project-structure)  
- [Dashboard](#-dashboard)  
- [Business Impact](#-business-impact)  
- [Research Questions](#-research-questions)  
- [Key Insights](#-key-insights)  
- [How to Run This Project](#-how-to-run-this-project)  
- [Final Recommendations](#-final-recommendations)  
- [What Makes This Project Stand Out](#-what-makes-this-project-stand-out)  
- [Ideal Use Cases](#-ideal-use-cases)  
- [Author & Contact](#-author--contact)  

---

## 🚀 Overview  

**AUSTISIGHT — Housing Market Insights** is a business intelligence solution designed to provide data-driven clarity into residential real estate performance.

It answers:

- What truly drives home prices?
- Which neighborhoods command premium valuation?
- How do schools influence property pricing?
- What structural attributes increase listing value?
- Where are high-density housing clusters located?

The dashboard is structured into 4 analytical layers:

1. Summary
2. Features
3. Location
4. School Impact 

This project simulates a real-world property analytics use case with structured data modeling, KPI engineering, and executive-focused storytelling.

---

## 🎯 Business Problem  

Real estate markets are multi-variable systems influenced by:

- Structural property attributes
- Lot size and living area
- Amenities
- School quality
- Geographic concentration
- Build year trends

Most buyers and investors rely on intuition rather than structured analytics.

This dashboard transforms raw housing data into **decision-grade intelligence**.

This dashboard transforms raw housing data into actionable intelligence for investors, developers, and decision-makers.

---

## 📂 Dataset  

The dataset includes structured housing market data such as:

- Property sale prices  
- Square footage  
- Bedrooms & bathrooms  
- Property type  
- Year built  
- Neighborhood / location  
- Sale date  

### Data Model  

<p align="center">
  <img src="https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights/blob/main/Dashboard%20Image/Data%20Model.png" width="850">
</p>

Star Schema Architecture:

- **Fact Table:** Housing-Fact      
- **Dimension Tables:**  
  - House
  - Features
  - Schools
  - Description
  - Word Summary
  - Location  
  - Property Type  
  - Property Attributes
  - Dynamic Parameter Tables 

This ensures:

- High performance  
- Accurate aggregation  
- Time intelligence capability  
- Enterprise-ready scalability  

### Key KPIs Derived:

- Property Count
- Median House Price
- Median Living Area (SqFt)
- Meadian Lot Size (SqFt)


---

## 🛠 Tech Stack  

- **Power BI** (Data Modeling & Visualization)  
- **DAX** (Advanced KPI Calculations)  
- **Power Query** (Data Cleaning & Transformation)  
- **Star Schema Architecture**  
- **Geo-Spatial Mapping**
- **Drill-through & Dynamic Filtering**  
- **Git & GitHub**  

---

## 📂 Project Structure  

📦 AUSTISIGHT---Housing-Market-Insights     
┣ 📷 Dashboard Images    
┣ 📁 Dataset    
┣ 📊 AUSTISIGHT.pbix    
┣ 📄 README.md     
┗ 📊 python-insight-generated     

---

## 🗂 Dashboard  

<p align="center">
  <img src="https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights/blob/main/Dashboard%20Image/Home%20Page.png" width="850">
</p>

The dashboard consists of **4 structured insight pages**:

---

# 1️⃣ Austin Housing Data Insight: Summary  

<p align="center">
  <img src="https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights/blob/main/Dashboard%20Image/Summary.png" width="850">
</p>

### 📊 Market Snapshot:

- **Property Count:** 15,171  
- **Median House Price:** $405,000  
- **Median Living Area:** 1,975 SqFt  
- **Median Lot Size:** 8,276 SqFt  

### Key Visuals:
- Median vs Average Price by Home Type  
- Property Distribution by Home Type  
- Properties by Build Year (1900–2020 trend)  
- Zip Code Distribution Map  
- Feature Penetration (% of homes with cooling, heating, etc.)

### Key Observations:
- Single-family homes dominate inventory.
- Cooling & heating penetration is near-universal.
- Property construction surged post-1980.
- Median vs average divergence suggests right-skewed price distribution.    

High-level market health assessment for executives & investors.

---

# 2️⃣ Austin Housing Data Insight: Features  

<p align="center">
  <img src="https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights/blob/main/Dashboard%20Image/Features.png" width="850">
</p>

### 🎯 Key Influencers Analysis

Top drivers increasing listing price:

- Bathrooms > 4.5 → +$1.09M  
- Lot Size > 28,314 SqFt → +$795K  
- Stories > 2 → +$549K  
- Bedrooms > 4 → +$464K  
- Higher School Ratings → +$312K  

### Feature-Based Price Breakdown:
- Spa & View significantly increase median price.
- Association & Garage presence impact pricing tiers.
- Feature-level comparison enables premium segmentation.

### Text Mining Insight:
Common listing words by price range:
- Lower range → "New", "Kitchen", "Room"
- Premium range → "Master", "Living", "Pool", "Private"

Indicates luxury positioning through amenity language.

---

# 3️⃣ Austin Housing Data Insight: Location  

<p align="center">
  <img src="https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights/blob/main/Dashboard%20Image/Location%20Insight.png" width="850">
</p>

### 📍 Geo-Spatial Analysis

- High-density property clusters concentrated in central Austin.
- Premium pricing pockets visible in select zip codes.
- Dynamic price slider enables cluster filtering.

### Advanced Filtering:
- Bedrooms
- Bathrooms
- Stories
- Accessibility
- Community Features
- Association / Garage / Cooling / Spa / Heating
- Year Built Range
- Home Type Segmentation

This enables hyper-targeted location strategy modeling.

---

# 4️⃣ Austin Housing Data Insight: School  

<p align="center">
  <img src="https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights/blob/main/Dashboard%20Image/School.png" width="850">
</p>

### 🎓 Education Impact Metrics

- Avg School Rating: 5.8  
- Avg School Size: 1,239  
- Median Student-Teacher Ratio: 14.8  

### Insights:
- Higher school ratings correlate strongly with premium clusters.
- Medium-to-large schools dominate high-value zones.
- Student-teacher ratio impacts mid-tier valuation bands.

Zip-level stacked analysis allows localized education-market comparison.

---

## 📈 Business Impact  

This dashboard helps:

- Identify high-growth investment zones  
- Detect undervalued properties  
- Improve pricing strategy
- Education-based valuation modeling    
- Anticipate market slowdowns   
- Provide executive-ready reporting  

---

## ❓ Research Questions  

### 1️⃣ Which neighborhoods show the strongest price appreciation?  
High-demand zones demonstrate consistent MoM growth patterns.

### 2️⃣ What property types command premium pricing?  
Larger detached homes show higher absolute values, while smaller homes often yield better price-per-sq-ft efficiency.

### 3️⃣ Is the market accelerating or cooling?  
Time-series analysis reveals seasonal patterns and cyclical corrections.

### 4️⃣ How does size influence valuation?  
Price increases non-linearly with square footage, showing threshold-based premium effects.

### 5️⃣ Are supply constraints impacting price growth?  
Inventory compression correlates with short-term price spikes, indicating seller-favored conditions.

---

## 📊 Key Insights  
1️⃣ **Price Trend -- Austin Prices Surged 35% in 3 Years — Structural, Not Cyclical**  
   
Median prices rose from $385K (2018) → $520K (2021), accelerating sharply post-2020. The +10% single-year jump in 2020 was triggered by remote-work migration, not a temporary demand spike — signaling a permanent repricing of Austin's housing stock.       
> YoY Growth: 2.6% → 10.1% → 19.6%   

2️⃣ **Market Segment -- 63% of Market Sits in the $200K–$500K Mid-Tier Band**

Price distribution shows 32% in $200–$350K and 31% in $350–$500K, with only 5.1% below $200K. The near-elimination of entry-level inventory creates a first-time buyer access crisis, while the mid-tier represents Austin's highest-volume opportunity for platforms and lenders.   
> Entry-Level (<$200K): Only 775 listings (5.1%) 

3️⃣ **Education Premium -- High School Ratings Add a Consistent 12% Structural Price Premium**   

Homes in school zones rated 4–5 stars trade at a median $335K vs. $299K in low-rated zones — a persistent $36K premium (r = 0.293 with price). This "school moat" holds across market cycles, making high-rated zones lower-volatility investments.
> Rating 4–5: $335K | Rating 2–3: $299K | Gap: +12.0%

4️⃣ **Renovation Play -- 1970–1990 Homes Are the Market's Most Undervalued Cohort**   

Mid-century builds (1970–1990) trade at a $359,900 median — 11% below 2000s homes and 26% below modern 2010–2020 builds ($454K). With Austin's land scarcity intensifying, these represent the city's highest fix-and-flip ROI corridor, with potential ARV uplifts of 25–40%.
> 1970–90: $360K vs 2010–20: $454K | Gap: $94K

5️⃣ **Price Driver -- Bathrooms Beat Square Footage as the #1 Price Predictor**

Correlation analysis across 47 features revealed bathrooms (r = 0.505) as the strongest price predictor — outperforming living area (r = 0.467). This signals a buyer shift from raw space to interior quality, with en-suite and luxury bath configurations driving disproportionate value.
> r = 0.505 vs. sq ft r = 0.467

---

## ▶ How to Run This Project  

1. Clone the repository:

```bash
git clone https://github.com/aman-theanalyst/AUSTISIGHT---Housing-Market-Insights.git
```

2. Open the `.pbix` file in Power BI Desktop.  

3. Use slicers to filter by:
   - Neighborhood  
   - Property Type  
   - Year  
   - Bedroom Count  

4. Drill down into visuals for deeper insights.

---

## 💡 Final Recommendations  

- Focus on properties with 4+ bathrooms and large lot sizes for high-end ROI.
- Target zip codes with higher school ratings for long-term appreciation.
- Prioritize investments in consistently appreciating neighborhoods.  
- Target mid-sized homes for balanced return and market liquidity.    
- Apply price-per-sq-ft benchmarking for strategic pricing decisions.  
- Leverage seasonal demand cycles for optimized entry and exit timing.  

---

## 📌 What Makes This Project Stand Out  

✔ Enterprise-ready star schema modeling  
✔ Key Influencer analytics integration
✔ Investor-focused storytelling 
✔ Geo-spatial clustering visualization
✔ Clean KPI engineering   
✔ Multi-layer dashboard architecture  
✔ Real-world real estate simulation  

---

## 🎓 Ideal Use Cases  

- Real Estate Investment Analysis  
- Property Valuation Benchmarking  
- Market Trend Monitoring  
- Urban Development Strategy  
- Executive BI Reporting  

---

## 👤 Author & Contact  

**Aman**  
Data Analyst | Business Intelligence Enthusiast  

🔗 LinkedIn  
🔗 Portfolio  

---

## ⭐ If You Found This Valuable, Give this repository a ⭐ and connect with me!
