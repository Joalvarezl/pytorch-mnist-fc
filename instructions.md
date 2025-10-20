# Assignment: MNIST Classification

## Assignment Overview

The assignment consists of two main parts:

1. **Model Implementation and Training** (`run_experiment_mnist.py`):
   - Use `run_experiment_moons.py` as a reference to implement the MNIST version
   - Implement the training and evaluation process for MNIST digit classification
   - Track and report training/validation metrics
   - Save the trained model

2. **Model Visualization and Analysis** (`visualization_mnist.ipynb`):
   - Load the trained model
   - Visualize sample predictions
   - Analyze model performance on different digits
   - Create visualizations of model predictions

## Dataset

The MNIST dataset consists of 70,000 handwritten digits (0-9) in grayscale format. Each image is 28x28 pixels. The dataset is automatically downloaded when running the code.

## Tasks

### Part 1: Model Implementation

1. Implement `run_experiment_mnist.py` using `run_experiment_moons.py` as a reference:
   - Load and preprocess the MNIST dataset
   - Implement appropriate data transformations
   - Define a suitable neural network architecture
   - Implement the training loop
   - Track training and validation metrics
   - Save the trained model

### Part 2: Visualization and Analysis

Complete the `visualization_mnist.ipynb` notebook to:
1. Load the trained model
2. Select and display sample images from the test set
3. Show model predictions for these samples
4. Visualize the model's confidence in its predictions
5. Analyze cases where the model makes mistakes
6. Create a confusion matrix to show overall performance

## Evaluation Criteria

Your submission will be evaluated based on:
1. Correct implementation of the MNIST dataset loading and preprocessing
2. Appropriate model architecture and training process
3. Quality of the visualization notebook
4. Analysis of model performance
5. Code organization and documentation
6. **Honest disclosure of AI tool usage** (see AI Tools Usage section below)

## AI Tools Usage

**Important**: If you used any AI tools (such as ChatGPT, GitHub Copilot, Claude, or other AI assistants) to help with this assignment, you must include a section in your README.md file that describes:

1. **Which AI tools you used** (e.g., ChatGPT, GitHub Copilot, etc.)
2. **How you used them** (e.g., for code generation, debugging, explanation, etc.)
3. **What specific parts of your code were AI-assisted** (be specific about functions, sections, or approaches)
4. **How you verified and understood the AI-generated code** (e.g., testing, manual review, etc.)

This disclosure is required for academic integrity and helps us understand your learning process. Using AI tools is permitted, but you must be transparent about their usage.

**Example README section:**
```markdown
## AI Tools Usage

I used the following AI tools in this project:
- **ChatGPT**: Used to help debug my training loop and optimize hyperparameters
- **GitHub Copilot**: Assisted with writing the data preprocessing functions
- **Claude**: Helped explain PyTorch tensor operations and model architecture decisions

The AI tools were primarily used for:
- Debugging the loss function implementation
- Generating boilerplate code for data loaders
- Explaining complex PyTorch concepts

All AI-generated code was thoroughly tested and understood before submission.
```

## Submission

Submit your completed:
1. `run_experiment_mnist.py` with your implementation
2. Completed `visualization_mnist.ipynb`
3. Updated `README.md` with AI tools usage disclosure (if applicable)
