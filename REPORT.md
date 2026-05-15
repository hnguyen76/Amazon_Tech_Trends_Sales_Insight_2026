# Amazon Big Sales Dataset 2026 - Professional Analysis Report

Created by Hieu Nguyen

## Executive Summary

This report analyzes 100 Amazon technology products across four categories: Accessories, Audio, Electronics, and Computers. The dataset includes product price, customer rating, and review count. Because the dataset does not include units sold or realized revenue, this analysis uses **sales potential** as a transparent proxy:

```text
Sales Potential = Price_USD x Review_Count
```

The portfolio shows strong customer engagement, with 483,421 total reviews and a 4.29 average rating. Computers has the strongest sales potential despite having the fewest products, while Accessories has the broadest assortment and the highest category-level average rating.

## Portfolio KPIs

| Metric | Value |
|---|---:|
| Total products | 100 |
| Categories | 4 |
| Average price | $738.97 |
| Price range | $23.23 to $1,476.80 |
| Average rating | 4.29 |
| Total reviews | 483,421 |
| Average reviews per product | 4,834 |
| Estimated sales potential | $349.0M |

## Category Performance

| Category | Products | Avg Price | Avg Rating | Total Reviews | Sales Potential |
|---|---:|---:|---:|---:|---:|
| Accessories | 29 | $826.43 | 4.35 | 121,536 | $92.1M |
| Audio | 27 | $701.05 | 4.30 | 116,311 | $77.3M |
| Electronics | 23 | $620.84 | 4.27 | 131,383 | $81.7M |
| Computers | 21 | $796.35 | 4.21 | 114,191 | $97.9M |

## Key Insights

1. **Computers is the strongest value pool.** It has only 21 products, but it leads the dataset in sales potential at $97.9M. This suggests fewer SKUs with higher commercial leverage.
2. **Accessories is the best assortment category.** It has the most products and the highest average rating, making it a strong candidate for bundles, cross-sell placement, and broad promotional coverage.
3. **Electronics owns the largest review base.** Electronics leads total reviews with 131,383, which points to strong market visibility and demand signal.
4. **The market spans premium and value tiers.** Product prices range from $23.23 to $1,476.80, so pricing decisions should be segmented by category, rating, and review momentum.
5. **High reviews plus high price drive the strongest opportunities.** The largest sales-potential products are not always the highest-rated products; review depth and price both matter.

## Top Products by Review Count

| Rank | Product | Category | Price | Rating | Reviews |
|---:|---|---|---:|---:|---:|
| 1 | USB-C Hub Model-10 | Accessories | $784.80 | 4.8 | 9,953 |
| 2 | External SSD Model-20 | Accessories | $647.02 | 3.6 | 9,779 |
| 3 | Smart Watch Model-72 | Accessories | $419.88 | 4.7 | 9,704 |
| 4 | Webcam Pro Model-18 | Electronics | $149.62 | 4.6 | 9,704 |
| 5 | Gaming Laptop Model-26 | Electronics | $506.59 | 4.9 | 9,645 |

## Top Products by Sales Potential

| Rank | Product | Category | Price | Rating | Reviews | Sales Potential |
|---:|---|---|---:|---:|---:|---:|
| 1 | Mechanical Keyboard Model-87 | Computers | $1,296.17 | 4.1 | 7,984 | $10.3M |
| 2 | Bluetooth Headphones Model-32 | Computers | $1,143.05 | 4.0 | 8,112 | $9.3M |
| 3 | Mechanical Keyboard Model-53 | Computers | $1,002.45 | 4.1 | 8,880 | $8.9M |
| 4 | VR Headset Model-24 | Audio | $1,233.49 | 4.1 | 7,205 | $8.9M |
| 5 | USB-C Hub Model-89 | Audio | $1,016.97 | 4.9 | 8,651 | $8.8M |

## Recommendations

1. Prioritize Computers SKUs for inventory protection, ad budget, and pricing review because the category has the highest sales-potential concentration.
2. Use Accessories as the main cross-sell and bundle category because it combines broad assortment with the highest average satisfaction.
3. Turn the strongest review leaders into campaign anchors, especially USB-C Hub Model-10, Smart Watch Model-72, and Gaming Laptop Model-26.
4. Investigate lower-rated high-review products such as External SSD Model-20. Strong demand with weaker rating can indicate a product-improvement or review-management opportunity.
5. Segment pricing decisions by product family and customer response. High price alone is not a weakness when review momentum and rating remain strong.

## Data Notes

- Source file: `Amazon_Big_Sales_Dataset_2026.csv`
- Fields analyzed: `Product_ID`, `Product_Name`, `Category`, `Price_USD`, `Rating`, `Review_Count`
- Missing values observed: none in the analyzed fields
- Duplicate product IDs observed: none
- Sales potential is an analytical proxy, not actual revenue

