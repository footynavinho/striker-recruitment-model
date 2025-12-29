# Striker Recruitment & Club Fit Model

## Overview
This project builds a data-driven striker recruitment model using publicly available FBref data.
Instead of relying on goals and assists, the model emphasizes repeatable performance indicators
such as shot generation, box presence, buildup involvement, and transition threat.

The objective is to support recruitment decision-making by identifying player profiles
that best fit different tactical environments.

## Methodology
1. Collected per-90 striker metrics from FBref
2. Removed goals and assists to reduce outcome noise
3. Normalized metrics using percentile ranks
4. Grouped metrics into tactical archetypes:
   - Box Dominator
   - Buildup Striker
   - Transition Outlet
   - Back-to-Goal Forward
5. Weighted archetypes based on club playing style
6. Generated ranked shortlists and visual player profiles

## Tools Used
- Excel (dashboarding and exploratory analysis)
- Python (pandas, NumPy, matplotlib)
- Google Colab
- GitHub

## Repository Structure
data/ Raw FBref striker data
excel/ Excel dashboard and profiling tool
python/ Python automation and modeling
outputs/ Radar visualizations and outputs

## Example Outputs
Radar charts illustrate how different forwards contribute across tactical archetypes,
allowing direct comparison of player profiles beyond traditional statistics.
