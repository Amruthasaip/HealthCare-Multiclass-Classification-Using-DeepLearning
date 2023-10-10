
# HealthCare-Multiclass-Classification-Using-DeepLearning

In this assignment, we will focus on healthcare. This data set is made available by MIT. It contains data about 9,026 heartbeat measurements. Each row represents a single measurement (captured on a timeline). There are a total of 80 data points (columns). This is a multiclass classification task: predict whether the measurement represents a normal heartbeat or other anomalies.
Description of Variables
You will use the hearbeat_cleaned.csv data set for this assignment. Each row represents a single measurement. Columns labeled as T1 from T80 are the time steps on the timeline (there are 80 time steps, each time step has only one measurement).

The last column is the target variable. It shows the label (category) of the measurement as follows:
0 = Normal
1 = Supraventricular premature beat
2 = Premature ventricular contraction
3 = Fusion of ventricular and normal beat
4 = Unclassifiable beat
## Goal

Use the data set **hearbeat_cleaned.csv** to predict the column called **Target**. The input variables are columns labeled as **T1 to T80**. 

## Results & Interpretation 

Tools: TensorFlow, Keras, LSTM with neuron layers.
Devised and engineered deep learning models in Keras/TensorFlow for healthcare multiclass classification, achieving up to 92% 
accuracy and contributing to data-driven insights in heart anomaly detection.
