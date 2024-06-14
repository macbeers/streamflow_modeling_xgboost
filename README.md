# streamflow_modeling_xgboost
Streamflow Modeling Using XGBoost


## Step 0:
Preprocess ET data. Convert rasterized data into spatial averages per time step. 

## Step 1: 
Pull and clean precipitation, temperature, streamflow data.

## Step 2: 
Run xgboost to model streamflow.

## Step 3:
NOT COMPLETE - create an ensemble of inputs for the model (snow, snow melt, temperature, etc.) to create a forecast for March 1st, April 1st, May 1st, June 1st. The ensemble of inputs should use the data at the date of the forecast as a guide to ge more accurate inputs. (i.e., you do not have more snow melt than there is snow). 

## Step 4:
NOT COMPLETE - run xgboost model using ensemble of inputs. 
