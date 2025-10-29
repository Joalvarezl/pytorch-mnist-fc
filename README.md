# PyTorch Neural Network

**Jose Enrique Alvarez Lara**

This repository contains a neural network that classifies handwritten digits.
It receives as input a grayscale image of size 28×28 pixels, converts it into a vector, and processes it through a fully connected neural network (Fully Connected Network) with ReLU activation functions and Dropout to prevent overfitting.

> **📋 Assignment Instructions**: Detailed instructions for this assignment can be found in [`instructions.md`](instructions.md). Please read the instructions file carefully before starting your work.

## Setup Instructions

### 1. Create a Conda Environment

```bash
# Create a new conda environment named 'torchenv'
conda create -n torchenv python=3.13

# Activate the environment
conda activate torchenv
```

### 2. Install Dependencies

```bash
# Install required packages
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
# Start Jupyter Notebook
jupyter notebook
```

Then open `[YOUR_MAIN_NOTEBOOK].ipynb` in your browser.

## Project Structure

- `[MAIN_NOTEBOOK].ipynb`: [DESCRIPTION OF YOUR MAIN NOTEBOOK]
- `run_experiment_[DATASET].py`: [DESCRIPTION OF YOUR TRAINING SCRIPT]
- `visualization_[DATASET].ipynb`: [DESCRIPTION OF YOUR VISUALIZATION NOTEBOOK]
- `requirements.txt`: List of required Python packages
- `instructions.md`: Assignment instructions and requirements

## Features

- [LIST YOUR SPECIFIC FEATURES HERE, e.g.,:]
- Data preprocessing with [LIBRARY NAME]
- PyTorch neural network implementation
- Training loop with loss and accuracy tracking
- Model evaluation on test set
- [ADD ANY OTHER FEATURES YOUR PROJECT INCLUDES]

## Requirements

- [ADD REQUIRED LIBRARIES]

> **Note**: All required packages are listed in `requirements.txt`. Install them using `pip install -r requirements.txt`

## Note

Make sure you have CUDA installed on your system if you want to use GPU acceleration with PyTorch. The requirements.txt file will automatically install the appropriate PyTorch version for your system.

---

## 📝 Template Instructions

This README.md file is a template. Please replace all placeholders (text in square brackets like `[PLACEHOLDER]`) with your specific information:

- `[PROJECT TITLE]`: Your project's title
- `[STUDENT NAME]`: Your name
- `[BRIEF DESCRIPTION OF YOUR PROJECT]`: What your project does
- `[MAIN_NOTEBOOK].ipynb`: Your main notebook filename
- `[DATASET]`: The dataset you're working with (e.g., mnist, moons)
- `[LIBRARY NAME]`: Specific libraries you used for preprocessing
- `[ADD OTHER REQUIRED LIBRARIES]`: Any additional dependencies
- `[ADD ANY OTHER FEATURES YOUR PROJECT INCLUDES]`: Additional features

Make sure to read the `instructions.md` file for detailed assignment requirements before starting your work.

## AI Tools Usage

[IF YOU USED ANY AI TOOLS, DESCRIBE THEM HERE. See instructions.md for detailed requirements on what to include in this section. If you didn't use any AI tools, you can delete this section or write "No AI tools were used in this project."]

---
