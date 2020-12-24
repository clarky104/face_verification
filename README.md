# Face Verification
- Imports a dataset containing images 114 different people with five different expressions: straight face, smiling, closed eyes, suprised (mouth open), straight face with sun glasses on.
- Builds a neural network atop of Google's Xception model (https://arxiv.org/pdf/1610.02357.pdf) - froze all the layers coming from Xception and added two more layers
- Predicts if new image is the same person as one specified in the dataset
