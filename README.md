# Hi, I'm Jonathan 👋

### 🎓 M.S. Applied Data Science Candidate @ USC Viterbi
### 🔍 Open to full-time roles in Data Science, ML Engineering, and Data Engineering

---

## 👨‍💻 About Me

I'm a Master's student at the **University of Southern California** specializing in **distributed data mining, machine learning, and applied AI**. I came to data science from a mathematics background — B.A. in Mathematics (Cum Laude) from University of North Texas — and previously taught secondary math, where I led a 5-teacher team and used data-informed strategies to improve student outcomes. That math foundation now drives how I approach ML: from first principles, with an emphasis on understanding what's actually happening under the hood.

My coursework spans the full ML stack — from classical statistical methods and deep learning to large-scale distributed algorithms on Apache Spark — and my projects emphasize building algorithms **from scratch** rather than just calling library functions. I'm particularly interested in problems where **scale, accuracy, and interpretability intersect**: recommendation systems, predictive maintenance, computer vision, and graph analytics. I enjoy the engineering side of ML as much as the modeling side — writing performant Spark code, designing feature pipelines that prevent target leakage, and tuning models under realistic runtime and memory constraints.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat&logo=scala&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)

**Machine Learning & Deep Learning**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6F00?style=flat&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)

**Big Data & Distributed Computing**
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

**Cloud & Visualization**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

**Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 🎯 Focus Areas

- **Distributed Data Mining** — Implementing classical algorithms (SON, LSH, Girvan-Newman, BFR, Bloom Filters, Flajolet-Martin, Reservoir Sampling) from scratch on Spark RDDs
- **Recommender Systems** — Hybrid models combining collaborative filtering with gradient-boosted regression, adaptive ensemble blending, feature engineering at scale
- **Computer Vision** — Deep transfer learning, CNN architecture benchmarking, image augmentation and regularization techniques
- **Statistical Machine Learning** — Regression, classification, regularization, dimensionality reduction, and clustering with rigorous attention to cross-validation methodology and data leakage prevention
- **Production ML Engineering** — Optimizing under runtime budgets, handling class imbalance, designing leak-free CV pipelines

---

## 🏆 Featured Projects

### ⭐ [Yelp Hybrid Recommender System](https://github.com/jonathan-chen010/yelp-hybrid-recommender)
> | Python, PySpark, XGBoost, Apache Spark, NumPy

Production-grade hybrid recommender combining item-based collaborative filtering with a 78-feature XGBoost regressor, blended adaptively by neighborhood density. **Achieved RMSE 0.9788** (beating the 0.9800 baseline) within a 355-second runtime budget on Apache Spark RDDs.

### ⭐ [Waste Classification with Transfer Learning](https://github.com/jonathan-chen010/waste-classification-transfer-learning)
> | Python, TensorFlow, Keras, OpenCV, NumPy

Multi-class image classification of 9 waste categories via deep transfer learning. Benchmarks four pre-trained ImageNet backbones (ResNet50, ResNet101, EfficientNetB0, VGG16) with frozen feature extractors, image augmentation, batch normalization, dropout, and early stopping.

### [Predictive Maintenance — Scania APS Failure](https://github.com/jonathan-chen010/aps-failure-predictive-maintenance)
> | Python, scikit-learn, XGBoost, imbalanced-learn

Failure prediction on 60K heavy truck sensor records with severe class imbalance (~1.7% positive). Compares Random Forests with class-weighting against L1-penalized gradient-boosted model trees, applying SMOTE inside CV folds to prevent data leakage.

### [BFR Clustering for Memory-Constrained Datasets](https://github.com/jonathan-chen010/bfr-clustering)
> | Python, NumPy, scikit-learn

Bradley-Fayyad-Reina algorithm implemented from scratch for constant-memory clustering of datasets exceeding RAM. Uses Mahalanobis distance and statistical cluster summaries (N, SUM, SUMSQ) to process data in chunks while maintaining >98% accuracy.

### [Streaming Algorithms — Bloom, Flajolet-Martin, Reservoir](https://github.com/jonathan-chen010/streaming-algorithms)
> | Python, Scala, Spark, hashlib

Three classical streaming algorithms implemented from scratch in **both Python and Scala** for approximate query processing under memory constraints — set membership, cardinality estimation with median-of-means aggregation, and fixed-memory uniform sampling.

---

## 📚 Currently Learning

- **MLOps & ML Infrastructure** — Model deployment patterns, monitoring, and lifecycle management
- **Cloud Platforms** — AWS / GCP for distributed ML workloads at production scale
- **Modern Recommender Systems** — Two-tower models, sequential recommenders, and retrieval-and-ranking architectures
- **Graph Neural Networks** — Extending classical graph algorithms into learned representations

---

## 📫 Get in Touch

I'm **open to full-time roles** in Data Science, ML Engineering, and Data Engineering.

- 📧 **Email:** [jonathan.chen010@gmail.com](mailto:jonathan.chen010@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/jonathan-d-chen](https://www.linkedin.com/in/jonathan-d-chen)
- 📍 **Based in:** Los Angeles, CA — open to relocation

Feel free to reach out if you'd like to discuss a role, collaborate on a project, or just talk about distributed systems and ML.

---

<p align="center"><i>Thanks for stopping by — take a look at my pinned repos below for a deeper dive into my work.</i></p>
