README.txt

📁 Project Title: Network Intrusion Detection using Random Forest on KDD Cup 1999 Dataset

📌 Setup Instructions:
-----------------------
1. Requirements:
   - Python 3.12.6
   - Required Python packages:
     - pandas
     - numpy
     - matplotlib
     - seaborn
     - scikit-learn
     - joblib (optional, for model saving)

2. Environment Setup:
   - Install required packages using pip:
     pip install pandas numpy matplotlib seaborn scikit-learn

3. Download the Dataset:
   - Download the KDD Cup 1999 dataset from [KDD Cup 1999 Data](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html).
   - Unzip the dataset and place it in the `Original_Data/` folder.

4. Preprocess the Dataset:
   - Run the notebook `pre_processing_data_file.ipynb` to preprocess the dataset.
   - This will create a dataset CSV `Data/` folder.

5. Running the Project:
   - Run the notebook `Random_Forest_Classification.ipynb` step-by-step using Jupyter Notebook or VSCode with Jupyter extension.
   - The code will:
     - Perform EDA (Exploratory Data Analysis)
     - Train and evaluate a Random Forest model
     - Output classification metrics and charts

🗃️ Folder Structure:
---------------------
- Code/
  - Random_Forest_Classification.ipynb → Main notebook with full pipeline
- Cleaned_Data/
  - kddcup_cleaned_data_full.csv → Preprocessed KDD dataset used for training
- Report.pdf → Final 5-page report (summary, EDA, modeling, evaluation)
- Slides.pptx → Presentation slides
- README.txt → This file

👥 Team Contributions:
-----------------------
1. Trần Trọng Hiếu:
   - Data preprocessing
   - Random Forest model training
   - Evaluation metrics and EDA

2. Lý Duy Linh:
   - Feature analysis
   - Label encoding and balancing strategy

3. Nguyễn Thanh Viên:
   - Visualizations (correlation matrix, class distribution)
   - ROC curve plotting

4. Nguyễn Huy Hoàng:
   - Code debugging
   - Documentation and commenting

5. Nguyễn Tân Phú:
   - Report writing and slide design
   - Presentation preparation and recording

📌 Notes:
----------
- Dataset was cleaned using one-hot encoding for categorical features.
- Label was encoded to binary: `normal` = 0, `attack` = 1.
- The final model was evaluated using accuracy, precision, recall, F1 score, and ROC AUC.
- If needed, class imbalance can be addressed with `class_weight='balanced'` in the model.

🔥 End of README
