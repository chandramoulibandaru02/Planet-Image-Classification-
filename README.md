# Planet-Image-Classification-
This is the image classification for the planets, If you send the image it will shows the planet name

Data Set LINK ---> kaggle datasets download emirhanai/planets-and-moons-dataset-ai-in-space

###  What I Did here is__>>
- Collected dataset from [Kaggle](https://www.kaggle.com/).
- Preprocessed and augmented images to improve model robustness.
- Used **TensorFlow/Keras** with a CNN architecture:
  - Conv2D → MaxPooling → Dropout → Dense layers
- Achieved **91% accuracy** on the test set.

- 🛠 Approach
Data Loading & Preprocessing
Combined two separate datasets (a1 and a2) into one (a3).
Applied resizing (224×224), normalization, and augmentation.
Model Architecture
CNN with Conv2D → MaxPooling → Dropout layers.
Dense layers with ReLU activation.
Output layer with Softmax for multi-class classification.
Training
Loss: sparse_categorical_crossentropy
Optimizer: Adam with learning rate 0.0001
Testing
Evaluated with accuracy and confusion matrix
Visualized predictions using matplotlib subplots.
- 
