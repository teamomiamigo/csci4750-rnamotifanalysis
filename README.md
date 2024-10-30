# csci4750-rnamotifanalysis
Final Project for CSCI 4750 - Project 3: Build End-to-End Machine Learning for RNA Motif Analysis Using Classification and Clustering

```mermaid
graph TD;
    A[Data Preprocessing] --> B[Data Merging];
    B --> C[Label Encoding];
    C --> D[Feature Selection];
    D --> E[Handling Missing Data];
    A --> F[Exploratory Data Analysis];
    F --> G[Statistical Summaries];
    F --> H[Data Visualization];
    F --> I[Multicollinearity Analysis];
    A --> J[Feature Engineering];
    J --> K[Dimensionality Reduction];
    J --> L[Normalization/Scaling];
    A --> M[Model Training and Selection];
    M --> N[Classification];
    M --> O[Clustering];
    N --> P[Traditional ML Model];
    N --> Q[Deep Learning Model];
    O --> R[Hierarchical Clustering];
    O --> S[DBSCAN];
    A --> T[Model Evaluation and Tuning];
    T --> U[Cross-Validation];
    T --> V[Evaluation Metrics];
    T --> W[Hyperparameter Tuning];
    A --> X[Visualization and Interpretation];
    X --> Y[Dimensionality Reduction for Visualization];
    X --> Z[Cluster Visualization];
    X --> AA[Result Interpretation];
    A --> AB[Report Generation];
    AB --> AC[Results Summary];
    AB --> AD[Comparison Analysis];