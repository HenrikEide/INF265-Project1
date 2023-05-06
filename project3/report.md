# Project 3: Sequence models

### Files included in this directory:

- `report.md`: This file.
- `sequence_models.ipynb`: Jupyter notebook containing the code for this project.
- `utils.py`: Python file containing helper functions from course material.

Token embedding and text generation, using different model architectures, like MLP and RNN. The models are trained on a dataset of real text. The goal is to learn some NLP and maybe get some cool text generation models.

### Questions:

1. What is the purpose of the masked softmax? Explain in your own words what it is.
   Ans: Some tokens are padded so they are same length as the longest once, the masked softmask is used to ignore the padded tokens when calculating the loss.

2. How do attention layers deal with sequences of different length?

   Ans: They calculate a weighted sum for the tokens.
