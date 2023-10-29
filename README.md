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

We repeated the experiment, but this time using a two-dimensional array of 100 neurons. The same data set used in the one-dimensional example was used here. Here's an example of how to create and train the data:

```python
data_2D = create_data_a2(1000)
model_2D = kohonen_2D(data_2D, 100)
model_2D.train()
```
