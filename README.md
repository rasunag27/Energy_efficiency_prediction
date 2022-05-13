# Energy_efficiency_prediction


![alt text](https://github.com/rasunag27/Energy_efficiency_prediction/blob/main/energy_efficiency.jpeg?raw=true)

## Objective

To predict the heating load and cooling load of the building. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. 

## Dataset

The dataset contains eight attributes (or features, denoted by X1…X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses.

Specifically:

X1 Relative Compactness

X2 Surface Area

X3 Wall Area

X4 Roof Area

X5 Overall Height

X6 Orientation

X7 Glazing Area

X8 Glazing Area Distribution

y1 Heating Load

y2 Cooling Load


## Methodology

* The given problem statement is a regression problem and hence regression models are used for the prediction.
* Models such as Linear Regression, Ridge and Lasso regression, Decision Trees and RandomForest is implemented to predict the two target variables separately (Heating load and cooling load).
* Hyperparamter tuning for all the models is carried out by using GridSearchCV method.

## Metrics

* R2 score is used as metric for the model evaluation.
* RandomForest provided an R2 score of 0.99 for heating load and 0.97 for cooling load on the test dataset.
* Evalution table is presented that compares the metric for all the models.

## Future development

* Feature scaling can be done for the model to reduce the time complexity and unnecessary features.
