# Aviation Accident Analysis

## Project Overview
This project analyzes aviation accident data (1948-2023) to provide recommendations to an airline insurer. The goal was to identify aircraft makes and models with low rates of total destruction and low likelihood of fatal/serious passenger injuries. 

*Data Cleaning:* The dataset was filtered to only include professional builds, airplanes, and events from 1983 onwards. Missing values were imputed, and key metrics (Injury Fraction and Destruction Rate) were engineered to quantify safety.

## Key Findings & Recommendations

### 1. Small Airplanes (<= 20 passengers)
*   *Safest Makes:* Stinson, Grumman, and Maule consistently showed the lowest injury fractions.
*   *Lowest Destruction Rates:* Luscombe, Grumman, and Stinson.
*   *Safest Specific Models:* The Cessna 180J, Piper PA-20, and Beech B19 had exceptionally low mean injury fractions.
*   *Recommendation:* For the small aircraft category, the insurer should offer favorable rates for Stinson or Grumman makes, and specific models like the Cessna 180J.

### 2. Large Airplanes (> 20 passengers)
*   *Safest Makes:* Boeing and Airbus dominate the top 15 for lowest injury fractions. Cessna, DeHavilland, and Grumman showed the lowest destruction rates.
*   *Safest Specific Models:* Commercial heavyweights like the Boeing 737 series, Boeing 777, and Airbus A319/A330 have exceptionally low injury fractions (near zero).
*   *Recommendation:* For large passenger jets, Boeing and Airbus are statistically the safest choices, aligning with modern commercial aviation standards.

### 3. Other Contributing Factors
*   *Weather:* Accidents in Instrument Meteorological Conditions (IMC / bad weather) result in a significantly higher mean injury fraction (~0.6) compared to Visual Meteorological Conditions (VMC / good weather) which is roughly 0.23.
*   *Purpose of Flight:* Personal flights have a notably higher mean injury fraction (~0.28) compared to Instructional flights (~0.16), likely due to varying pilot experience and aircraft types.

## Visualizations
See the Jupyter Notebook (Aviation_Accidents_Data_Analysis.ipynb) for detailed visualizations, including bar charts, violin plots, and stripplots detailing these findings.