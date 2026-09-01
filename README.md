# Fuzzy Logic Student Performance Prediction System

An academic expert system that uses fuzzy logic to evaluate student performance based on multiple academic criteria.

## Overview

This project was developed as part of the **Artificial Intelligence and Advanced Applications** course of the MSc in Informatics.

The system uses a fuzzy inference approach to estimate a student's overall academic performance based on four input variables:

- **Participation:** 0–100% (Low, Medium, High)
- **Assignment Grades:** 0–100 (Poor, Average, Good)
- **Exam Grades:** 0–100 (Poor, Average, Good)
- **Absences:** 0–30 (Few, Many)

The system produces a final **Performance Score** on a scale from 0 to 100.

## Methodology

The system follows a standard fuzzy inference process:

1. **Fuzzification**  
   Input values are converted into fuzzy membership values.

2. **Rule Evaluation**  
   A knowledge base of **54 IF-THEN rules** is used to evaluate the inputs.

3. **Aggregation**  
   The outputs of the activated rules are combined into a single fuzzy output set.

4. **Defuzzification**  
   The final crisp performance score is calculated using the **Centroid Method**.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Fuzzy Logic
- Expert Systems

## Features

- Fuzzy membership functions for academic variables
- 54-rule fuzzy knowledge base
- Automated student performance evaluation
- Centroid-based defuzzification
- Visualization of fuzzy sets and results

## Installation

Install the required dependencies:

```bash
pip install numpy matplotlib





--- *Developed as an individual project for the MSc in Informatics for the 2025 academic year. .*
