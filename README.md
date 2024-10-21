# COVID-19 Prediction

This repository contains the solution for the COVID-19 Prediction task from the machine learning assignment. The goal is to predict whether a person has COVID-19 based on specific symptoms.

## Table of Contents

- [Dataset](#dataset)
- [Features](#features)
- [Model Training and Prediction](#model-training-and-prediction)
- [How to Run](#how-to-run)
- [Requirements](#requirements)

## Dataset

The dataset consists of 30 samples with the following columns:

| Fever | Cough | Breathing Difficulty | COVID Positive |
|-------|-------|----------------------|-----------------|
| High  | Yes   | Yes                  | Yes             |
| Low   | No    | No                   | No              |
| High  | Yes   | Yes                  | Yes             |
| Low   | No    | Yes                  | No              |
| High  | Yes   | No                   | Yes             |
| Low   | Yes   | Yes                  | No              |
| High  | No    | Yes                  | Yes             |
| Low   | Yes   | No                   | No              |
| High  | Yes   | Yes                  | Yes             |
| Low   | No    | Yes                  | No              |
| High  | Yes   | No                   | Yes             |
| Low   | No    | No                   | No              |
| ...   | ...   | ...                  | ...             |

## Features

- **Fever**: Indicates if the person has a high or low fever.
- **Cough**: Indicates if the person has a cough (Yes/No).
- **Breathing Difficulty**: Indicates if the person has breathing difficulty (Yes/No).
- **COVID Positive**: Target variable indicating if the person tested positive for COVID-19 (Yes/No).

## Model Training and Prediction

A Decision Tree Classifier is trained using 70% of the dataset, and the model's accuracy is evaluated on the remaining 30%. The model predicts whether a person is COVID positive based on the input features. The accuracy of the model is printed as a percentage after testing.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>

   
### Instructions:
- Replace `<repository_url>` and `<directory_name>` with the actual URL and directory name of your repository.
- Adjust the sample data in the dataset if necessary to match your actual data.

Feel free to modify any sections as needed!

## Requirements
- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook
