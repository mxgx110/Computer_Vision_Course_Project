# Computer_Vision_Course_Project
Modeling Temporal Dynamics and Spatial Configurations of Actions Using Deep Learning(LSTM, Attention)

## Abstract:

Recently, skeleton-based action recognition gained more
popularity due to cost-effective depth sensors coupled with
real-time skeleton estimation algorithms. Due to the improved accuracy of depth detection sensors and cameras, it
is possible to detect three-dimensional coordinates of body
joints at high frame rates. These coordinates are input into
the activity detection system. Using deep neural networks to
solve machine learning problems has become very common
with the advent of powerful hardware today. By utilizing
the attention mechanism, a method that has significantly improved natural language processing in the past two years,
we designed a structure to prevent unnecessary and junk
data from entering both temporally and spatially. By dividing the body into five parts and recombining them together,
this organizational structure shifts the focus of the model to
the part of the body that performs the majority of the activity. In this research, I develop a model and examine its performance on the NTU RGB+D dataset. The original version
of this dataset categorizes different human activities into 60
classes, each containing approximately 9000 data samples.
However, this research considers 20 labels of the original
dataset, each containing 200 data samples. This model pro-
vides an accuracy of 91.6% and 80.5%, respectively, for the
train and test sets. Once the model was trained, this research attempts to bring the model into the federated learning space to take advantage of multiple clients whose data
are privately considered to train the model.

