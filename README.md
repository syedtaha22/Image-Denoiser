# Image Denoiser

This repository contains a neural network model for image denoising. The model is implemented using TensorFlow and Keras, and the code is structured in a Jupyter Notebook for ease of use and experimentation.

## Files

- **`denoiser.ipynb`**: A Jupyter Notebook containing the implementation of the image denoising model, including training, evaluation, and visualization of results.
- **`requirements.txt`**: A text file listing the dependencies required to run the code. You can install them using pip.
- **`denoiser.keras`**: The saved model file, which contains the weights and architecture of the trained denoiser model.

## Installation

To set up the environment and install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. **Open the Jupyter Notebook**: You can open `denoiser.ipynb` in Jupyter Notebook or Jupyter Lab.
2. **Run the Notebook**: Execute the cells in the notebook to train the denoiser model and evaluate its performance.
3. **Load the Model**: If you want to use the trained model, you can load it with the following code:

   ```python
   import tensorflow as tf

   # Load the trained model
   model = tf.keras.models.load_model('denoiser.keras')
   ```

## Requirements

The dependencies required for this project are listed in `requirements.txt`. Ensure you have Python 3.x installed on your machine.