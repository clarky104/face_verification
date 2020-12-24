# Face Verification
- Imports a dataset containing images 114 different people with five different expressions: straight face, smiling, closed eyes, suprised (mouth open), straight face with sun glasses on.
- Builds a neural network atop of Google's Xception model (https://arxiv.org/pdf/1610.02357.pdf) - froze all the layers coming from Xception and added two more layers
- Predicts if new image is the same person as one specified in the dataset

# Project Features
- import_pictures
  - preliminary step to set up data, gathers all the images and puts them into new folders based on training_data, validation_data, and test_data
- face_verification
  - creates the model to determine if individual in the image is verified; uses transfer learning along with feature tuning to fit on the data

# Resources
- Transfer learning models (https://keras.io/api/applications/)
- Udemy course for introduction to AI (https://www.udemy.com/share/101WmQA0odcF9bTXw=/)
