# Data Preprocessing: Concepts:
- Why raw features cannot be fed directly to most ML model
- Encoding categorical variables: LabelEncoder, OrdinalEncoder, OneHotEncoder (pd.get_dummies)
- Feature scaling: StandardScaler (z-score), MinMaxScaler (0–1 range), RobustScaler (IQR-based)
- When to use which scaler — and why scaling matters for distance-based models
- Train/test split: train_test_split() — the golden rule of no data leakage
- Handling class imbalance: oversampling, undersampling, SMOTE (concept)
- Feature engineering basics: creating new features from existing ones
- Binning continuous variables: pd.cut(), pd.qcut()
- Pipelines in sklearn: Pipeline() — chaining preprocessing steps cleanly
- Saving and loading preprocessors: joblib.dump(), joblib.load()

## Task:
● Preprocessing Pipeline Builder: Take a mixed dataset containing numeric and categorical features with class imbalance. Build a full sklearn Pipeline that encodes categorical columns, scales numeric columns, and splits into train/test sets with no leakage. Print the shape and dtype of data at each stage. Save the fitted pipeline using joblib and reload it to transform a new batch of raw samples — demonstrating it works end to end.
