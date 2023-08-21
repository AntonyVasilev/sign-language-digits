# Images detection - sign language digits.

**Data**:
## Sign Language Digits Dataset
### Turkey Ankara Ayrancı Anadolu High School's Sign Language Digits Dataset
https://www.kaggle.com/ardamavi/sign-language-digits-dataset

### Context
Sign languages (also known as signed languages) are languages that use manual communication to convey meaning. This can include simultaneously employing hand gestures, movement, orientation of the fingers, arms or body, and facial expressions to convey a speaker's ideas.

### Details of datasets:
* Image size: 64x64
* Color space: Grayscale
* File format: npy
* Number of classes: 10 (Digits: 0-9)
* Number of participant students: 218
* Number of samples per student: 10

**Stack**: python 3, numpy, matplotlib, keras, tensorflow

**Solution**: A convolutional neural network consisting of 3 blocks of Conv2D+MaxPooling2D layers and 2 fully connected layers and one more fully connected layer at the output.
