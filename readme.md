Detailed description about LSTM and RNN in prediction of time series can be seen in the author's blog:http://www.cnblogs.com/arkenstone/p/5794063.html#3750733

**trainingset_selection.py** is used to format input data to training data set. It will return files of those enterprises satisfying the screening rule.

**neural_network_run.py** is used to train neural network for time series prediction. It returns a lstm model and evaluation results of the model.

**preprocessing.py** provided some functions required in neural_network_run.py, training_set_selection.py and dataset_merging.py.

### optional script
**dataset_merging.py** is used to merge similar enterprises data set (or enterprises whose data is within similar range) based on Q-Q plot and ks-statistic. It will return merged cluster data set files and summary file to illustrate enterprises in each cluster.
