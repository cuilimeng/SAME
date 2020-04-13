# SAME

We implemented the code of SAME.

## Files

The original dataset can be found at [FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet).

The root folder contains the preprocessed news files __sample\_politifact\_fake.csv__ and __sample\_politifact\_real.csv__, and corresponding image files.

Each of the CSV files is comma separated file and have the following columns:

- id - unique identifier for each news

- text - news content

- meta data - rating, channel, description, keywords, original source

- replies - all replies posted under a news tweet, which are separated by "@@@"

Each image file is named as "id"+".jpg".

## Requirements

- Python 3.6.x

- Keras 2.3.1

- Numpy 1.18.2

- Tensorflow 1.15.2

- NLTK 3.2.5

- OpenCV 4.1.2

## Parameters

- MAX\_SENT\_LENGTH = 500

- MAX\_NB\_WORDS = 20000

- EMBEDDING\_DIM = 100

- VALIDATION\_SPLIT = 0.25

- epochs=10, set # of epochs through validation

- batch_size <= 64 to achieve the best performance

## How to run

Note: This code is written in Python3.

- Please see __SAME.ipynb__ to run demos and get basic usage information.