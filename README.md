# Neural Style Transfer

This code contains a simple implementation of neural style transfer using TensorFlow and Keras. The code allows you to apply style transfer to a content image using a style image.
Below are instructions on setting up and running the notebook.

## Prerequisites:

Make sure you have the following dependencies installed:

- TensorFlow
- Numpy
- Matplotlib


## Directions: 

1. Open the `22CL60R04_PARAG_GAWAI.ipynb` notebook in your jupyter notebook and follow the instructions within the notebook.
2. Execute the cells in the notebook to perform style transfer. The stylized image will be displayed at regular intervals during training.
3. You can customize the parameters such as num_epochs, alpha, beta, and learning_rate according to your preferences.
4. Ensure that you provide the correct file paths for your content and style images in the example section of the notebook-
*style_transfer("path/to/content/image.jpg", "path/to/style/image.jpg", num_epochs=10)*

## Limitations and Potential Improvements:

1. Both the Content loss and style loss are 0 in every epoch, this is because this model is not training well.
2. We can change the optimizers and activation functions for the better results.
3. Also we can tune the hyperparameters like num_epochs, alpha, beta, and learning_rate according to our preferences.
