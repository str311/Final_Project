# Final_Project

This project explores how to predict the helpfulness of Amazon reviews using supervised machine learning models. We extract multi-source features from review texts, metadata, and contextual variables, and benchmark model performance across different learning paradigms.

## Project Structure

- **data_processing.ipynb**  
  Performs data cleaning, feature engineering, and embedding generation. This notebook includes text preprocessing, sentiment labeling, and feature export. The final output is a structured feature matrix ready for modeling.

- **Modeling.ipynb**  
  Implements and evaluates multiple regression models, including XGBoost, MLP, and KNN. It includes model selection, feature selection, and result visualization. It also tests the impact of polynomial feature expansion.

## Run the Model

You can skip the data preparation step by using our preprocessed feature matrix. Download the ready-to-use `X.csv` and `Y.csv` from the following shared folder:

👉 [Preprocessed Data (Google Drive)]([https://drive.google.com/drive/home?dmr=1&ec=wgc-drive-globalnav](https://drive.google.com/drive/folders/1Al7aFsnUYcpEU9688TbEiof_OLLTMR1g?usp=drive_link)
