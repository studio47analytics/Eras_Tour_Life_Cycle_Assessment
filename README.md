# Eras_Tour_Life_Cycle_Assessment
**Taylor Swift | Eras Tour LCA**

This project quantifies the life cycle CO₂ emissions of Taylor Swift’s private jet flights during the Eras Tour, using robust data cleaning, trip classification, and emissions analytics. It demonstrates advanced data engineering, visualization, and executive reporting—designed to meet the standards of aerospace sustainability and LCA teams.

**Author:** Austin McCollough
**studio.47 Analytics**
**Date:** September 2025
**Tools:** Python, Pandas, Matplotlib
**Full Report & Code:** [Google Drive - Taylor Swift LCA](https://drive.google.com/drive/folders/1woP1VchGFpONwi_ejhfrOYhZ-9GdjV7_?usp=sharing)

# Table of Contents

- Project Overview
- Problem Statement
- Solution Design
- Methodology
- Business Impact
- Implementation Recommendations
- Expected Benefits and Costs
- Risks and Challenges
- Next Steps
- Full Report & Code

## Project Overview

This project delivers a transparent, data-driven Life Cycle Assessment (LCA) of Taylor Swift’s private jet usage during the Eras Tour (2023–2024). Leveraging advanced data cleaning, trip classification, and emissions quantification, the analysis reveals the true environmental impact of high-frequency, high-profile private air travel.

## Problem Statement

Celebrity private jet travel is a significant but under-examined driver of aviation emissions. Key challenges include:
Lack of transparency around trip purposes and emissions.
High variability in travel patterns (tour, personal, romantic).
Outlier behaviors (e.g., rapid city-hopping) that disproportionately increase impact.
Need for actionable insights to inform sustainability and policy.

## Solution Design

Comprehensive LCA Workflow:
Data Integration: Combined public flight logs, celebrity trackers, and manual research.
Trip Classification: Used trip notes/context to label flights as Tour, Personal – Romantic, or Personal – Residence.
Emissions Calculation: Applied reported fuel burn and ICAO/ICCT conversion factors for robust estimates.
Outlier Detection: Flagged high-impact days and rapid multi-city sequences.

## Methodology

1. **Data Preparation**
Standardized dates, airport/city names, and numeric fields.
Removed duplicates, handled missing values, and validated all records.

2. **Trip Purpose Classification**
Analyzed the “Notes” field to assign each flight to a meaningful category.

3. **Emissions Analysis**
Calculated total and per-flight CO₂ emissions using provided fuel burn and industry-standard factors.
Identified and quantified emissions from outlier trips.

4. **Visualization & Reporting**
Generated pie, bar, line, and scatter charts for executive-level insights.
Benchmarked against average American/global citizen footprints.

## Business Impact

* Transparency: Quantifies the true environmental cost of celebrity private air travel.
* Benchmarking: Provides a template for LCA of other high-profile individuals or fleets.
* Actionable Insights: Identifies specific behaviors (e.g., daytrips, non-essential flights) driving avoidable emissions.
* Sustainability Strategy: Informs both public discourse and internal sustainability efforts for aviation stakeholders.

## Implementation Recommendations

Adopt LCA and analytics frameworks for all private and corporate aviation clients.
Integrate trip purpose classification for more granular emissions reporting.
Monitor and flag outlier behaviors to target reduction efforts.
Communicate findings through clear, visual reporting to drive awareness and change.

## Expected Benefits and Costs

Benefits:
* Improved emissions transparency and accountability.
Data-driven recommendations for emissions reduction.
Enhanced stakeholder trust and public reputation.

Costs:
* Initial investment in data collection and analysis.
Ongoing resources for monitoring and reporting.

Estimated Payback:  
* Immediate reputational benefits; long-term cost savings via targeted emissions reduction.

## Risks and Challenges

* Data Quality: Incomplete or inconsistent flight logs require ongoing validation.
* Attribution: Distinguishing between tour-related and personal travel needs robust classification.
* Interpretability: Communicating nuanced findings to both technical and non-technical audiences.

## Next Steps

1. Expand LCA methodology to other artists, executives, and fleets.
2. Integrate real-time flight tracking and automated trip classification.
3. 4. Develop dashboards for ongoing emissions monitoring and reporting.
Explore partnerships with sustainability teams (e.g., Rolls-Royce, major airlines).

# Full Report & Code

Access the complete project report, code, and analysis here:  
[Google Drive - Taylor Swift LCA](https://drive.google.com/drive/folders/1woP1VchGFpONwi_ejhfrOYhZ-9GdjV7_?usp=sharing)

Access all original datasets and supporting resources for this project here:  

[Google Drive – Datasets & Resources](https://drive.google.com/drive/folders/1ZUxy-J5qt071J7XSvKBr3N3x5aH1YjlK?usp=share_link)

Access all original datasets and supporting resources for this project here:

[Google Drive – Datasets & Resources]

For questions or collaboration, please reach out:

GitHub: https://github.com/studio47Analytics  
Email: amcco.datascience@gmail.com
