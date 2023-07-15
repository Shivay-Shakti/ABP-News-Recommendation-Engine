# News Recommendation Engine for ABP Network

This repository contains the implementation of a machine learning-based news recommendation system for ABP News. The system uses Collaborative Filtering, a popular technique in artificial intelligence, to suggest news articles to users based on their previous interactions.

## Structure of the Repository

The repository is structured as follows:

1. **Data Collection**: In this phase, data is gathered from the ABP News website. This includes user interaction data as well as the content of the news articles themselves.

2. **Data Preprocessing**: In this phase, the data is cleaned and formatted for use in the model. This involves handling missing data, removing outliers, and transforming the data into a format suitable for the model.

3. **Model Training**: In this phase, a model is trained on the preprocessed data. A collaborative filtering approach is used, which takes into account both the user's history and the similarities between different news articles.

4. **Evaluation**: In this phase, the trained model is evaluated on a test set to determine its effectiveness.

5. **Implementation**: In this phase, the trained model is deployed to make actual recommendations.

## Dependencies 

This project relies on the following libraries:

- Pandas
- NumPy
- Scikit-Surprise
- Seaborn
- Matplotlib

## How to Use

1. Clone the repository.
2. Install the necessary dependencies.
3. Run the Jupyter notebook.

For more detailed instructions and to understand the code, please go through the Jupyter notebook.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- ABP News for the data
