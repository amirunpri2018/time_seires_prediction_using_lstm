**trainingset_selection.py** is used to format input data to training data set. It will return files of those enterprises satisfying the screening rule.

**neural_network_run.py** is used to train neural network for time series prediction. (There are two options in the script: dense for fully-connected artificial neural network and lstm for LSTM network.) It retruns trained model and model weight files, together with statistics result for predicted values and real values.

**preprocessing.py** provided some functions required in neural_network_run.py, training_set_selection.py and dataset_merging.py.

### optional script
**dataset_merging.py** is used to merge similar enterprises data set (or enterprises whose data is within similar range) based on Q-Q plot and ks-statistic. It will return merged cluster data set files and summary file to illustrate enterprises consists in each cluster.
