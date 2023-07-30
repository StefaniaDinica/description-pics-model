# Multilabel classification model for description.pics

The deployed web application can be viewed at https://description.pics.

Medium post: [Multi-label classification for generating images descriptions](https://medium.com/@stefaniadinica/multi-label-classification-for-generating-images-descriptions-8f362fe5dff8)

## Motivation of the project

Multi-label classification can save time by automating some processes. It has so many use cases, from automating labelling in e-commerce or healthcare to assisting visually impaired people.

The scope of this project is to generate the description of an image, based on a Multi-label classification model that was trained on a dataset of images and their description.

## About the files
ImagesDescription.ipynb applies a multilabel classification on a dataset of uploaded images and their descriptions.

MoviesGenre.ipynb applies the same classification on [Movie posters genre](https://www.kaggle.com/datasets/raman77768/movie-classifier) dataset from Kaggle.

## Project structure
```
├── images
│   ├── images
│   ├── results.csv
├── movies-images
│   ├── Images
│   ├── train.csv
├── ImagesDescription.ipynb
├── MoviesGenre.ipynb
├── .gitignore
├── README.md
├── requirements.txt
```

! /images and /movies-images folders are not uploded in git because of their dimension.

The folders can be downloaded from https://drive.google.com/drive/folders/1LcARea0fQz4y9lul623hvzDLuXBrDcN0?usp=drive_link.

After downloading the images, make sure the project structure is as described.

## Required libraries
The following libraries were used for this project:
```
absl-py==1.4.0
astunparse==1.6.3
cachetools==5.3.1
certifi==2023.7.22
charset-normalizer==3.2.0
contourpy==1.1.0
cycler==0.11.0
flatbuffers==23.5.26
fonttools==4.41.1
gast==0.4.0
google-auth==2.22.0
google-auth-oauthlib==1.0.0
google-pasta==0.2.0
grpcio==1.56.2
h5py==3.9.0
idna==3.4
importlib-metadata==6.8.0
importlib-resources==6.0.0
joblib==1.3.1
keras==2.13.1
kiwisolver==1.4.4
libclang==16.0.6
Markdown==3.4.4
MarkupSafe==2.1.3
matplotlib==3.7.2
numpy==1.24.3
oauthlib==3.2.2
opt-einsum==3.3.0
packaging==23.1
pandas==2.0.3
Pillow==10.0.0
protobuf==4.23.4
pyasn1==0.5.0
pyasn1-modules==0.3.0
pyparsing==3.0.9
python-dateutil==2.8.2
pytz==2023.3
requests==2.31.0
requests-oauthlib==1.3.1
rsa==4.9
scikit-learn==1.3.0
scipy==1.11.1
six==1.16.0
sklearn==0.0.post4
tensorboard==2.13.0
tensorboard-data-server==0.7.1
tensorflow==2.13.0
tensorflow-estimator==2.13.0
tensorflow-macos==2.13.0
termcolor==2.3.0
threadpoolctl==3.2.0
typing_extensions==4.5.0
tzdata==2023.3
urllib3==1.26.16
Werkzeug==2.3.6
wrapt==1.15.0
zipp==3.16.2
```

## Installation
This project was build using Python 3.
For installing all the requirements, run `pip install -r requirements.txt`

## References and acknowledgements
Many thanks to the authors of the following articles, which were a source of inspiration:

[How to Grid Search Hyperparameters for Deep Learning Models in Python with Keras](https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/)

[Build your First Multi-Label Image Classification Model in Python](https://www.analyticsvidhya.com/blog/2019/04/build-first-multi-label-image-classification-model-python/)

Also, thanks to the author of this dataset in Kaggle:

[Movie Posters](https://www.kaggle.com/datasets/raman77768/movie-classifier)
