# Fish Dataset — Multiple Linear & Polynomial Regression Comparison

This project explores and compares the performance of **Multiple Linear Regression** and **Polynomial Regression** models using a fish measurement dataset. The goal is to predict outcomes and evaluate model accuracy using metrics like **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, **R² Score**, and **Adjusted R²**. Dummy data is also generated to test model predictions beyond the original dataset.

---

## Project Structure

- **`data/`**: Contains the dataset used for analysis and prediction.
- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`README.md`**: Project overview and usage instructions.


---

## Features

- Compares **Multiple Linear Regression** and **Polynomial Regression** on the same dataset.
- Uses real-world fish measurement data for training and testing.
- Generates dummy data to test model predictions.
- Outputs key evaluation metrics: MSE, RMSE, R², and Adjusted R².
- Saves trained models for reuse.

---

## Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Joblib  

---

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/nurulashraf/comparative-regression-fish-dataset.git
    cd comparative-regression-fish-dataset
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas numpy scikit-learn matplotlib joblib
    ```

3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Untitled1.ipynb
    ```

4. Run through the notebook to:
    - Train both models.
    - Evaluate performance.
    - Generate predictions for dummy data.
    - Save or load pre-trained models using `joblib`.

---

## License

This project is licensed under the [MIT License](LICENSE).
