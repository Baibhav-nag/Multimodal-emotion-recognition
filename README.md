# Multimodal emotion recognition
Here we have performed human emotion recognition from audio-visual data on two datasets the RAVDESS and the SAVEE dataset using CNNs as both our audio and video models. We have extracted the video features using the in-built OpenCV face detector that can be implemented using the .caffemodel and .prototxt.txt files. Audio features have been extracted using librosa library. We have used spectral contrast,tonnetz,mfccs and melspectrograms as our audio features. Our results are as follows:-  

For RAVDESS dataset we get a test accuracy of 75.69 %.

For SAVEE dataset we get a test accuracy of 97.91 %.
