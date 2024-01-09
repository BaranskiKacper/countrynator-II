# Countrynator II

## Overview

Countrynator II is a guessing game similar to Akinator, but it focuses on identifying countries. It uses a question-and-answer style interaction to determine the country a user is thinking of. The application employs a decision tree algorithm that uses the Gini index as a measure of impurity to optimize the selection of questions and efficiently converge on the correct country.

## Features

- Interactive Q&A gameplay to deduce the country in the user's mind.
- A decision tree algorithm enhanced by the Gini index to choose the most informative questions.
- Bayesian probability updates to refine the guessing accuracy with each question answered.
- A dataset of countries with features used by the decision tree to make guesses.

## Technologies Used

- Python as the primary programming language.
- Decision tree algorithms for the logical structure, utilizing the Gini index for information gain.
- Bayes' theorem for probabilistic inference and updating beliefs.

## Files Description

- `main.py`: The main executable script that launches the game.
- `DecisionNode.py` & `Leaf.py`: Implementation of the decision tree nodes.
- `Tree.py`: Handles the construction and operation of the decision tree, employing the Gini index for optimal question selection.
- `Question.py`: Manages the presentation and sequencing of questions to the user.
- `probability.py`: Utilizes Bayes' theorem to calculate the likelihood of each country being the right guess after each answer.
- `utils.py`: Provides support functions for various operations within the application.
- `base.csv`: A dataset of countries with features used by the decision tree to make guesses.

## Setup

Ensure you have Python installed on your system to run Countrynator II. Follow these steps to get started:

1. Install any necessary dependencies.
2. Execute `main.py` to begin the game.

```bash
python main.py
