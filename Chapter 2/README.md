## End-to-End Machine Learning Project


### Steps 
- Look at the big picture
- Get the data 
- Explore and visualize the data  to gain insight
- Preaper the data for machine learning algorithm
- Select a model and train it
- Fine tune your model
- Present your solution
- Launch, monitor and maintain your system
    
#^ two spaces

In this project i'm using California Housing Prices dataset from [Kaggle](https://www.kaggle.com/datasets/harrywang/housing)

### Look at the big picture 
 There are details like __house no__, __population__, __median house  price__ model should learn from this data and should be able to predict __housing price__ from any __area__

// Thsi is a typical __supervised learning__ problem task as the mmodel can be trained with labeled example 
// It's a __multiple regression problem__ as the model will use multiple features to make prediction
// This is also a __univariate regression problem__ as it's predicting a single value from the a district 

// The data is small to fit in memory so __Batch learning__ should be fine

#### Select Performance Measure

SPM for a regression problem is  __root mean square matrix(RMSE)__, this gives an overview of how much  error the system do in predictionm with a higher weight given to the larger errors.

\mathrm{RMSE}(\mathbf{X}, h) = \sqrt{\frac{1}{m} \sum_{i=1}^{m} \left( h\left(\mathbf{x}^{(i)}\right) - y^{(i)} \right)^2}

