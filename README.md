# Second hand data analysis

### Main Purpose:
Predicting the impairment and the year of your vehicle.

### Data Acquisition:
* Gathering information using beautiful-soup & selenium
* We made the withdrawal from the KOMO website.
  - We took the information on vehicles by manufacturer.
  - The information we drew is about second-hand vehicles.

### Data Cleaning
* We cleaned each manufacturer individually.
* We merged all the data frames.
* On the merged data frame we removed:
  - missing values.
  - signs (' ₪ ' , ' , ').
  - outliers.
* At the end we changed all the values to numeric.

### EDA
* We presented how is the price of the vehicle is affected.
* We presented the quantities of vehicles according to the characteristics.
* We presented the average of the features by manufacturer.
* We presented the average hand of used vehicles.


### Machine Learning
* We built a linear regression model.
* We made changes to the model, to improve its prediction.
* We presented a visualization of the model prediction versus reality.
* We have built a method that returns for the user the expected depreciation of his vehicle.
