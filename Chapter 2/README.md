## End-to-End Machine Learning Project


###<ins> Steps </ins>

>1. Look at the big picture
>2. Get the data 
>3. Explore and visualize the data  to gain insight
>4. Preaper the data for machine learning algorithm
>5. Select a model and train it
>6. Fine tune your model
>7. Present your solution
>8. Launch, monitor and maintain your system
    

__In this project i'm using California Housing Prices dataset from [Kaggle](https://www.kaggle.com/datasets/harrywang/housing)__

### <ins> Look at the big picture</ins>

 There are details like __house no__, __population__, __median house  price__ model should learn from this data and should be able to predict __housing price__ from any __area__

- Thsi is a typical __supervised learning__ problem task as the mmodel can be trained with labeled example 
- It's a __multiple regression problem__ as the model will use multiple features to make prediction
- This is also a __univariate regression problem__ as it's predicting a single value from the a district 

- The data is small to fit in memory so __Batch learning__ should be fine

#### <ins> Select Performance Measure</ins>

SPM for a regression problem is  __root mean square matrix(RMSE)__, this gives an overview of how much  error the system do in predictionm with a higher weight given to the larger errors.

$$
\mathrm{RMSE}(\mathbf{X}, h) = \sqrt{\frac{1}{m} \sum_{i=1}^{m} \left( h\left(\mathbf{x}^{(i)}\right) - y^{(i)} \right)^2}
$$
