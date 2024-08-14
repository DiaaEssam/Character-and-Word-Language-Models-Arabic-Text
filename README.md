# Arabic Text Language Models

This Jupyter notebook focuses on creating language models for Arabic text using TensorFlow and other Python libraries. The models include character-level and word-level language models designed to generate text based on input sequences.

## Getting Started

To run this notebook, ensure you have Python 3 installed along with the following libraries:

- `wikipedia`
- `reportlab`
- `arabic_reshaper`
- `python-bidi`

You can install these dependencies using pip:

```bash
pip install wikipedia reportlab arabic_reshaper python-bidi
```

## Notebook Contents

1. **Installing Libraries**: Installation of necessary Python libraries for text processing and model building.
   
2. **Importing Libraries**: Importing required libraries including TensorFlow, NumPy, Matplotlib, and more.
   
3. **Function to Generate Documents**: A function to scrape Arabic text from Wikipedia related to "صلاح الدين" (Saladin).
   
4. **Function to Build Character Dictionaries**: Creating dictionaries for mapping characters to indices and vice versa.
   
5. **Function to Prepare Data**: Preparing data for the language models by creating input sequences and target characters.
   
6. **Model Building**: Building character and word-level language models using TensorFlow.

## Usage

1. Open the notebook in a Jupyter environment.
2. Run each cell sequentially to install libraries and execute functions.
3. Customize the models, data preparation, or training process as needed.
4. Experiment with different hyperparameters and architectures to improve the language models.
