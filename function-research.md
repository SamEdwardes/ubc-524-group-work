## Preprocessing Shortcut

`preprocess_recipe()`: There are many great tools in the data science ecosystem for pre-processing data (Python's [scikit-learn preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html), R's [caret preprocessing](https://topepo.github.io/caret/pre-processing.html)). However, from our experience we find we are often writing the same lengthy code for common preprocessing tasks (e.g scale numeric features and one hot encode categorical features). `preprocess_recipe()` provides a _shorcut function_ to apply your favourite recipes quickly