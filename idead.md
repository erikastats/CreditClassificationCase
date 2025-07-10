Ideas to improve the analysis

1. Feature Engineering
Combine features to identify strong correlations
 * saldo_rotativo_total / limite_rotativo_total
 * valor_total_emprestimos / patrimonio_total
 * qtd_consultas_ultimos_6m * qtd_linhas_credito_abertas

Outlier anaylises
Transformation
category grouping

Study techniques as:
 * Polynomial features
 * Interaction terms
 * Target encoding

2. Make the exploratory analysis based on the target feature
 * you can make a segmented exploratory analysis  by target
 * Supervized clusterization (use decision trees)
 * Clustering + target distribution in each cluster
 * Cluster classification

3. Use another type of clusterization
 - kproptypes
 - kmodes

4. Change the metrics
  * Log_loss

5. Understand the hyperparameters optimization
     * Boosting models has a limited gain point
     * Use RandomizedSearchCV with small n_iter

6. Learn more about the models
This allows you to make better choices
 * Why AdaBoost is outlier sensitive
 * When Gradient Boost has overfit
 * Why Logistic Regression it's a great baseline