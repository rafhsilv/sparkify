# Sparkify 

This is a capstone Spark project for Udacity Data Science Nanodegree whose goal is to predict churn for the fictional music streaming service called Sparkify which emulates a real streaming service like Spotify.

## Motivation

Sparkify offers its users the ability to stream music through two types of subscription plans: a free plan that includes advertisements, and a paid plan that is ad-free. Users can interact with the service in various ways, such as giving songs a thumbs up or down, adding songs to playlists, or adding friends. They also have the flexibility to modify their subscription plan, either by upgrading from free to paid, downgrading from paid to free, or completely discontinuing the service by cancelling their subscription. We categorize users who downgrade or cancel their subscription as 'churned users'. In this project, we focus on two specific types of churn: users who cancel their subscription and users who downgrade their subscription.

The primary objective of this project is to develop a machine learning model capable of accurately identifying churned users.

## Libraries Used

This project uses the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- pyspark

## Results 
The winning model for churn prediction is a optimized logistic regression model that achieves an Accuracy of 0.88 and a F1 score of 0.87 on the test set.
Remember that we are using a small sample data, the results can be different if we user the full dataset.
Please visit this [article](https://medium.com/@rafhslv/spark-and-churn-prediction-a-case-study-on-sparkify-61fbbf53461) for more details.

## Files in the repository

- `data/`: Directory containing the data files.
  - `mini_sparkify_event_data.json`:  small subset of the user data on Sparkify's Log 

- `README.md`: Documentation for the project.
- `requirements.txt`: List of Python packages required for this project.
- `sparkify.ipynb`: File containing all the analysis.

## Installation

To install the necessary libraries, run the following command:

```pip install -r requirements.txt

To clone the repository, use the following command:

`git clone https://github.com/rafhsilv/sparkify.git`


## Acknowledgements

Thanks to Udacity for providing this project.