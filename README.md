# CSE523

I was working on Disfluency Detection and removal under PhD Sagnik Das. 
I worked on the whole pipeline of creating the dataset from raw videos of public speaker, augmenting the data and finally training different models in order to analysis which model fits best. 


Given the videos of public speaker, following steps were taken to create the datset:
1. Extracting the audio from the video of the public speaker.
2. From the audio signal, converted that into text with the use of Kaldi Library. Also, corresponding to each word were timestamps.
3. Now, I made windows of size 3 seconds with the overlapping of 50%. 
4. The dataset is now augmented. Augmentation is done by adding white noise and rolling the sound.
5. Now, various models like SVM, Neural Network, etc are being trained and tested for the accuracy, false positives and false negatives. 
