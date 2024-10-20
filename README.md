# FitBit Fitness Tracker Data Analysis

## Overview

This project analyzes fitness tracker data to extract insights related to physical activity patterns, distances tracked, and caloric expenditure. The dataset consists of daily activity records collected from multiple users, providing a comprehensive overview of their fitness levels over time.

## Dataset

You can download the dataset from [dailyActivity_merged.csv](https://drive.google.com/file/d/1oqrpLWvL1OtpuSqGaQ_vpd0K2Zx-Hn_s/view?usp=drive_link).

The dataset used in this project is a CSV file containing the following columns:

- **Id**: Unique identifier for each user.
- **ActivityDate**: Date of the recorded activity.
- **TotalSteps**: Total number of steps taken in a day.
- **TotalDistance**: Total distance covered (in km).
- **TrackerDistance**: Distance tracked by the fitness device (in km).
- **LoggedActivitiesDistance**: Distance from logged activities (in km).
- **VeryActiveDistance**: Distance covered during very active minutes (in km).
- **ModeratelyActiveDistance**: Distance covered during moderately active minutes (in km).
- **LightActiveDistance**: Distance covered during light active minutes (in km).
- **SedentaryActiveDistance**: Distance covered during sedentary periods (in km).
- **VeryActiveMinutes**: Number of minutes spent in very active activities.
- **FairlyActiveMinutes**: Number of minutes spent in fairly active activities.
- **LightlyActiveMinutes**: Number of minutes spent in lightly active activities.
- **SedentaryMinutes**: Number of minutes spent in sedentary activities.
- **Calories**: Total calories burned.

## Objectives

- Clean and preprocess the dataset.
- Analyze the relationship between different activity types and total calories burned.
- Identify trends in user activity over time, including the impact of weekdays versus weekends.
- Visualize key metrics such as total steps, distance, and active minutes.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.

## Installation

To run this project, make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib
