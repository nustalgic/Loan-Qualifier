# Project Title

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.

---

## Technologies

The loan application app was written in Python. 
The following Python Libraries were used.

* [fire] - (https://github.com/google/python-fire) - Helps with the design of modular app building.

* [questionary] - https://github.com/tmbo/questionary - Grants you with the ability to to pull and compare data to get a desired outcome. In this case the amount of loans someone qualifies for.

---

## Installation Guide

In order for the Loan Qualifer to operate properly you'll need to run the following commands

```
pip install fire
pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```
![Loan Qualifier Prompts](Images/loan_output.png)
---

## Contributors

Brought to you by Elgin Braggs Jr.

---

## License

MIT
