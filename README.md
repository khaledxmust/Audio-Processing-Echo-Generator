# Audio-Processing-Echo-Generator
Echo Generator - Generating Echo-Based Dataset from Audio file for Training Neural Networks

This a Echo Dataset Creation from Audio files based on 3 parameters:
1.     Delx = [1, 50, 100, 300, 500, 1000], where Delx is the "Delay" between the actual sound and the generated echo.
2.     Volx = [0.1, 0.2, 0.4, 0.6, 0.8, 1], where Volx is the "Volume" of the generated echo.
3.     Mulx = [0, 1, 2, 3, 4, 5]          ,where Mulx is the "Number" of generated echos in one audio file.

That Notebook should iterate on specified folder that was given to run on all included audio files, generating all the possible combination from those 3 parameters in a single audio file, generating arround 200 audio files named as the parameters specified from a single audio file, Creating a Folder called Echo where all of Echoed-Audios will be saved.
