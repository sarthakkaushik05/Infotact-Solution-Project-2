# Infotact-Solution-Project-2

# SaaS / E-Commerce Cohort Retention & CLTV Analysis

An end-to-end implementation of Project 2 from the Infotact Data Analytics brief. It cleans transaction data, creates cohort-retention matrices, calculates historical CLTV by acquisition channel, segments customers, and produces executive-ready visuals.

## Project deliverables

| Requirement | Implementation |
| --- | --- |
| Transaction cleaning | Filters failed/refunded orders and invalid customer, quantity, and price records. |
| Cohort matrix | Calculates each customer's first-purchase month and activity month index. |
| Retention analysis | Exports absolute and percentage retention matrices. |
| CLTV analysis | Calculates AOV, purchase frequency, historical CLTV, and VIP share by channel. |
| Visualization | Produces a retention heatmap and channel-level retention-decay curves. |
| Business storytelling | Documents findings and actions in `outputs/EXECUTIVE_SUMMARY.md`. |

## Data provenance

The code creates a deterministic, realistic **synthetic** retail dataset because the public dataset host was unavailable in this environment. This makes every result reproducible while avoiding the misrepresentation of generated results as live company data. For a real submission, replace `make_transactions()` with the approved transactional data source and rerun the pipeline
