# Football-Analysis-In-Malawi

# Malawi National Football Team Matches Analysis

## Overview
This project analyzes historical match data of the Malawi National Football Team using Python and Pandas. The dataset includes match results, venues, competition types, and statistical insights derived from the data.

## Features
### Data Cleaning
- Handling missing values in team and opponent scores
- Standardizing the 'Venue' column for consistency
- Formatting and correcting date values

### Feature Engineering
- Creating a `Goal Difference` metric
- Generating flags for match outcomes (`Win`, `Draw`, `Loss`)
- Defining location-based match indicators (`Home`, `Away`, `Neutral`)

### Data Export
- Saving the cleaned dataset in a structured CSV format

## Dataset Details
### Columns:
- `Date`: Date of the match
- `Opponent`: Name of the opposing team
- `Team Score`: Malawi team's score
- `Opponent Score`: Opponent's score
- `Result`: Match outcome (`Win`, `Draw`, `Loss`)
- `Venue`: Location of the match (`Home`, `Away`, `Neutral`)
- `Competition`: Type of tournament (`AFCON`, `World Cup Qualifier`, `Friendly`, etc.)

### Data Summary:
- **Total Matches:** 73 entries
- **Average Goals Scored per Match:** 0.83
- **Average Goals Conceded per Match:** 1.57
- **Highest Scoring Match:** Malawi 8-1 Botswana (1968)
- **Largest Defeat:** Malawi 0-12 Ghana (1962)

## Requirements
Ensure you have the following dependencies installed:
- Python 3.x
- Pandas
- NumPy

## Usage
1. Clone or download the dataset and script to your local machine.
2. Run the script to load and process the dataset:
   ```bash
   python malawi_analysis.py
