# Racial Diversity and Quality of Life in New York State Counties

🤖An R analysis that explores whether county-level racial diversity is related to quality of life across New York's 62 counties. It combines 2010 U.S. Census data with County Health Rankings (Robert Wood Johnson Foundation) quality-of-life ranks, builds a diversity index for each county, and visualizes the results with maps and boxplots.

Table of Contents
Overview
Data Sources
Methodology
Visualizations
Getting Started
Project Structure
Notes and Limitations
Tech Stack

👓 OVERVIEW

Questions this project explores:

How does racial composition vary across New York counties?
How can that variation be summarized with a single diversity measure?
Do counties with higher racial diversity tend to have higher or lower quality-of-life rankings?

What the script does:

Using the  2010 Decennial Census (SF1) data for every NY county through the Census API, including county geometry for mapping
We calculate the racial percentages and a Simpson's Diversity Index per county
Merging the Census data with RWJF county quality-of-life rankings
And produces choropleth maps and boxplots, then combines them into a single 2x2 figures.


[RPLOTS QUALITY OF LIFE LAB 7.pdf](https://github.com/user-attachments/files/32881460/RPLOTS.QUALITY.OF.LIFE.LAB.7.pdf)

