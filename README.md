# Music-Genre-Classification
The project uses Machine Learning and Deep Learning techniques to Classify music into 10 genres of music as provided in the GTZAN dataset. This was submitted as my final project.

### Approach

#### 1) Machine Learning :-
Features like mel-ceptral coefficients, zero-crossing rate, power, loudness etc. are extracted from audio files using librosa library afterwhich the data is feed into the ML models to classify data.

#### 2) Deep Learning :-
Mel Spectrogram images are formed from audio files which are very strong features to discriminate the properties of two audio files. So, these images are feed into CNN model for classification into 10 genres.

## Raw data:
Download GTZAN Dataset from: http://opihi.cs.uvic.ca/sound/genres.tar.gz
Raw data is 1.2GB and consists of 1000 audio files(.au) divided into 10 folders for 10 genres equally. I.e Every genre has 100 audio files.

## Preprocessed data
The raw audio has been converted to mel-spectograms and other features using librosa library for Machine Learning purpose and can be found in the folder as csv file. Feature spectrogram images are made from the audio files directly during training for Deep Learning model.
