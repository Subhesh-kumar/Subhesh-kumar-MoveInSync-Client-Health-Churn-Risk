# MoveInSync Client Health & Churn Risk Dashboard
5 enterprise clients across Desk, Meeting Room, Visitor, Parking and Meal modules. Sample data, May to Oct 2026.

## Overview

An interactive client health and churn risk dashboard developed as part of an Implementation Project Manager assignment.

The dashboard demonstrates how usage, adoption, support performance, customer sentiment, and commercial indicators can be combined to identify accounts requiring proactive attention.

## Business Objective

- Monitor client health across multiple workplace management solutions.
- Identify declining engagement and potential churn risks.
- Track health score trends and changes over time.
- Provide actionable recommendations for Implementation and Customer Success teams.
- Support prioritisation of accounts for proactive intervention.

## Dashboard Features

- Portfolio-level client health overview.
- Client and monthly filters.
- Health score trends compared with the portfolio average.
- Health score breakdown across six dimensions.
- Churn risk flags and recommended next steps.
- Module-level adoption, utilisation, and booking performance.
- Support, SLA, CSAT, NPS, and commercial indicators.
- Adjustable scoring weights to explore different scenarios.

## Scoring Methodology

The health score combines six weighted dimensions:

| Dimension | Default Weight |
|---|---:|
| Adoption | 25% |
| Utilisation | 25% |
| Usage Trend | 15% |
| Support | 15% |
| Sentiment | 10% |
| Commercial | 10% |

Health bands:
- Healthy: 75 and above
- Watch: 50–74
- At Risk: Below 50

The churn score is calculated using the health score and identified risk flags. These thresholds and weights are illustrative and can be calibrated against historical client outcomes.

## Sample Data and Assumptions

The dashboard uses synthetic sample data for five illustrative enterprise clients across May–October 2026.

The client scenarios cover desk booking, meeting room booking, visitor management, parking management, and meal booking.

Certain client capacities, employee counts, contract values, and other operating details are assumed for demonstration purposes. The data does not represent verified MoveInSync customer records.

## Technology

- HTML
- CSS
- JavaScript
- SVG-based visualisations
- GitHub Pages for static hosting

## Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Use the client and month controls to explore the dashboard.

An internet connection may be needed to load the externally hosted fonts.

## Live Demo

Add the GitHub Pages URL here after deployment.

## Disclaimer

This is an assignment prototype using synthetic data. The health and churn scores are rule-based indicators for demonstration, not a validated predictive model trained on historical churn outcomes.
