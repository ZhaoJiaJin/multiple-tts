scalable multiple tts识别

plan1:

1. collect single audio files from multiple tts service

2. concat single audio file into 8 characters audio files

3. convert audio to spectrogram using sox command

4. use train.py to train the model




plan2: 


1. collect single audio files from multiple tts service

2. train model for single character

2. split test audio with 8 characters into single character file based on silence

4. use classify.py to recognize single character

3. combine the results from single character

