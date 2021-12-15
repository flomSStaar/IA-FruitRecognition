# IA-FruitRecognition
Ce projet consiste à développer une intelligence artificielle permet de classifier des fruits grâce à une photo.

Lien vers le dataset: https://www.kaggle.com/sshikamaru/fruit-recognition

## Dataset
Total number of images: 22495.

Training set size: 16854 images (one fruit or vegetable per image).

Test set size: 5641 images (one fruit or vegetable per image).

Number of classes: 33 (fruits and vegetables).

Image size: 100x100 pixels.

Training data filename format: [fruit/vegetable name][id].jpg (e.g. Apple Braeburn100.jpg). Many images are also rotated, to help training.

Testing data filename format: [4 digit id].jpg (e.g. 0001.jpg)

Content
train - the training folder that contains 33 subfolders in which training images for each fruit/vegetable are located. There is a total of 16854 images.
test - the testing folder that contains 5641 testing images
sampleSubmission.csv - a sample submission file in the correct format, with id number and string label

## Bibliothèques utilisés
- numpy
- pandas
- matplotlib
- sklearn
- glob
- os
- datetime
- seaborn
- cv2 (opencv)
