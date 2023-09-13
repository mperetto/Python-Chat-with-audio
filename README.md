# Python-Chat-with-audio

## Chat with audio interviews
This ongoing project aims to develop a chat app that allows users to upload an audio file and view the chat history of the file in the format of 'speaker_1: ... speaker_2: ...,' with the ability to ask questions about the interview.

## Project Structure
The project is subdivided in 5 main parts.

1.   Upload and conversion to .wav format of the audio file (using ffmpeg) in case it is not already in .wav format.
2.   Processing the diarization of the audio file using the pyannote model to recognize the speakers in the audio.
3.   Extract the text from the audio with Whisper model.
4.   Matching the audio text segment get by Whisper with the timing of the diarization.
5.   Visualize the extracted text in chat format and permit the Q&A.
