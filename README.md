# Linear Regression on Wine Quality Dataset

This project applies Linear Regression on the Wine Quality dataset obtained from the UCI Machine Learning Repository. It includes feature selection, data visualization, and model evaluation.

## 📂 Project Structure
- `Linear-Regression.ipynb` - The main Jupyter Notebook containing the analysis.
- `data/` (optional) - Folder containing the dataset if downloaded separately.
- `README.md` - Documentation about this project.

## 📥 Dataset
The dataset is fetched directly using `ucimlrepo`:

- **Source:** UCI Machine Learning Repository
- **Dataset ID:** 186 (Wine Quality)

## 📦 Dependencies
Make sure you have the required libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo statsmodels
```

## 🚀 Running the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/JebinAbraham/Linear-Regression.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Linear-Regression
   ```
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `Linear-Regression.ipynb` and run all cells sequentially.

## 📊 Steps in Analysis
1. **Data Loading**: Fetch the dataset using `ucimlrepo`.
2. **Exploratory Data Analysis (EDA)**:
   - Check for missing values.
   - Compute Pearson correlation.
   - Visualize feature relationships using scatter plots.
3. **Feature Selection**:
   - Select important features based on correlation.
   - Consider transformation if non-linear patterns exist.
4. **Model Training**:
   - Split data into training and testing sets.
   - Train a Linear Regression model.
5. **Model Evaluation**:
   - Compute R², MSE, and RMSE for performance evaluation.
   - Interpret results and suggest improvements.

## 📈 Results & Observations
- Linear Regression performance is evaluated based on multiple metrics.
- Insights from correlation and visualization aid feature selection.
- Additional methods like feature transformation or regularization (Ridge/Lasso) may further improve results.

## 🤝 Contributions
Feel free to contribute by opening an issue or submitting a pull request!

## 📜 License
This project is licensed under the MIT License.
