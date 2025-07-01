📌 Task 5: Decision Trees and Random Forests

🎯 Objectives
- Train a Decision Tree Classifier and visualize the tree structure 
- Analyze overfitting and control tree depth using hyperparameters
- Train and evaluate a Random Forest Classifier
- Compare accuracy and interpret feature importances 
- Apply cross-validation to assess generalization

🛠️ Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

📁 Dataset
- Dataset Used: Heart Disease Dataset
- Target Variable: target (1 = disease present, 0 = no disease)

✅ Steps Performed
- Loaded and explored the dataset
- Ensured data was clean
- Performed train-test split
- Trained a Decision Tree classifier
- Visualized the decision tree using plot_tree()
- Controlled overfitting using max_depth
- Trained a Random Forest classifier and compared it to the Decision Tree
- Extracted and plotted feature importances from Random Forest
- Evaluated both models using accuracy, precision, recall, and F1-score
- Applied 5-fold cross-validation to evaluate generalization

📊 Key Evaluation Metrics
| Model            | Accuracy | Cross-Validation Accuracy (5-fold) |
|------------------|----------|------------------------------------|
| Decision Tree    | 0.86     | 0.83                               |
| Random Forest    | 1.0      | 0.99                               |

📈 Visuals
- Decision Tree Visualization (plot_tree)
- Feature Importance Bar Chart

🧠 Key Concepts
- Decision Trees: Intuitive tree-based model; prone to overfitting if too deep
- Random Forest: An ensemble of decision trees; reduces overfitting and improves generalization
- Overfitting Control: Controlled with max_depth
- Feature Importance: Random Forest provides ranking of features
- Cross-Validation: Ensures model performance is consistent across splits

📎 Files
File Name                           
- Task 5.ipynb 
- heart.csv                 
- README.md

💡 What I Learned
- Building and tuning tree-based models for classification
- Visualizing and interpreting decision trees
- Controlling overfitting using tree hyperparameters
- Understanding how Random Forest improves performance
- Interpreting feature importances to explain predictions
- Using cross-validation for reliable evaluation
