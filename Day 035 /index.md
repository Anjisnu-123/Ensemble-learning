# Ensemble learning

**Overview of ensemble learning :**
Introduction
usability of ensemble learning
  - Robustness
  - Bias reduction
  - variance reduction
  - Flexibility
  - feature importance
    
why ensemble learning has been adapted
  - Why ensemble leaning has been adapted
  - performance on benchmark
  - Development of libraries and tools
  - Addressing real world problems
  
problems solved by ensembles learning compared to classical algorithms
  - overfitting
  - Model performance variability
  - High dimensional data
  - imbalanced dataset
  - complex decision boundaries
  - Interpretability
Types of ensemble learning
  - Bagging
  - Boosting
  - Stacking
  - Voting
  - Blending
Bias and variance decomposition
  - introduction
  - bias ensembles learning
    - How to ensembles address bias
  - variance in ensemble learning
    - Variance in high-variance models
    - How ensembles addresses bias:
      - bagging
      - Example
  - Decomposition in ensembles
    - Ensemble technique in bias variance tradeoff
      - Bagging
      - Boosting
    - balancing both with ensembles
  - Summary
    - summary of ensemble benefits
    - different techniques for different scenario
    - Takeaway
---
# Model diversity and correlation

Introduction
  - model diversity
  - correlation
Importance of model diversity in ensemble learning
  - why diversity matters
  - example
Correlation in model prediction
Techniques for creating model diversity
Role of diversity in ensemble success
  - Reduced overfitting
  - improve generalization
  - Enhance stability
Examples and techniques promoting diversity
  
Basic ensemble concepts: wisdom of crowds in ML

Introduction, conditions, applications, techniques, advantages and limitations

Voting ensembles: hard voting, soft voting, when to use hard vs soft voting, practical applications, advantages and disadvantages

Parallel vs sequential ensemble (definition, mechanism, benefits and limitations), comparison and practical applications, conclusion 

bagging : definition, key ideas, advantages,applications, bootstrap sampling
Random forest: definition, key components, assumptions, mathematical formulation and explanation

## Random forsts
- Defination
- Key concepts
- Assumptions
  - Independence of trees
  - Sufficiently large data
- Mathematical formulation and explaination
  - Decision trees
    - Ginni impurity
    - ENtropy
  - Random forest construction
  - 
> [!IMPORTANT]
> for regressinon task  we take mean of all decision trees,
> for classification taks we take mode of all

- key features and concepts
  - Feature importance measures
  - out of bag error Estimation
  - proximity matrices
- How to use random forests
- When to use random forest
- Pros and cons
- use cses
- Intution
- Evaluation metrics
- Complexity
- real world challenges
- variants and extension
- Challenges and limitations

## Extra Trees

> [!IMPORTANT]
> Used when noisy data


- Defination
- Assumptions
  - Independence
  - Randomness
  - overfitting tolerance
- Mathematical formulation and explaination
  - tree construction
  - Prediction
- Key features and concepts
- How to use
- when to use
- pros and cons
- usecase
- intution
- Evaluation metricss
- Complexity
- Real world challenges
- Variants and extension
- challenges and limitations

## Meta Estimator with diff base larner

