# Pipeline Project

This project involves building a machine learning pipeline to predict whether a customer recommends a product based on their review. The dataset includes numerical, categorical, and text features, and the target variable is binary (`Recommended IND`).

## Getting Started

Follow the instructions below to set up the project and run the pipeline.


### Dependencies

Ensure you have the following installed:
* Python 3.x
* [scikit-learn](https://scikit-learn.org/stable/)
* [pandas](https://pandas.pydata.org/)
* [spaCy](https://spacy.io/)
* [Jupyter Notebook](https://jupyter.org/)

### Installation

1. Clone the repository:

```
git clone https://github.com/hupe1980/dsnd-pipelines-project.git
cd dsnd-pipelines-project
```

2. Install the required Python packages:

```
pip install -r requirements.txt
```

3. Download the SpaCy language model:

```
python -m spacy download en_core_web_sm
```

## Testing

To test the pipeline:

1. Run the cells in the notebook that evaluate the model's performance.
2. Use the provided test set to check accuracy and other metrics.

### Break Down Tests

- **Data Splitting**: Ensures the data is split into training and testing sets.
- **Pipeline Training**: Verifies that the pipeline processes data correctly and trains the model.
- **Model Evaluation**: Tests the model's accuracy and other metrics on the test set.

## Project Instructions

Deliverables for this project include:
- A complete machine learning pipeline that handles numerical, categorical, and text data.
- Properly trained and evaluated model with hyperparameter tuning.
- Documentation of the process and results.

## Built With

* [scikit-learn](https://scikit-learn.org/) - Machine learning library
* [pandas](https://pandas.pydata.org/) - Data manipulation and analysis
* [SpaCy](https://spacy.io/) - Natural language processing
* [numpy](https://numpy.org/) - Numerical computations

## License

[License](LICENSE.txt)
