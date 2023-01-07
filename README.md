
# Covid-19 Detection using Cough Analysis

This is a file contains the algorithm that detects the presence of covid disease in a person.
The working principle of this project is that the audio file in .wav or .mp3 format that contain cough of the patient is given as input to the algorithm.
The audio's features are extracted from its melspectrogram, out of these MFCC values are extracted using a library called "speaker verification toolkit" after filtering out the noise using RMS silence filter.
In addition to the MFCC values the spectral centroid, spectral bandwidth, spectral rolloff values are extracted from the audio. These values are later used for predicition.
Now, for training algorithm on dataset ,I have selected a decision tree classifier. After training the algorithm is able to predict the Covid-19 disease in the patients cough.


## Deployment

To ensure the successful operation of this project, there are some aspects one should look at.
The python libraries that I used have some dependency issues. So, after downloading required libraries to run the algorithm successfully the following commands should be executed in the terminal.

```python
pip install speaker-verification-toolkit
pip install numba==0.48
pip install resampy==0.3.1
```




## Screenshots

![](/melspectrogram.png)

## Authors

[Bharadwaj](https://github.com/Bharadwaj75-ceo)
