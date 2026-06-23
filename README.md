# 📱 Smartphone Hardware-to-Price Value Analysis

## Objective

Analyze smartphone value-for-money across 930 smartphone models released between 2014 and 2025 by comparing launch prices against a custom hardware scoring model.

### Tools Used

- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Dashboard Design
- Data Visualization
- Feature Engineering
- Statistical Analysis

### Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- KPI Development
- Dashboard Development
- Business Intelligence
- Data Storytelling

---

## Project Overview

This project analyzes smartphone value-for-money by comparing hardware specifications against launch prices across 930 smartphone models released between 2014 and 2025.

The goal was to determine:

- Which smartphone brands deliver the best value for money
- Which market tiers (Budget, Mid-range, Flagship) provide the highest pricing efficiency
- How smartphone value has evolved over time
- Whether rising smartphone prices are justified by hardware improvements

To accomplish this, I developed a custom Specs Score and Price-to-Specs Ratio to measure how much hardware consumers receive for every dollar spent.

---

## Dataset Overview

| Metric | Value |
|----------|----------|
| Total Smartphones Analyzed | 930 |
| Brands | 19 |
| Years Covered | 2014–2025 |
| Market Segments | Budget, Mid-range, Flagship |
| Variables | RAM, Storage, Cameras, Battery, Display Size, Processor Tier, Launch Price |

---

## Business Problem

Smartphone prices have steadily increased over the years, but consumers often struggle to determine whether those higher prices translate into meaningful hardware improvements.

This project investigates which brands and device categories provide the strongest value-for-money by comparing smartphone specifications against launch prices using a custom scoring model.

---

## Data Preparation

The dataset was cleaned and transformed using Power Query.

### Data Cleaning Tasks

- Removed duplicate records
- Standardized smartphone brand names
- Converted specification values into numerical formats
- Validated launch price data
- Organized devices into Budget, Mid-range, and Flagship tiers
- Created calculated fields for analysis

---

## Feature Engineering

### Specs Score

A custom hardware scoring system was developed using:

- RAM Capacity
- Internal Storage
- Processor Tier
- Camera Configuration
- Battery Capacity
- Display Size

Higher scores indicate stronger overall hardware specifications.

### Price-to-Specs Ratio

Price ÷ Specs Score

Lower values indicate better value-for-money.

---

## Dashboard

<img width="613" height="654" alt="dashboard" src="https://github.com/user-attachments/assets/745a9125-1c77-4e2e-86d7-8790e292451a" />


---

## Key Findings

### 1. Price to Specs ratio Top 10 (2014 / 2025)

<img width="637" height="323" alt="Price to Specs ration top 10" src="https://github.com/user-attachments/assets/34008787-6b0d-4f54-b0c3-1d25309d0771" />

<img width="637" height="345" alt="Scatter Plot Tier Ranking" src="https://github.com/user-attachments/assets/694316dd-1845-4f12-9a8f-6cbcf8b3c722" />

The scatter plot reveals a clear positive correlation between Specs Score and launch price across all tiers, but with significant variance. Budget devices (blue) cluster tightly along a steeper value line, while Flagship devices (orange) show wider price dispersion at similar spec levels—suggesting brand premium pricing rather than hardware-driven costs. Mid-range devices (grey) occupy the middle ground, offering a compromise between the two.

- Price-to-Specs Ratio decreased from 42.86 in 2014 to 9.72 in 2025.
- Hardware value improved by approximately 77%.

### 2. Best Value Smartphone Brands

<img width="629" height="340" alt="Best Value By Brand" src="https://github.com/user-attachments/assets/69b4ffaa-1e67-438a-ae2f-92e0562396ba" />


1. iQOO
2. Realme
3. Infinix
4. POCO
5. Xiaomi

### 3. Flagship Smartphones Deliver Lower Value

<img width="634" height="341" alt="Chipset Value Ranking" src="https://github.com/user-attachments/assets/0fe1841c-5555-450e-b75d-84b9191b836b" />

| Tier | Ratio |
|--------|--------|
| Budget | 10.22 |
| Mid-range | 10.76 |
| Flagship | 18.46 |

Flagship devices cost approximately 81% more per hardware point than budget devices.

### 4. Hardware Improvements Outpaced Price Inflation

<img width="633" height="329" alt="Hardware improvement" src="https://github.com/user-attachments/assets/ec13c428-de45-4bb2-a6c0-7f4a5956573f" />
<img width="631" height="336" alt="Smartphone Value Trend" src="https://github.com/user-attachments/assets/ed218b71-daac-4350-b803-2a14665ef905" />
<img width="633" height="405" alt="Price Inflattion avg" src="https://github.com/user-attachments/assets/abd01380-7296-4f96-b48f-b20f8500e7f8" />

Hardware specifications improved faster than smartphone prices, resulting in better overall consumer value.

---

## Data Limitations

- **Specs Score Weighting:** The custom Specs Score applies equal implicit weighting to RAM, storage, processor, camera, battery, and display. Real-world user value may vary (e.g., a photography-focused user might prioritize camera over battery).
- **Missing Variables:** Build quality, software update longevity, brand ecosystem, and after-sales support are not captured in the hardware score.
- **Launch Price Only:** Prices reflect launch MSRP and do not account for depreciation, discounts, or regional tax variations.
- **Processor Tier Assignment:** Processors were categorized into tiers rather than using benchmark scores, which may obscure performance differences within tiers.

---

## Business Recommendations

### For Consumers

Consider Mid-range and Upper Mid-range devices for the strongest balance between price and performance.

### For Manufacturers

Focus on pricing efficiency as hardware improvements alone may not justify significant price premiums.

### For Retailers

Promote value-oriented brands such as iQOO, Realme, POCO, and Infinix to cost-conscious consumers.

---

## Skills Demonstrated

### Analytics

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- KPI Development
- Trend Analysis

### Excel

- Power Query
- Pivot Tables
- Pivot Charts
- Dashboard Development

### Business Intelligence

- Market Research
- Pricing Analysis
- Competitive Benchmarking
- Data Storytelling

---

## Conclusion

This project demonstrates how data analytics can be used to evaluate product value beyond simple price comparisons.

By developing a custom Specs Score and Price-to-Specs Ratio, I identified which smartphone brands, models, and market segments deliver the strongest value while uncovering long-term trends in smartphone pricing and hardware development.

---

## Next Steps

This analysis establishes a baseline for hardware-to-price value. The next phase of this research will explore **Regional Price Comparison**—analyzing how smartphone pricing, taxes, and availability vary across global markets for the same device models.
