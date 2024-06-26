# Soccer Pass Evaluation

## Table of Contents



- [Project Overview](#project-overview)
- [Why is this Metric Interesting?](#why-is-this-metric-interesting)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Data Source](#data-source)
---

## Project Overview

This project aims to evaluate the impact of soccer passes made by individual players and the team as a whole using the Metrica Sports dataset. The primary objective is to calculate an "impact factor" for each pass, which will help in assessing the effectiveness of passes. The impact factor will be a numeric value. Additionally, this project involves choosing Game 2 of one of the three matches from the dataset.

## Why is this Metric Interesting?

The impact factor provides a quantitative measure of the effectiveness of soccer passes, allowing coaches and analysts to understand how well players and teams perform in outplaying opposing players. This information is crucial for strategic decision-making and player evaluation.
For More info Please Read the Report.pdf

---
## Getting Started

### Prerequisites
- Python (version 3.x)
- Required Python libraries (specified in `requirements.txt`)

### Installation
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/nahiid/soccer-impact-factor.git
2. Clone the dataset repository in src folder.
   ```bash
   git clone https://github.com/metrica-sports/sample-data.git
   
3. Install Requierments.
   ```bash
   pip install -r requirements.txt

## Directory Structure
This repository is organized as follows:

- **src/**: This directory contains the main project files, including the Jupyter Notebook named `impact_factor.ipynb`.
- **requirements.txt**: This file lists all the Python libraries and dependencies required to run the project.
- **Report**: Includes full explantion of the project.
- **.gitignore**: This file specifies which files or directories should be ignored by Git.
- **LICENSE**

## Data Source

The data for this project is sourced from the Metrica Sports dataset, which provides detailed tracking data for soccer matches. You can access the dataset [here](https://github.com/metrica-sports/sample-data).

---

