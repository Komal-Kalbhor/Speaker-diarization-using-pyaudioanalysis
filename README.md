### Speaker diarization using pyAudioAnalysis

This contains a python script for speaker diarization

#### Steps followed :
1.  Git clone [pyAudioAnalysis repository](https://github.com/tyiannak/pyAudioAnalysis.git)
2.  Import required libraries
3.  Read input audio
4.  Some modifications are made in [audioSegmentation](script/audioSegmentation.py) python file as compared to the originalpython file from     the repository.
6.  Function to detect speaker id and speech and write data to CSV file
7.  Sppech recognition is done using [wit.ai](https://wit.ai/)

##### [Full python script for speaker diarization](script/audioSegmentation.py)
