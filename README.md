# Heart-Disease-Risk-Predictor
This repository features an end-to-end data science and machine learning solution built to process clinical patient profiles, analyze lifestyle indicators, and predict cardiovascular risk using optimized classification ensembles.

The project pipeline begins with robust data engineering, transforming a structured database of 5,000 patient records across 16 critical diagnostic channels. These factors incorporate precise physiological metrics—such as age, systolic blood pressure, BMI, and LDL cholesterol levels—alongside qualitative behavioral indicators like smoking habits, dietary patterns, and chronic stress indices.

Advanced SQL analytics were leveraged to query and aggregate clinical historical trends. This exploratory phase isolated definitive medical risk thresholds, uncovering a striking 82% correlation rate between elevated lipid profiles (LDL > 200 mg/dL) and high-risk cardiovascular classifications.

For the predictive engine, an ensemble Random Forest Classifier was implemented and fine-tuned to map highly complex, non-linear feature interactions. By optimizing hyper-parameters to maximize sensitivity and minimize dangerous false-negative diagnostic classifications, the finalized model achieved a high-performance 91% ROC-AUC score.

The final stage of the project synthesizes these analytical and machine learning pipelines into a cohesive corporate intelligence asset. Utilizing Power BI, the project delivers an interactive executive dashboard featuring an algorithmic risk assessment matrix. This dashboard allows stakeholders and medical coordinators to dynamically filter population demographics, isolate vitals, cross-examine risk multipliers, and derive real-time, actionable patient health insights.

Core Stack: Python, SQL (SQLite), Scikit-Learn, Pandas, NumPy, Power BI.
