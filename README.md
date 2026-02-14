# Aviation Accident Analysis

# Summative Lab: Data Analysis Jet Airline Safety

## Business Problem
Identify small and large aircraft makes/models with low total destruction and low serious/fatal injury rates (1983–2023) for a client airline/airplane insurer.

## Methodology
- Removed amateur-built aircraft; filtered to 1983+ and makes with ≥50 incidents.  
- Calculated destruction and serious/fatal injury rates.  
- Conducted groupby aggregation, summary statistics, and visualizations using Pandas, Matplotlib, and Seaborn.  
- Analyzed small and large aircraft separately.  

## Key Findings

- **Small Aircraft Recommendation:** None met the minimum sample threshold in this dataset.  

- **Large Aircraft Recommendations:**  
  | Make | Model | Serious/Fatal Fraction |
  |------|-------|----------------------|
  | Bell | 47D-1 | 0.00 |
  | BOEING | 737-800 | 0.00 |
  | Maule | MX-7-235 | 0.00 |
  | DIAMOND AIRCRAFT IND INC | DA 20 C1 | 0.00 |
  | Grumman | G164B | 0.00 |
  | Beech | 19 | 0.00 |
  | Maule | M-7-235C | 0.00 |
  | Cessna | 180C | 0.00 |
  | Cessna | 310B | 0.00 |

## Safety Factors
1. **Weather Condition** — Poor weather increases destruction rate and the likelihood of serious/fatal injuries.  
2. **Phase of Flight** — Takeoff and landing phases show higher destruction rates compared to cruise.

## Evidence
Supporting tables and visualizations are included in:  
- `Aviation_Accidents_Cleaning.ipynb`  
- `Aviation_Accidents_Data_Analysis.ipynb`  
- `phase_summary.csv` and `weather_summary.csv` provide evidence for the two key safety factors.
