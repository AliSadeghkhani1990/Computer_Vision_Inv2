# Computer_Vision_Inv2
**Project Description:**

This project is prepared based on my second course in Coursera which is titled: "Convolutional Neural Network in TensorFlow". This project is simply developed for distinguishing between Dog and Cat images. Some code blocks are added in this program to make it more reliable than the previous computer vision program (Computer_Vision_Inv1), including Data Augmentation; however, there is long way to make it perfect still.


**How to Run the Model:**

For running the project, you can simply open it via Colab, then run the developed project; it will automatically download the dataset, auto-label them, and finally after pre- processing of images they will be fed into the model and training is performed. (Note: Some of the details related to this program are listed in "Extra Explanation").

**Extra Explanation:**
1. For training the model "Cats VS Dogs" dataset which is prepared by "Kaggle" is used.
2. This dataset contains 2000 images of Cats and Dogs for training and 1000 images for validation. 
3. To prevent Over-fitting Data Augmentation is used in this project.
4. ImageDataGenerator class is used to prepare the dataset (Performing Data Augmentation), so it can be fed to a convolutional neural network.
5. The model is developed through TensorFlow, and totally 4 Convolution layers are used (The model architecture can be checked via model.summary()).
6. The model is trained with "binary_crossentropy" loss and "RMSprop" optimizer.
7. Preprocessing of images is done by ImageDataGenerator; the images are auto-labeled, and they are fed to the model in baches of 128 and size of 150*150 pixel.
8. Training is performed for 20 epochs

