# Project 3: Password Security Analysis and Policy Design

[![Project](https://img.shields.io/badge/Project-3-blue?style=for-the-badge)](https://img.shields.io)
[![Language](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python)](https://python.org)
[![Focus](https://img.shields.io/badge/Focus-Password%20Security-darkgreen?style=for-the-badge)](https://img.shields.io)

## Summary
This project analyzes password quality using Python and Jupyter, identifies risky password patterns, and proposes a practical password policy for safer credential management.

## Objective
- Evaluate password strength using dataset-driven analysis
- Detect weak patterns and password reuse
- Demonstrate secure hashing techniques
- Build visual insights for reporting
- Design a practical corporate password policy

## Folder Contents
```text
3_Password Security Analysis & Policy Design/
|- README.md
|- Data/
|  |- sample_passwords.csv
|- notebooks/
|  |- Password_Analysis.ipynb
|  |- reports/
|- Password_Policy/
|- Report/
|- Screenshot/
```

## Analysis Workflow
1. Loaded and validated dataset records.
2. Explored password length and complexity trends.
3. Checked reuse and common-pattern risk indicators.
4. Demonstrated bcrypt hashing for secure storage.
5. Generated plots and documented insights.
6. Prepared policy recommendations.

## Key Findings
- Short and predictable passwords significantly reduce security strength.
- Password reuse creates high lateral-risk potential across accounts.
- Better security outcomes are linked to longer and more diverse passwords.

## Tools and Technologies
- Python
- pandas
- matplotlib
- seaborn
- bcrypt
- Jupyter Notebook

## Deliverables
- Dataset in Data folder
- Notebook and outputs in notebooks
- Policy artifact in Password_Policy
- Written report in Report folder
- Visual evidence in Screenshot folder

## Security Recommendation Snapshot
- Prefer passphrases over short complex-only passwords.
- Enforce uniqueness across systems and services.
- Store only hashed passwords using strong adaptive algorithms.
- Rotate and review policy controls periodically.
