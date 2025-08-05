# <ins>The Machine Learning Landscape</ins>

## What is Machine Learning?

-> A program that can learn from data.

## Why use Machine Learning?

-> To automate boaring jobs, repeatable boring jobs or automate any job that can be controlled by computers. Predict results.

- Problem for which slolution already exists and need a lot of fine tuning ML simplify code and perform better than brute force
- Complex problem for which the brute force doesn't give good solution ML finds solution in that case
- ML system alyays stay updated with new data
- Getting insights about Complex problem and large data

## Application




## Type of ML syatem

- Based on how they were supervised during training(## Training Supervision)
    - 1. Supervised Learnign
    - 2. Unsupervised Learning
    - 3. Semi-Supervised Learning
    - 4. Self-Supervised Learning
    - 5. Reinforcement Learning <ins>(Sometimes not considered in Supervised)</ins>

- If they can learn incrementally 
    - 1. Online Learning 
    - 2. Batch Learning

- Weather comparing new data points to training data or finding patterns in training data and building models 
    - 1. Instance baesed Learning 
    - 2. Model based Learning

$$
We can combine them to create suitable algo of our need
$$

## Training Supervision

- 1. <ins>Supervised</ins>

        Feed the training set to the algo with desired outcomes, called labels. (Largely used in the prediction of target numerical values, this task is called regression)

- 2. <ins>Unsupervised</ins>

        The training data is unlabeled 

        __For Example__, Let us apply clustering algorithm which group different type of data, IN this case when a new data is added we don't specify which group does this data belongs but it does find the connection between the data and the grup this data belongs without any supervision.

- 3. <ins>Semi-Supervised</ins>

        Some algorithm deal with datasets with some labeled and some unlabeled instances

        __For Example__, In google photos label each person with their name (__this part is sepervised__ )and when you add new photo in galary the photo will be recognized and will be added to that person's group (__this part is unsupervised__).

- 4. <ins>Self_Supervised</ins>

        This Learning involves converting fully labeled dataset from fully unlabeled dataset. There after we can apply any supervised algo on that dataset.

        __For Example__, 