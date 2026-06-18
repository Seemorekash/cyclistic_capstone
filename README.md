# Cyclistic Case Study: Comparing Casual Riders and Annual Members

## Overview

This project analyzes 2019 Cyclistic bike-share trip data to understand how casual riders and annual members use the service differently. The objective is to generate business insights that can help Cyclistic design marketing strategies to convert more casual riders into annual members.

## Business Objective

Cyclistic wants to increase the number of annual memberships. This analysis compares rider behavior across trip duration, weekly activity, hourly ride timing, and station usage to identify patterns that can support membership conversion strategies.

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Analysis Process

The project involved:

- loading and combining four quarterly trip datasets
- aligning mismatched column names across files
- engineering new features such as ride length, day of week, and hour of day
- cleaning the data to remove invalid ride durations and irrelevant rider types
- comparing rider behavior through visual analysis

## Key Insights

- Annual members take more rides overall and are more active on weekdays
- Annual members show stronger ride peaks during commuting hours
- Casual riders tend to take longer rides
- Casual riders show relatively stronger weekend and midday activity
- These patterns suggest annual members use Cyclistic more for routine transportation, while casual riders use it more for leisure and flexible travel

## Recommendations

- Target casual riders with weekend and leisure-focused membership campaigns
- Emphasize convenience and cost savings for repeat riders
- Use high-traffic casual rider stations as conversion touchpoints
- Promote trial membership offers for frequent casual users

## Repository Structure

- `notebooks/` — analysis notebooks
- `README.md` — project summary
