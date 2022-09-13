# Music Emotion Recognizer

This project is a recognizer that can distinguish emotions delivered by different music.

## Algorithm

Our algorithm contains 3 steps:
1. Analyze audio files to get scores of some features;
2. Label those files with different emotions;
3. Use Machine Learning to build a mapping from features to emotions.

For step 1, we evaluated 3 features, which is tonality, tempo and spectral centroid.
For step 2, we simply supposed that emotions can be described by two factors, which is valence and energy, and labeled files by ourselves.
For step 3, we used Random Forest algorithm to build the mapping.

## How to Use

1. Install all needed libraries;
2. Place the audio file to be analyzed and the notebook file in the same directory;
3. In the last cell of the notebook, change the target file name.

## Future Edition

Actually there are a number of drawbacks. In the future, we may evaluate more features, collect more traning data and optimize the classification of emotions and the ML algorithm. ~~But we don't think we have that time.~~
