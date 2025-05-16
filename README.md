# MP Neuron Like/Unlike Classification

A simple implementation of a McCulloch-Pitts (MP) neuron model for binary classification, specifically to classify "like" and "unlike" patterns. This project is part of a course(from padhAI) assignment to predict whether a user will like a mobile phone based on its features.

## Dataset

- Uses the phone dataset from [91mobiles](https://www.91mobiles.com/) as input data.
- The dataset contains various features of mobile phones, which are used to train and test the model for user preference classification.

## Features

- Implements the MP neuron algorithm from scratch.
- Classifies input patterns as "like" or "unlike".
- Includes training and testing scripts.
- Written in Python with minimal dependencies.

## Project Structure

```bash
MP_Neuron_Like_Unlike_Classification/
├── data/                # Input datasets (phone data from 91mobiles)
├── mp_neuron.py         # Core MP neuron implementation
├── README.md            # Project documentation
└── submission.txt       # The file submitted into the Kaggle Competition
```

## Usage

- Modify [`data`](input) or scripts as needed for your dataset.
- Run the cells in [`MP_neuron.ipynb`](MP_neuron.ipynb) for experimentation.

## References

- [McCulloch, W. S., & Pitts, W. (1943). A logical calculus of the ideas immanent in nervous activity.](https://en.wikipedia.org/wiki/Artificial_neuron#McCulloch%E2%80%93Pitts_(MCP)_neuron)
- [91mobiles - Mobile Phone Dataset](https://www.91mobiles.com/)
