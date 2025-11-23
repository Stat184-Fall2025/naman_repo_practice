# naman_repo_practice

My first repository for STAT 184 - practicing GitHub workflows and version control

## Repository Purpose

This repository serves as a practice space for:
- Learning Git and GitHub version control
- Implementing proper branching strategies
- Managing collaborative workflows
- Storing and organizing data analysis projects

## Activity #14: US Armed Forces Data Analysis

This repository contains Activity #14, which explores patterns in U.S. Armed Forces personnel data using R and the PCIP (Plan-Code-Improve-Polish) system.

### PCIP Plan for Activity #14

#### Plan
**Goal:** Analyze the relationship between sex and rank in the U.S. Army enlisted personnel through data wrangling and visualization

**Needs:**
- Data: Google Sheets with Armed Forces personnel data
- Packages: tidyverse, googlesheets4, rvest, janitor, knitr, kableExtra, babynames, ggplot2
- Rank lookup table from web scraping
- Functions for data wrangling and visualization

**Steps:**
1. Load required packages and authenticate Google Sheets access
2. Import and wrangle Armed Forces data
3. Create two-way frequency tables for Army enlisted personnel
4. Analyze baby name popularity trends for instructional team
5. Solve the box volume optimization problem
6. Write narrative interpretations and self-reflection

#### Code
- Implement data import from Google Sheets
- Wrangle data using tidyverse (pivot, filter, join operations)
- Create visualizations with ggplot2
- Generate tables with janitor and kableExtra
- Develop custom functions for box volume calculations

#### Improve
- Debug any data import or wrangling issues
- Refine visualizations for clarity and accessibility
- Ensure narrative interpretations align with data patterns
- Check for DRY (Don't Repeat Yourself) code principles

#### Polish
- Add proper titles, labels, and captions to all visualizations
- Format tables professionally
- Ensure code readability with comments
- Verify all output renders correctly in HTML format

## Repository Maintenance Plan

### Branching Strategy
- **main branch**: Stable, production-ready code only
- **dev branch**: Active development and testing
- **feature branches**: For specific new features or analyses (if needed)

### Workflow
1. Create feature/dev branches for new work
2. Make regular commits with clear, descriptive messages
3. Test code thoroughly before merging
4. Use pull requests to merge into main
5. Keep main branch up-to-date and clean

### Commit Message Guidelines
- Use clear, concise descriptions
- Start with verb (Add, Update, Fix, Remove)
- Reference issues when applicable

### Issue Tracking
- Use GitHub Issues to track:
  - Bugs and errors
  - Feature requests
  - Analysis improvements
  - Documentation updates

## Files in This Repository

- `Activity14_ArmedForces.qmd`: Quarto document with full Activity #14 analysis
- `README.md`: This file - project overview and plans
- `LICENSE`: MIT License
- `.gitignore`: Files to exclude from version control

## Author

Naman Khandelwal  
STAT 184 - Fall 2025  
Penn State University
