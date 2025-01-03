# Next-Word-Prediction-Model-using-LSTM

This project builds a Next Word Prediction model using LSTM (Long Short-Term Memory) in Python on Google Colab. The model predicts the next word in a sequence based on context.

## Setup

1. **Open the notebook** in Google Colab.
2. **Install necessary libraries**:
    ```python
    !pip install tensorflow numpy
    ```

## Steps

1. **Import Data**: Collect a text dataset for training.
2. **Preprocessing**: Tokenize and preprocess the data.
3. **Model**: Build and compile an LSTM model.
4. **Training**: Train the model with a reduced batch size to avoid memory issues.

## Run the Code

```python
from tensorflow.keras.utils import to_categorical
# Data Preprocessing and Model setup
model.fit(X, y, epochs=100, batch_size=32, verbose=1)  # Adjust batch size for memory issues
```

## Conclusion

The trained model can now predict the next word in a sequence, enabling text generation functionality.

