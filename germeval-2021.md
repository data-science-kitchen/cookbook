# What we have learned from the GermEval 2021 shared task

- To get the most gain with task specific features infer as much as possible about the manual label strategy from the invitation paper and read around 100 comments of each label type and develop own theories about what could be useful features. Then test them. 
- Don’t do data splitting by hand but work directly with scikit cross validation library and a random_state.
- Do object oriented programming for a modular pipeline architecture (Features and models as objects)
- Gather and load run-parameters with a logger file for fast trails and easy documentation
- Strive for the simplest solution with minimal number of features and minimal ML model complexity (Naive Bias, logistic regression, SVM, Transformer... DNN...). Validate each addition. Is it yielding in an enhancement for the final score.
