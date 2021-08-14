# Data Science Primer

Machine Learning

Machine learning is not about algorithms. It's a comprehensive approach to solving problems.
What makes machine learning so special?

Machine learning is the practice of teaching computers how to learn patterns from data, often for making decisions or predictions.

For true machine learning, the computer must be able to learn patterns that it's not explicitly programmed to identify.
Machine Learning Tasks

    A task is a specific objective for your algorithms.
    Algorithms can be swapped in and out, as long as you pick the right task.
    In fact, you should always try multiple algorithms because you most likely won't know which one will perform best for your dataset.

The two most common categories of tasks are supervised learning and unsupervised learning.
Supervised Learning

    Supervised learning includes tasks for "labeled" data.
    In practice, it's often used as an advanced form of predictive modeling.
    Each observation must be labeled with a "correct answer."
    Only then can you build a predictive model because you must tell the algorithm what's "correct" while training it (hence, "supervising" it).
    Regression is the task for modeling continuous target variables.
    Classification is the task for modeling categorical (a.k.a. "class") target variables.

Supervised Learning
Unsupervised Learning

    Unsupervised learning includes tasks for "unlabeled" data.
    In practice, it's often used either as a form of automated data analysis or automated signal extraction.
    Unlabeled data has no predetermined "correct answer."
    We'll allow the algorithm to directly learn patterns from the data (without "supervision").
    Clustering is the most common unsupervised learning task, and it's for finding groups within your data.

Supervised Learning
The 3 Elements of Great Machine Learning

How to consistently build effective models that get great results.

# 1: Human guidance

    Human guidance plays a huge role.
    We'll need to make dozens of decisions along the way.
    In fact, the very first major decision is how to roadmap your project for guaranteed success.

# 2: Clean, relevant data

    The second essential element is the quality of our data.
    Garbage In = Garbage Out, no matter which algorithms you use.
    Professional data scientists spend most of their time understanding the data, cleaning it, and engineering new features.

# 3: Avoid overfitting

    One of the most dangerous pitfalls in machine learning is overfitting. An overfit model has "memorized" the noise in the training set, instead of learning the true underlying patterns.
    An overfit model within a hedge fund can cost millions of dollars in losses.
    An overfit model within a hospital can cost thousands of lives.
    For most applications, the stakes won't be quite that high, but overfitting is still the single largest mistake you must avoid.

# The Blueprint

There are 5 core steps:

Exploratory Analysis

First, "get to know" the data. This step should be quick, efficient, and decisive.

Data Cleaning

Then, clean your data to avoid many common pitfalls. Better data beats fancier algorithms.

Feature Engineering

Next, help your algorithms "focus" on what's important by creating new features.

Algorithm Selection

Choose the best, most appropriate algorithms without wasting your time.

Model Training

Finally, train your models. This step is pretty formulaic once you've done the first 4.

Successful Model
There are other situational steps as well:

S. Project Scoping

Sometimes, you'll need to roadmap the project and anticipate data needs.

W. Data Wrangling

You may also need to restructure your dataset into a format that algorithms can handle.

P. Preprocessing

Often, transforming your features first can further improve performance.

E. Ensembling

You can squeeze out even more performance by combining multiple models.

Why explore your dataset upfront?

The purpose of the exploratory analysis is to "get to know" the dataset.
Start with Basics

Basic questions about the dataset:
How many observations do I have?

How many features?

What are the data types of my features? Are they numeric? Categorical?

Do I have a target variable?

Plot Numerical Distributions

Plot Categorical Distributions

Plot Segmentations

Study Correlations
