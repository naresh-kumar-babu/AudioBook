# AudioBook

In this code, a simple implementation of PDF Audiobook is shown. PDF text is read to the user as audio using this code.

**Introduction**

Reading stories or essays or any text can be arduous, however an audio reading of the text is convenient and doesnt require as much concentration as reading requires. In this project, I implemented a simple PDF to audio converter. This code scans page(s) of PDF and reads it using audio, to the user.

**Project Flow**

1. This code reads the pdf file.
2. It extracts text from the pdf file.
3. Then, we use Google Text to Speech (gTTS) library to convert text to audio file.
4. Also, we used pyttsx3 for audio in replace of gTTS.

**Conclusion**

It was seen that the code performs really well in reading straightforward PDF text files, however, if equations are involved in the text, then the reader cannot properly read the equations. However, text will be read just fine.
