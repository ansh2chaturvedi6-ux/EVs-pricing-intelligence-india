
#  Indian EV Pricing Intelligence & Launch Strategy

> Feature-value decomposition of 5 Indian EV brands across 18+ variants 
> to identify optimal pricing architecture for a sub-₹10L EV launch

---

##  Problem Statement

India's sub-₹15L EV segment has 5+ competing brands but no clear 
value-for-money leader. OEMs are pricing features inconsistently — 
some charge ₹1.2L extra for OTA updates, others bundle it for free. 
This creates a whitespace opportunity for a new entrant with a smarter 
variant architecture.

**Key question:** If you were launching a new EV at ₹10L, which 3 
features give maximum perceived value per rupee spent?

---

##EVs Analyzed

| Brand | Model | Variants | Price Range |
|-------|-------|----------|-------------|
| Tata | Tiago EV | 4 | ₹7.99L – ₹11.99L |
| Tata | Punch EV | 5 | ₹9.99L – ₹14.99L |
| MG | Comet EV | 3 | ₹6.99L – ₹9.99L |
| Citroën | ë-C3 | 2 | ₹11.50L – ₹12.50L |
| Hyundai | Exter EV | 4 | ₹10.00L – ₹14.00L |

---

## 🔬 Methodology

1. **Data Collection** — Variant-wise pricing scraped from official OEM 
   websites across 12 feature parameters
2. **Feature-Value Decomposition** — Calculated price premium per feature 
   using AVERAGEIF across variants with/without each feature
3. **Value Multiplier Analysis** — Compared price premium vs estimated 
   OEM implementation cost per feature
4. **Competitive Positioning** — Scored each brand on 5 axes to identify 
   whitespace
5. **RICE Prioritization** — Recommended 3-feature base variant for a 
   sub-₹10L launch

---

##  Key Findings

- **OTA connectivity** commands ₹80,000–₹1,20,000 price premium but 
  costs ~₹12,000 to implement — a **7.5x value multiplier**
- **No brand** currently offers connected features + >300km range 
  under ₹10L — clear whitespace
- **MG Comet** is most vulnerable to a new entrant due to weakest 
  range-to-price ratio in the segment

---

##  Outputs

- `data/ev_pricing_data.xlsx` — Raw variant data across 18 variants
- `analysis/ev_analysis.ipynb` — Python EDA, charts, correlation heatmap
- `output/ev_pricing_strategy.pdf` — 1-page strategy recommendation

---

##  Tools Used

`Python` `Pandas` `Matplotlib` `Seaborn` `Excel` `Canva`

---

##  Repository Structure

EVs-pricing-intelligence-india/

├── data/                  ← Raw Excel data

├── analysis/              ← Python notebook

├── output/                ← Charts and PDF

└── README.md

---

*Self project | Indian Automobile & EV Market | June 2026*
*Author: Ansh Chaturvedi | IIT Kharagpur*
