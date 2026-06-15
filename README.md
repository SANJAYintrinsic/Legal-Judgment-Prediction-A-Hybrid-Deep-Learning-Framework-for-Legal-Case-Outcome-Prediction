# Legal-Judgment-Prediction-A-Hybrid-Deep-Learning-Framework-for-Legal-Case-Outcome-Prediction

[+] Developed a Hybrid Deep Learning Framework for Legal Judgment Prediction to predict whether a legal appeal will be accepted or rejected.
[+] Integrated Role-Weighted InLegalBERT and Entity-Aware BiLSTM with Role-Biased Attention to capture both legal semantics and document structure.
*Utilized rhetorical role information (Facts, Arguments, Statutes, Precedents, Judicial Reasoning, and Final Decision) to improve legal document understanding.
Implemented Monte Carlo Dropout for prediction uncertainty estimation and confidence scoring.
Evaluated models using both Temporal (Random 80:20) and Chronological data splits to measure real-world generalization.
Used Logistic Regression and Support Vector Machines (SVM) as baseline models for comparison.
Explored Latent Discourse Trajectory Modeling to capture the progression of legal reasoning across judgments.
Investigated Semantic-Structural Learning using discourse states, transition patterns, and structural document representations.
Performed ablation studies to analyze the contribution of semantic and structural features.
Applied McNemar's Statistical Significance Test to validate performance improvements.
Achieved best performance using the Entity-Aware BiLSTM framework, obtaining 75.0% Accuracy and 73.6% Macro-F1 Score on the temporal split.
Demonstrated that combining legal semantics, discourse structure, and entity-aware representations improves legal judgment prediction performance.

## Technologies Used
- Python
- PyTorch
- Transformers (Hugging Face)
- InLegalBERT
- Sentence-BERT (all-mpnet-base-v2)
- BiLSTM / BiGRU
- Scikit-learn
- NumPy & Pandas
- Matplotlib & Seaborn
- MiniBatch K-Means Clustering
- CNN-based Structural Modeling
