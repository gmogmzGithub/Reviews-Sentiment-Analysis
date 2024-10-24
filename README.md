# Amazon Alexa Reviews Analysis

## Project Overview
This project analyzes Amazon Alexa reviews data to extract insights about customer feedback, ratings, and product variations. The analysis includes data visualization and text analysis components to understand customer sentiment and common themes in reviews.

## Features
- Analysis of customer feedback distribution (positive vs negative)
- Rating distribution visualization
- Product variation analysis
- Word cloud generation from verified customer reviews
- Comprehensive data visualization using Seaborn and Matplotlib

## Technologies Used
- Python 3.x
- pandas: Data manipulation and analysis
- numpy: Numerical computing
- seaborn: Statistical data visualization
- matplotlib: Creating static, animated, and interactive visualizations
- wordcloud: Text visualization

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/amazon-alexa-analysis.git
cd amazon-alexa-analysis
```

2. Install required packages:
```bash
pip install pandas numpy seaborn matplotlib wordcloud
```

## Data
The project uses a TSV (Tab-Separated Values) file containing Amazon Alexa reviews with the following columns:
- verified_reviews: Customer review text
- feedback: Binary feedback (1 for positive, 0 for negative)
- rating: Product rating
- variation: Product variation/model

## Analysis Components

### 1. Data Loading and Exploration
- Loads the Amazon Alexa reviews dataset
- Performs initial data exploration using pandas
- Generates basic statistical summaries

### 2. Visualization
The project includes several visualizations:
- Feedback distribution plot showing positive vs negative reviews
- Rating distribution analysis
- Product variation comparison
- Word cloud visualization of review content

## Usage
```python
# Run the analysis script
python alexa_analysis.py
```

## Sample Visualizations
The analysis generates several visualizations:
- Distribution of customer feedback (positive/negative)
- Rating distribution across all reviews
- Product variation comparison
- Word cloud of commonly used terms in reviews

## Future Improvements
- Implement sentiment analysis on review text
- Add statistical testing for significance
- Create interactive visualizations
- Add time-series analysis of reviews
- Implement machine learning models for review classification

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

