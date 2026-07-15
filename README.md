# **Conversion Rate Analysis Report**
Welcome to my personal project!

This repository contains my complete data analysis project using Python for Conversion Rate (CR) Analysis and Optimization.

## 🚀 **Customer Experience Optimization & A/B Testing Result**

A comprehensive case study on "TeddyWorld" utilizing transaction and web session data (March 2012 - March 2015) to evaluate A/B testing results, diagnose funnel bottlenecks, and strategically maximize customer experience.  
* **Full-Funnel Decomposition:** Mapped the end-to-end user journey across 4 major branches to diagnose a 6.83% overall conversion rate. Uncovered a severe top-funnel bottleneck where over 55% of total traffic bounced before ever reaching a product detail page.
* **Device-Specific UI/UX Friction:** Identified a critical drop-off specifically on mobile devices, which only achieved a 32.23% product view rate compared to 49.91% on desktop. Conducted a heuristic UX evaluation revealing disruptive pop-ups, poor color contrast, and cramped navigation menus as the root causes of customer drop-off.
* **A/B Testing Validation:** Evaluated a bottom-funnel A/B test between two checkout pages (/billing vs. /billing-2). Proved that /billing-2 significantly outperformed the original in both conversion rate and Average Order Value (AOV) across all devices.
* **Strategic Revenue Projection:** Modeled future performance, calculating that rolling out the /billing-2 page to 100% of traffic would recoup testing costs and generate an additional projected revenue of $1,916 per month, elevating the baseline expected monthly revenue to $4,557.

## 🔧 **Tech Stack**

* **Pandas & NumPy –** Data ingestion, datetime conversions, handling missing values, and merging multi-level funnel tracking across sessions and pageviews.
* **Plotly –** Visualizations including dual-axis charts (`make_subplots`), step-by-step Funnel comparisons (go.Funnel), and Revenue forecast Waterfall charts (`go.Waterfall`). 

## 🌐 About Me

Hello, I’m Phuc Kien, a senior college student striving to achieve the milestones on my data journey.
I am passionate about data analysis and enjoy uncovering insights that help me better understand business problems through data.
