# Predicting-30-Day-Readmission-Risk-in-COPD-Patients-
Predicting 30-Day Readmission Risk in COPD Patients 
Chronic Obstructive Pulmonary Disease (COPD) places a significant clinical and financial
strain on healthcare systems and is a major cause of readmissions to hospitals. Precise
estimation of 30-day readmission risk can optimise resource allocation, enable proactive
treatments, and enhance patient outcomes. This study uses a carefully selected subset of the
UCI Diabetes 130-US Hospitals dataset,ewhich includes over 100,000 patient contacts, to
predict 30-day hospital readmissions among patients with COPD using sophisticated
interpretable machine learning algorithms. The data underwent preprocessing, which included
handling missing values, categorical encoding, and scaling continuous variables, to isolate
pertinent COPD cases and guarantee feature quality. Logistic Regression,eRandom Forest,
XGBoost, MLPClassifier, and Balanced Bagging were among the machine learning algorithms
that were trained, fine-tuned by cross-validation, and assessed using statistical measures
including ROC-AUC, F1-score, accuracy, and calibration curves. With a mean F1-score of
0.827 (±0.005) and a mean ROC-AUC of 0.868 (±0.003), the ensemble model showed the best
predictive performance. To ascertain feature relevance, interpretable machine learning
techniques sucheas Accumulated Local Effects (ALE) and SHapley Additive exPlanations
(SHAP) were employed to the ensemble model. The findings show that the most significant
predictors of 30-day readmission are patient age, duration of stay, number of drugs, discharge
disposition, and number of previous inpatient hospitalisations. Notably, readmission risk is
consistently increased by higher values for age, drugs, and prior admissions, whereas risk is
decreased by discharge to home and shorter hospital stays. The results assist focused post-
discharge care planning, efficient resource allocation, and policy formulation aimed at lowering
preventable readmissions by offering hospital managers and physicians practical information.
By connecting clinical decision-making with data-driven operationalestrategies, this study
shows the value of integrating interpretable techniques with predictive machine learning,
advancing healthcare management theory andepractice.
