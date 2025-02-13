# Fitness Tracker Data Analysis

Welcome to the **Fitness Tracker Data Analysis** project! This repository contains an exploratory data analysis (EDA) of fitness tracker datasets. Our aim is to uncover trends in daily activity, sleep patterns, and device usage that can help drive improvements in health and wellness.

## Table of Contents

- [Overview](#overview)
- [Data Description](#data-description)
- [Project Phases](#project-phases)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Setup and Usage](#setup-and-usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project analyzes data from multiple CSV files covering users' daily physical activities, hourly step counts, and sleep logs. By cleaning, merging, and visualizing the data, we identify user behaviors and trends that can be valuable for developers of fitness tracking devices and health enthusiasts alike.

## Data Description

The analysis uses data from four main sources:

- **Daily Activity Data**: Contains details about steps taken, distances covered, and calories burned.
- **Hourly Steps Data**: Captures the number of steps recorded on an hourly basis.
- **Sleep Data**: Logs daily sleep metrics such as total minutes asleep and time in bed.
- **Weight Log Data**: Includes users’ weight records (this dataset was set aside due to limited sample size).

> **Note:** The weight data was excluded from most analyses because it only covers a small subset of users.

## Project Phases

The project is broken down into the following key phases:

1. **Understanding the Data**  
   - Import and inspect CSV files  
   - Check structure and summary statistics  

2. **Data Cleaning**  
   - Remove duplicate records  
   - Standardize column names and convert date/time formats  
   - Merge activity and sleep data for combined insights

3. **Analysis and Visualization**  
   - Calculate descriptive statistics for steps, calories, and sleep duration  
   - Use scatter plots and heat maps to explore relationships and trends  
   - Segment users by activity levels and usage patterns

4. **Insights and Recommendations**  
   - Summarize the key findings  
   - Provide actionable suggestions to improve device engagement and promote healthier lifestyles

## Key Insights

- **Activity Levels**:  
   Users average around 8,500 steps per day, which is below the 10,000-step goal often recommended by the CDC for a healthy lifestyle.

   67% of the day is spent being inactive, indicating a need for better engagement strategies from wellness device companies.

- **Caloric Burn**:  
  There is a positive correlation between daily steps and calories burned, meaning users who move more tend to lose more calories.

  However, there is little to no correlation between steps taken and sleep duration, suggesting that physical activity does not significantly impact sleep patterns.

- **Sleep Patterns**:  
   On average, users sleep about **7 hours per night**, with minimal correlation between sleep duration and physical activity.

- **Usage Trends**:  
   Users are most active during lunchtime and after work hours on weekdays and around midday on weekends.
   Wellness companies should encourage movement in the morning and afternoon hours, where inactivity is higher.

- **Device Engagement**:  
   88% of users log data for more than 20 days per month, showing strong engagement with fitness tracking devices.
   However, 12% of users use the tracker less frequently, highlighting the need for gamification, rewards, and reminders to improve consistency.

- **Data Limitations**:  
   Weight log and heart rate data are insufficient for detailed analysis. Encouraging users to enable these features could provide better insights.
   The dataset was collected in 2016, before the 2020 pandemic, which significantly changed people's behavior. More recent data is needed for up-to-date consumer insights.

## Recommendations

Based on the analysis, consider the following recommendations:
- **Boost Daily Activity**: Encourage users to meet daily step goals through gamification, reminders, or challenges.
- **Enhance Sleep Tracking**: Provide deeper insights and tips to help users improve their sleep quality.
- **Increase User Engagement**: Implement features like leaderboards, rewards, and personalized tips to maintain high usage rates.
- **Target Peak Activity Periods**: Tailor notifications or challenges during times when users are most active, such as lunch and early evenings.

## Setup and Usage

### Prerequisites
- **R** (version 4.0 or above) and **RStudio**
- Required R packages: `tidyverse`, `janitor`, `lubridate`

