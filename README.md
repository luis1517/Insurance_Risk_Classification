
# Client Classification Model

This learning model classifies clients by categories based on their characteristics. The model was trained using a dataset of client information and their corresponding categories, and it uses a classification algorithm to predict the category of a new client based on their characteristics.

## Getting Started
To get started with this model, you'll need to have the following software installed on your machine:

- Python 3.6 or higher
- Scikit-learn library
- Xgboost library
- Pandas library
- Numpy library
- Seaborn library

You can install these libraries using pip:

```bash
  pip install scikit-learn pandas numpy Xgboost seaborn
```
To train the model, you'll need to have a dataset of client information and their corresponding categories. The dataset should be in CSV format, with the client characteristics in the columns and the categories in a separate column.

Once you have the dataset, you can train the model using the train_model.py script. You'll need to specify the path to the dataset as a command-line argument:


## Using the Model

To use the trained model to classify a new client, you can use the predict_category.py script. You'll need to provide the client characteristics as a list of values:

## Results
After training the model, a recall value above 70% on higher risk class was obtained

## Contributing
If you'd like to contribute to this project, feel free to submit a pull request with your changes. You can also open an issue if you have any suggestions or bug reports.    
