**Aviation Safety Data Analysis**

This project analyzes historical aviation accident data to identify the safest aircraft models, operators, and accident causes. The goal is to provide data-driven recommendations that guide procurement decisions for safe and reliable aircraft in both commercial and private aviation operations.

**Project Overview**

Aviation safety is a critical factor in determining not only passenger trust but also operational costs and regulatory compliance. This project cleans, prepares, and visualizes accident records to identify aircraft models and manufacturers with the lowest accident severity, understand the most common causes of aviation accidents and provide recommendations to minimize safety risks and insurance costs.

**Business Understanding**

The company is launching a new aviation division to diversify into charter, cargo, and executive travel services. Entering this high-stakes industry requires strict safety measures to reduce risks and ensure sustainable operations. This analysis addresses key questions such as:

1. Which aircraft models and manufacturers have the lowest historical accident risk?

2. What are the most common causes of accidents?

3. How can safety risks and insurance costs be minimized?

The outcome is a set of actionable insights—prioritizing safer aircraft for procurement and recommending safety protocols to reduce incident risks and long-term costs.

**Data Understanding**

Source: Aviation Accident Data (Kaggle)

Size: 23,967 accident records

Features include: date, year, type (aircraft model), operator, registration, fatalities, location, country and cat (accident category/cause)

`**Limitations**

1. Missing values in registration, operator, fatalities, and location.

2. Inconsistent aircraft naming conventions.

3. Lack of exposure data (e.g., total flight hours, fleet size) means accident rates are based on absolute counts.

**Data Preparation**

Key steps in data preparation:

1. Converted date to datetime and year to numeric.

2. Standardized type values (e.g., mapping B737 → BOEING 737).

3. Converted fatalities to integers, filling missing values with 0.

4. Filled missing categorical fields with "Unknown".

5. Dropped rows with critical missing values (no date/type).

6. Saved a cleaned dataset for analysis.

**Data Analysis & Visualization**
  1. Fatalities Trend (2003–2023)**

Overall fatalities per year show fluctuations, with some years experiencing significantly higher loss of life.

  2. Safest Aircraft-Operator Combinations:

A.W. AW-650 ARGOSY 222 | BEA

A.W. AW.27 ENSIGN I | BOAC

AIRBUS A300 | American Airlines

AIRBUS A300B2-1C | Air Inter

AIRBUS A300B4 | Eastern Air Lines

These combinations had multiple accidents but zero fatalities.

  3. Accident Causes

-Most common categories: pilot error, mechanical failures, weather related incidents.

-Mechanical failures and weather accidents, while less frequent, are linked to higher fatality counts.

   4. Operator Safety

-Larger carriers with long histories have more recorded accidents, but lower fatalities per accident due to modern fleets and stronger safety protocols.

-Smaller operators often show disproportionately high fatalities per event, likely due to older fleets or weaker oversight.

**Conclusion**

-Operators with long histories may have more accidents, but not necessarily worse safety.

-Large aircraft tend to have higher fatalities per accident, while smaller aircraft crash more often but with fewer fatalities.

-Weaker-regulated operators show higher severity rates, while established global carriers maintain better safety records.

**Recommendations**

-Prioritize Modern Aircraft

-Procure models with strong safety records (e.g., Airbus A320, Boeing 737, Embraer E-jets).

-Avoid outdated wide-body and cargo conversions with consistently higher accident severity.

-Select Safer Operators

-Partner only with airlines that demonstrate compliance with ICAO/FAA/EASA standards.

-Exclude operators with high fatalities-per-accident ratios or weak oversight histories.

-Mitigate Cause-Based Risks

-Enhance pilot training and decision-making to reduce human error.

Invest in predictive maintenance for technical reliability.

Strengthen weather monitoring and enforce stricter operational go/no-go rules.





**TABLEAU DASHBOARD LINK**
https://public.tableau.com/authoring/AVIATIONSAFETYINSIGHTS_17594059024800/AVIATIONSAFETYINSIGHTS#1

