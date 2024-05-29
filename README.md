# Creating-a-Model-for-Rusty-Bargain-Car-Company

Project Description:

Rusty Bargain is a used car trading company that is developing an application to attract new buyers. In this application, you can quickly determine the market value of your car. You have access to historical data, technical specifications of vehicles, vehicle model versions, and vehicle prices. Your task is to create a model that can determine the market value of cars.

Rusty Bargain is interested in:

prediction quality;
model speed in prediction;
time taken to train the model
Goal
Create a model that can determine the market value of cars.

Project Instructions:

Save and observe the data.
Train different models with various hyperparameters (You should create at least two different models, but more is better. Remember, various implementations of gradient boosting are not counted as different models). The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.
Analyze the speed and quality of the model.
Note:

Use RMSE metric to evaluate the models.

Linear regression is indeed not very suitable for setting hyperparameters, but linear regression is the right model to perform sanity checks compared to other methods. If the performance of gradient boosting is not better than linear regression, then something is wrong.

Independently, learn the LightGBM library and use the tools provided in the library to create a gradient boosting model.

Ideally, your task should include linear regression for sanity check, tree-based algorithms with hyperparameter tuning (preferably random forest), LightGBM with hyperparameter tuning (try several sets), as well as CatBoost and XGBoost with hyperparameter tuning (optional).

Pay attention to encoding categorical features for simple algorithms. LightGBM and CatBoost do implement it, but XGBoost requires OHE.

You can use a specific command to determine the processing time of a code cell in Jupyter Notebook. Find that specific command.

Considering that training a gradient boosting model can take a long time, change only a few model parameters.

If Jupyter Notebook stops working, delete unnecessary variables using the del operator:

del features_train"
