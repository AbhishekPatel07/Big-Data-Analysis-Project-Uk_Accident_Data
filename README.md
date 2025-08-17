# Big-Data-Analysis-Project-Uk_Accident_Data
Big Data Analysis Project Uk_Accident_Data

## Installation
Clone the repository:
git clone https://github.com/AbhishekPatel07/Big-Data-Analysis-Project-Uk_Accident_Data.git
cd Big-Data-Analysis-Project-Uk_Accident_Data

Install dependencies:
pip install -r requirements.txt


## Running the Project
1. Download the dataset from Kaggle (link above) and place it in the `data/` folder.
2. Run preprocessing:
   python src/preprocessing.py
3. Train models:
   python src/train_models.py
4. Evaluate models:
   python src/evaluate.py
5. Alternatively, open and run the Jupyter notebooks in the `notebooks/` folder.


## Results
- Random Forest achieved the best ROC-AUC (0.763).
- XGBoost provided the best trade-off between accuracy and efficiency.
- Logistic Regression, while interpretable, struggled with severe accident detection.

### Key Visualizations:
- Confusion Matrices (Figure 2)
- Feature Importance Plots
- Correlation Heatmap

## Replication
All code and instructions are provided for reproducibility.  
Researchers and practitioners can replicate results by following the installation and run instructions above.

