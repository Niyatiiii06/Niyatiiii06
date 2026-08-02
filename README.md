�

�
￼
�
￼ 
�


�
￼ ￼ ￼



�
￼ ￼ ￼ ￼ 



�
￼ ￼ ￼
�

 About
class NiyatiSingh:
    def __init__(self):
        self.role      = "AI & Data Science Engineer"
        self.education = "B.Tech, AI & Data Science (2024–2028)"
        self.focus     = ["Machine Learning", "Deep Learning", "Computer Vision", "NLP"]
        self.stack     = ["Python", "TensorFlow/Keras", "Scikit-learn", "Streamlit"]
        self.mindset   = "Ship models that survive contact with real data."
I build end-to-end machine learning systems — from raw data and exploratory analysis through model training, evaluation, and live deployment. My work sits at the intersection of applied AI research and product engineering: I care as much about ROC-AUC and generalization as I do about the interface a user actually touches.
Machine Learning Engineering — supervised, unsupervised, and ensemble methods with rigorous evaluation (ROC-AUC, F1, precision/recall, threshold analysis) and imbalance handling via SMOTE.
Deep Learning & Computer Vision — ANN/CNN/RNN architectures in TensorFlow/Keras, pose estimation pipelines with MediaPipe and OpenCV, early stopping and validation monitoring against overfitting.
Natural Language Processing — TF-IDF vectorization, cosine similarity, semantic feature engineering, sentiment analysis, and text classification at 80K+ record scale.
Product Engineering Mindset — every model I train gets deployed. Three production Streamlit applications, live and publicly accessible, with session analytics and automated reporting.
Data Analysis & Storytelling — EDA, correlation analysis, statistical inference, and Power BI dashboards that turn model output into decisions.
�

Open To
�
￼ ￼ ￼ ￼
�

 Tech Stack
�

Languages
�
￼
Machine Learning & Deep Learning
�
￼
Data & Scientific Computing
�
￼ ￼ ￼ ￼ ￼ ￼ ￼
Deployment, Tooling & Analytics
�
￼ ￼ ￼ ￼ ￼ ￼
�

 AI / ML Expertise
�

Domain
Proficiency
Details
Supervised Learning
�
Classification & regression, Random Forest, KNN, Logistic Regression, ensemble learning
Deep Learning
�
ANN, CNN, RNN in TensorFlow/Keras — early stopping, feature scaling, validation monitoring
Computer Vision
�
MediaPipe pose estimation, OpenCV video pipelines, joint-angle biomechanical analysis
Model Evaluation
�
ROC-AUC, F1, precision/recall, confusion matrix, threshold analysis, R², SMOTE
Natural Language Processing
�
TF-IDF vectorization, cosine similarity, sentiment analysis, text classification
Feature Engineering
�
Semantic descriptors, PCA-transformed features, imbalance correction, scaling strategies
Unsupervised Learning
�
Clustering, Nearest Neighbors similarity search, dimensionality reduction
Statistical Analysis
�
EDA, correlation analysis, distribution testing, statistics for AI
ML Deployment
�
Streamlit production apps, Pickle model serialization, automated PDF reporting
�

 Featured Projects
�
 FitVisionAI — AI Workout Form Analyzer
�


An end-to-end computer vision system that analyzes squat and push-up form from uploaded video, combining neural exercise-state classification with rule-based biomechanical scoring.


Stack
Python · TensorFlow/Keras · MediaPipe · OpenCV · Streamlit · ReportLab
Scale
Frame-by-frame pose-landmark extraction across full-length workout videos
Performance
Custom ANN classifiers trained on pose-landmark features with early stopping, feature scaling, and validation monitoring to reduce overfitting
Architecture
Hybrid pipeline — ANN exercise-state prediction fused with joint-angle threshold rules for repetition counting and posture scoring
Impact
Live workout metrics, session analytics, workout history, and automated PDF report generation
Repository
� �
The core engineering challenge was fusing two fundamentally different signals: a learned classifier that recognizes what the body is doing, and deterministic biomechanics that judge how well it is doing it. MediaPipe extracts normalized pose landmarks per frame; the ANN maps those landmarks to exercise states, while a rule layer computes joint angles to count repetitions and grade posture. The result is feedback that is both adaptive and explainable — a user sees not just a score, but the specific joint that failed the threshold, exported as a shareable PDF session report.
�

�
 Credit Card Fraud Detection
�


A production fraud-detection classifier built on severely imbalanced transaction data, with full threshold and cost-sensitivity analysis.


Stack
Python · Pandas · Scikit-learn · Streamlit
Scale
PCA-transformed V1–V28 transaction feature space
Performance
ROC-AUC 0.9568 — Random Forest outperforming the Logistic Regression baseline
Security
Anonymized PCA feature space; no raw cardholder data used in training or inference
Impact
Live web application returning real-time fraud probability with tunable decision thresholds
Repository
� �
Fraud detection is a precision/recall trade-off problem disguised as a classification problem. The dataset's extreme class imbalance was corrected with SMOTE oversampling on the training split only — preserving an untouched, realistically imbalanced validation set. Model comparison was deliberately evaluated on ROC-AUC and confusion-matrix behavior rather than raw accuracy, and threshold analysis exposes how the operating point shifts the balance between missed fraud and false alarms.
�

�
 Hybrid Music Recommendation System
�


A dual-signal recommender that blends audio-feature similarity with semantic NLP matching across an 81K+ track catalogue.


Stack
Python · Pandas · Scikit-learn · NLP (TF-IDF) · Streamlit
Scale
81,000+ tracks indexed for real-time retrieval
Performance
Weighted hybrid ranking — 70% Nearest Neighbors audio similarity, 30% TF-IDF cosine semantic match
Architecture
Semantic feature engineering converting numeric audio features into human-readable descriptors (mood, energy, danceability)
Impact
Production-ready interactive app for real-time music discovery with measurably improved recommendation relevance
Repository
� �
Pure audio-similarity recommenders return technically adjacent but contextually irrelevant tracks. The fix was a second, semantic channel: numeric audio features were translated into natural-language descriptors, vectorized with TF-IDF, and compared by cosine similarity — then blended with the Nearest Neighbors audio signal at a 70/30 weighting. The hybrid preserves acoustic coherence while restoring the mood and intent that a listener actually searches with.
�

 Experience
Independent Machine Learning Engineer  ·  Self-Directed Projects
June 2026 — Present  ·  New Delhi, India
Designing, training, and deploying production machine learning systems end to end — owning the full lifecycle from dataset acquisition and exploratory analysis through model selection, evaluation, and public deployment.
Built and shipped three live ML applications spanning computer vision, imbalanced-data classification, and hybrid recommendation.
Established a repeatable evaluation discipline — ROC-AUC, confusion matrices, and threshold analysis over headline accuracy.
Engineered deep learning pipelines in TensorFlow/Keras with early stopping, feature scaling, and validation monitoring to control overfitting.
Deployed and maintained public Streamlit applications with session analytics and automated PDF reporting.
    
�


B.Tech, AI & Data Science  ·  Dr. Akhilesh Das Gupta Institute of Professional Studies
August 2024 — August 2028  ·  New Delhi, India
Undergraduate coursework and applied research spanning the full modern AI curriculum, with a consistent emphasis on translating theory into deployed systems.
Core coursework: Machine Learning, Python for Data Science, Data Analysis, Natural Language Processing, Statistics for AI.
Applied statistical inference and hypothesis testing to real datasets as the foundation for model validation.
Extended classroom concepts into independently scoped, publicly deployed project work.
   
�


Student Council Member  ·  St. Mary's School, Dwarka
March 2012 — March 2024  ·  New Delhi, India
Elected to the 2024 Student Council, leading event operations and cross-school coordination.
Organized and ran the Interschool Model United Nations competition end to end.
Coordinated logistics, scheduling, and delegate management across multiple participating institutions.
  
 Achievements
�

Recognition
Details
ROC-AUC 0.9568 — Fraud Detection
Random Forest classifier outperforming the Logistic Regression baseline on a severely imbalanced transaction dataset
81K+ Track Recommendation Engine
Hybrid audio + semantic NLP system delivering real-time recommendations at catalogue scale
3 Production ML Deployments
Every trained model shipped as a publicly accessible, live Streamlit application
End-to-End CV Pipeline
Full pose-estimation workout analyzer built solo — data, model, biomechanics, UI, and PDF reporting
2024 Student Council
Elected member, St. Mary's School, Dwarka
Interschool MUN Organizer
Led planning and execution of a multi-school Model United Nations competition
�

 Certifications
�

Udemy
�
￼ 



Academic Coursework — Dr. Akhilesh Das Gupta Institute
�
￼ ￼ ￼ ￼ ￼
�


Languages
�
￼ ￼
�

 Coding Profiles
�

�
￼ ￼ 



�
￼ ￼ 
�

 GitHub Analytics
�

�
￼ ￼



�
￼
�

 GitHub Trophies
�

�
￼
�

 Contribution Activity
�

�
￼
�

 Contribution Snake
�

�
￼ 
�

 Current Focus
learning:
  - Advanced Deep Learning Architectures (CNN, RNN, Transformers)
  - MLOps: model versioning, monitoring, and reproducible pipelines
  - Advanced NLP: embeddings, transformer-based semantic search
  - Cloud deployment for machine learning workloads

building:
  - Production-grade computer vision systems with real-time inference
  - Hybrid recommendation engines at 100K+ record scale
  - Explainable ML pipelines with rigorous evaluation discipline

exploring:
  - Generative AI and large language model applications
  - Model interpretability and fairness in high-stakes classification
  - Edge deployment of lightweight vision models

open_to:
  - Machine Learning / Data Science internships
  - AI research collaborations
  - Open source contributions in the Python ML ecosystem
  - Technical mentorship and peer code review
 Connect
�

�
￼ ￼ 
�


�
￼ ￼ 
�

�

"A model that never ships is just an expensive opinion."
�
￼
�