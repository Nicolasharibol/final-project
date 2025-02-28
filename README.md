- Team: Nicolás Muñoz

- Topic: Student performance and learning styles.

- Business case: Predicting student performance. 

Objective: The central aim is to leverage data to make informed predictions about student outcomes. This can then guide interventions designed to enhance academic success and foster better educational environments.

- Data sources: kaggle.com

This Dataset is synthetically generated to simulate real-world student performance and learning habits. The Data was created using Python and the Numpy and Pandas libraries to model realistic distributions of students behaviors, studdy patterns, and academic performance. 

Data Generation process

The Data set was generated using the following logic:
1. Demographics: Randomly Assigned ages (19-30 years) and gender distribution (Male, Female, other)
2. Study Habits: Study hours per week (5-50 hours) and preferred learning styles (Visual, Auditory, Reading/Writing, Kinesthetic)
3. Online Learning and Participation: Number of online courses completed (0-20) and discussion participation (Yes/No)
4. Performance Metrics: Assignment completion rates, attendance percentages, and exam scores, all generated within a logic range.
5. Behavioral factors: Time spent on social media (0-30 hours per week), self reported stress level (Low, Medium, High), and sleep hours per night (4-10 hours).
6. Final grades: Assigned based on exam scores an A-F grading scores.

Transformation and Considerations

The Dataset follows realistic probability distributions to simulate real-world trends.
No personally identifiable information (PII) is included to maintan privacy.


----> Plan for the next 10 days

- Day 1: Define Projects's Topic, Project Business Case, Project Objective and Initial Dataset exploration.  


- Day 2: Data Wrangling and Cleaning

Cleaning: Address missing values: Explain or drop where necessary. Convert, Tranform, Group data types as needed for analysis.

Wrangling: Remove duplicates and irrelevant features. Correct any inconsistencies within the data, such as misaligned columns or incorrect entries.

(Deliverable: Clean dataset ready for analysis)


- Day 3: Exploratory Data Analysis (EDA)

Descriptive Statistics: Use descriptive statistics to understand distributions, outliers, and key statistics.
Visual Analysis: Create visualizations (histograms, scatter plots, box plots) to identify patterns, trends, and correlations among features.

(Deliverable: EDA report with significant findings and potential features of interest)


- Day 4: Feature Engineering and Selection

Feature Engineering: Create new features from the existing dataset if needed, such as aggregated metrics or normalized features.
Feature Selection: Use correlation matrices or machine learning techniques to select the most impactful features for modeling.

(Deliverable: Refined feature set for modeling)

- Day 5: Preprocessing and Normalization 

Normalization: Normalize/standardize features to prepare them for training.
Encoding: Convert categorical data into dummy variables if necessary.

(Deliverable: Preprocessed data ready for models)

- Day 6: Model Selection and Training (Deliverable: Set of trained models with initial performance metrics)

Baseline Model: Start with a baseline model (e.g., Linear Regression or Decision Tree) to understand performance.
Advanced Models: Train multiple models, such as Random Forest, XGBoost, or Neural Networks for better accuracy.

(Deliverable: Set of trained models with initial performance metrics)

- Day 7: Model Evaluation and Tuning 

Model Evaluation: Use cross-validation to evaluate model robustness.
Tuning and Enhancement: Tune hyperparameters for best-performing models and perform oversampling if necessary to address imbalanced datasets.

(Deliverable: Finalized model with evaluation metrics (accuracy, precision, recall, F1)

- Day 8: Visualization and Presentation 

Result Visualization: Plot prediction results and key metrics.
Insight Reporting: Summarize insights, predicted trends, and actionable recommendations generated from the model.
Documentation: Compile comprehensive project documentation covering objectives, methods, analysis, results, and conclusions.

(Deliverable: Final report and presentation of model insights and findings)

