# FIFA 23 Player Analysis Dashboard

## Tools & Skills Used

![Tableau](https://img.shields.io/badge/Tableau-Dashboard-%235778a4)
![Tableau](https://img.shields.io/badge/Tableau-Data%20Analysis-%235778a4)
![Tableau](https://img.shields.io/badge/Tableau-Interactive%20Filtering-%235778a4)  

## Quick Access

- [Raw Data](/fifa-23-dataset.csv)
- [Metadata](/fifa-23-metadata.md)
- [Tableau Workbook](/fifa-23-dashboard-revised.twbx)
- [Tableau Public Dashboard](https://public.tableau.com/app/profile/annelize.krause/viz/FIFA23PlayerInsights/PerformanceInsights)

## Project Overview

This project is part of the Masterschool Data programme focusing on data visualization and analysis using Tableau. Through multiple phases, it explores real-world player data from FIFA 23, applying best practices in dashboard design and analytical storytelling. The project aims to develop hands-on experience with data visualization that answer key performance questions, refine visualization techniques, and uncover insights into team composition, scouting, and player valuation.

The Tableau Public Dashboard can be [viewed online](https://public.tableau.com/app/profile/annelize.krause/viz/FIFA23PlayerInsights/PerformanceInsights) and the workbook can be [downloaded here](/fifa-23-dashboard-revised.twbx).

## Part 1: Initial Dashboard and Objectives

In the first part of this project, the foundation is built with essential analytical questions and core dashboard elements. It uses interactive visualizations to answer key analytical questions such as:

1. **Bar chart:** Identify the top 10 clubs with highest average player ratings
2. **Scatter plot:** Analyze how a player's potential compares to their current overall rating for each country. Add a country filter and linear trend line.
3. **Tree map:** Which clubs have the highest total player market value?
4. **Scatter plot:** Compare players' wages against their overall rating
5. **Bubble chart:** Explore how the top 20 player market value changes with potential rating. Bubble size should be defined by market value and the potential rating should be shown inside each bubble with the player’s name.
6. **Bar chart:** Identify FIFA 23’s most expensive players based on market value

The key objective is to deliver an interactive dashboard that allows users to explore key player trends using filters to drill down at country level. The goal is to understand how players from different countries fare in rating and wage, assess their growth potential, and analyze their contribution to club ratings. Dashboard to include:

- visualizations 1, 2, and 4,
- a title, a subtitle with the purpose, and a logo of your choosing, and
- optionally other filters and interactivity to help drill-down the visualization.

## Part 2: Final Objectives

In the second part of this project, the deep dive into player data continues to create impactful visualizations. The additional questions to answer are:

1. **Histogram:** Analyze the height distribution of the highest-rated players with an overall rating exceeding 85
2. **Line chart:** Determine how player key attributes (`Dribbling`, `Finishing`, `Long Shots`, `Short Passing`, `Strength` and `Stamina`) contribute to the overall rating
3. **Histogram:** Compare sprint speed distributions across different player value categories with a category bin size of 10 million.
4. **Filled map visualization:** Compare countries based on key player attributes, that includes:

- **Map View:**
  - Use a filled map to display each country colored by the average score of a selected player attribute.
  - Attribute examples include: `Acceleration`, `Aggression`, `Agility`, `Balance`, `Ball Control`, `Composure`, `Curve`, `Defensive Awareness`, `Diving`, `Dribbling`, and `Overall`.
- **Attribute Selector:** Add a parameter control to allow users to dynamically choose which attribute to visualize on the map.
- **Dynamic Coloring:** Color countries using a gradient scale based on the selected attribute's average value.
- **Tooltip Enhancements:** Display the country name and the exact average value of the selected attribute in the tooltip.
- **Highlighter Integration:** Add highlighters for player name, country, or club to support exploration by clicking or searching.
