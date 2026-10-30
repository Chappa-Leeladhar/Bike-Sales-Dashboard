# Bike-Sales-Dashboard

An end-to-end Excel analysis of bike buyer data, built to show which customer segments are most likely to buy a bike. Includes data cleaning, standardization, pivot charts and an interactive dashboard with slicers.

## Business Problem

The company wants to increase bike sales but is spending its marketing budget on broad, untargeted campaigns. This project analyzes customer purchase data (1,000 customers) to find which segments are most likely to buy, so marketing spend can be focused where it converts best.

## 📊 Dashboard Preview

<img width="648" height="420" alt="Screenshot_20260807_122619" src="https://github.com/user-attachments/assets/eb368c97-1ffe-4959-8c48-9bdb5ae75458" />

## Key Insights & Recommendations

**1. Middle-aged customers (31-55) are the strongest segment.**
54% of this group bought a bike, compared with 36% of ages 18-30 and 32% of ages 56+. They also make up 81% of all buyers (388 of 481).
→ **Recommendation:** Make the 31-55 group the primary target for campaigns, and test whether messaging can lift the weaker 18-30 and 56+ groups.

**2. Commute distance matters: shorter commutes buy more.**
Customers commuting under 5 miles bought at 53%, versus 36% for those commuting 5+ miles. The lowest rate is for 11+ miles (30%).
→ **Recommendation:** Focus local and short-commute campaigns first. For long-distance commuters, test a different offer (e.g., e-bikes) before spending broadly.

**3. Income is only a weak signal on its own.**
Buyers earn slightly more on average ($60.3K vs $57.5K for non-buyers), and the gap shows in both genders (female $59.3K vs $54.9K, male $61.3K vs $59.4K). But the difference is small.
→ **Recommendation:** Don't build campaigns on income alone. Use it as a secondary filter alongside age and commute distance.

## Data Cleaning & Processing Steps

1. **Duplicates:** Removed 26 duplicate records (1,026 → 1,000 unique customers) to maintain data integrity.
2. **Standardization:** Converted codes to readable values (e.g., Marital Status 'M'/'S' → 'Married'/'Single', Gender 'M'/'F' → 'Male'/'Female').
3. **Age Brackets:** Used nested IF formulas to group customers into Adults (18-30), Middle Age (31-55) and Old Age (56+).
4. **Analysis:** Built pivot tables and pivot charts, then combined them into a dashboard with slicers.

**Tools:** Microsoft Excel (formulas, pivot tables, pivot charts, slicers)

## How to View the Project

1. Download the `.xlsx` file from this repository.
2. Open it in Microsoft Excel.
3. Go to the **Dashboard** sheet and use the slicers to filter the data interactively.
