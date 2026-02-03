
# Movie Rating Prediction

## Project Overview
This project focuses on building a machine learning model to predict movie ratings based on various attributes. The goal is to understand the factors influencing movie ratings and to provide a predictive tool.

## Dataset
The dataset used for this project is `IMDb Movies India.csv`, which contains information about Indian movies, including their names, years of release, duration, genres, ratings, votes, and cast/crew details.

## Features
- Data loading and initial exploration.
- Handling of missing values.
- Feature engineering (e.g., converting 'Duration' to numerical, extracting 'Year').
- Exploratory Data Analysis (EDA) to understand data distributions and relationships.
- Machine learning model training (e.g., using RandomForestRegressor).
- Model evaluation using metrics like Mean Squared Error and R-squared.

## Installation
To run this project locally, you'll need Python and several libraries. It's recommended to use a virtual environment.

```bash
# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install the required packages
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-rating-prediction.git
   cd movie-rating-prediction
   ```
2. Place the `IMDb Movies India.csv` file in the root directory of the project.
3. Open and run the Jupyter Notebook or Colab notebook provided in the repository.
   ```python
   # Example of loading the dataset in your notebook
   import pandas as pd
   df = pd.read_csv('IMDb Movies India.csv', encoding='latin1') # Or 'utf-8', 'ISO-8859-1'
   ```
4. Follow the steps in the notebook for data cleaning, EDA, model training, and evaluation.

## Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
