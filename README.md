# PotatoDiseaseClassification
Most often there are many virus affecting plants.One such disease we are going to classify for Potato plants

In this project we collect 3 types of Potato Leaf images and classify into either Early_Blight,Healthy or Late Blight

Libraries used:

Matplotlib,seaborn,numpy,Tensorflow

These images are passed to tensorflow dataset for quick optimization and then preprocessing is applied to the images before passing to the Deep Neural Networks.

Sparse Categorical Entropy is used as Loss function and Optimizer is adam , activation function is relu. 

Below are the results:

loss: 0.0433 - accuracy: 0.9844 - val_loss: 0.0333 - val_accuracy: 0.9883

This DNN gives us 100% confidence.

Predictions on Sample images are shown below:
