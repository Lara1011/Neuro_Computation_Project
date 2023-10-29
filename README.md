# Neuro Computation Project
In this project, we implemented the Kohonen algorithm to fit a set of 100 neurons in two configurations: one-dimensional and two-dimensional. We used the Kohonen algorithm to train the neurons based on input data. Here is an overview of what we did:
## Part A

### 1. One-Dimensional SOM

In this section, we implemented the Kohonen algorithm using a one-dimensional array of 100 neurons. We started by creating a dataset with 1000 neurons as an example. Then, we trained the model using the Kohonen algorithm and plotted the results at various iterations. The code snippet for this part is as follows:
```python
data = create_data_a1(1000)
model = kohonen_1D(data, 100)
model.train()
```

### 2. Two-Dimensional SOM

This part of the project focuses on creating and training a two-dimensional Self-Organizing Map (SOM). The code above demonstrates how to use the create_data_a2 function to generate sample data with 1000 data points and then create a two-dimensional SOM model with 100 neurons using the kohonen_2D class. After initializing the model, you can train it using the train() method.

```python
data_2D = create_data_a2(1000)
model_2D = kohonen_2D(data_2D, 100)
model_2D.train()
```

### 3. Neurons on a "Donut" Shape

This experiment explores the placement of neurons on a "donut" shape to represent data. It follows a similar pattern to the previous experiments but focuses on creating a SOM model where neurons are distributed in a circular manner. The create_data_a3 function generates data, and the kohonen_donut class helps in creating and training the SOM model.

```python
data_donut = create_data_a3(1000)
model_donut = kohonen_donut(data_donut, 100)
model_donut.train()
```













