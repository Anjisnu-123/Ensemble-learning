# Stacking

- What is stacking
- How stacking works
  - base model
  - meta model
- Step by step stacking process
  - train models
  - generate predictions for meta features
  - Train meta model
  - final prediction
- Purpose of stacking
- mathematical intution behind stacking
- When to use stacking
  - Example scenario
- flow of stacking : step by step
  - step 1 : split the data
  - step 2 : train base models on the training data
  - step 3 : Generate base model predictions
  - step 4 : Train the meta model using meta features
  - step 5 : Make predictions on new data using the stacking ensemble
- cross validation strategies in Stacking
- common cross validation strategies in stacking
  - k fold cross validation
  - Stratified k fold cross validation
  - LOOCV
  - summary of cross validation strategies in stacking
    
> [!NOTE]
> If imbalanced dataset the use stratified k fold for all .

- choosing right cross validation strategy for stacking
- Meta feature generation in stacking
- Types of stacking
  - Single layer stacking
    - How it works
    - examples
    - advantages
    - disadvantages
  - multi layer stacking
    - how it works
    - example
    - advantage
    - disadvantage
  - Feature weighted linear stacking
    - how it works
    - example
    - advantage
    - disadvantage
  - Dynamic ensemble selection
    - how it works
    - example
    - advantage
    - disadvantage

- Choosing right  stacking
  - For beginners or smaller datasets; start with single layer stacking due to simplicity
  - For complex tasks or high dimensional data : consider multi-layer stacking or feature weighted linear stackingfor more learning capacity
  - for highly variable or diverse datasets: use dynamic ensemble selection ito adaptively tailor the ensemble in individual samples.
- Choosing and combining base models in stacking
  - Types of models to use in stacking

- Why diversity in base model is important
  - Avoiding redundancy
  - capturing a variety of patterns
  - Enhance generalization
  - Reducing overfitting and underfitting
  - improving robustness
- Guidelines for choosing diverse models
  - model variety
  - Model complexity
  - model diversity in error patterns
  - Data and task consideration
- Meta model choice and optimization in stacking
- common choices for meta models
  - Linear regression
    - charatereictics
    - why choose linear regression
    - Mathematical formulation
  - Logistic regression
    - charatereictics
    - why choose logistic regression
    - Mathematical formulation
  - Neural networks
    - charatereictics
    - why choose Neural networks
    - Mathematical formulation
- Optimization of meta model
  - training the meta model
  - cross validation in meta model optimization
  - Hyperparameter tuning
    
- practical application of stacking
  - finance
  - Healthcare
  - e comerce
  - NLP
- specific scenario where stacking outperforms
  - when there is model doversity
  - in high dimensional data
  - when base models are complementary
  - improving predictions on imbalance datasets
  - in classification tasks
- pros and cons of stacking
- evaluation metrics for stacking
  - Appropiate matrix selection
- complexity analysis
- Real world challenges in stacking
  - data leakage : somehow accidentaly validation set data exposed to model, so when validating the data validating in known pattern, generalization not done for unseen data,it is Data leakage.
  - Model interactions
- variants and extension in stacking
- limitations and best practices in stacking

# Advance ensemble techniques
- why do we need ensemble techniques
- key advantage of advanced techniques over traditional ensembles
- when to use adv ensemble tachniques
  
# cascade generelization
- Defination
- mechanism
- Mathematical formulation
- key feature and concepts
- How to use,when to use
- pros and cons
- fraud detection in financial

# Rotation forest
- Defination
- mechanism
- Mathematical formulation
- key feature and concepts
- how to use
- when to use
- pros and cons

# Deep forest
- defination
- mechanism
- mathematical formulation
- key features and concepts
- How to use
- when to use
- pros and cons
- use cases
- evaluation metrics
- complexity
- real world challenges

# Hierarchical mixture of experts (HME)
- defination
- mechanism
- mathematical formulation
- key features and components
- how to use
- when to use
- pros and cons
- use case
- evaluation metrics
- complexity real world challenges
>[!NOTE]
>WHen there is major o of catagorical variable for multiclass classification
