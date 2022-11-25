# note_extraction
<img width="800" align="center" alt="Schermata 2022-11-25 alle 19 52 20" src="https://user-images.githubusercontent.com/91341004/204041791-2c3eb5d8-efb7-4c55-a6a1-8d3e98ddd4c7.png">


In this project we use basic tachniques in the field of signal processing (e.g. audio filtering and FFT) to transform an audio track into playable sheet music. The tools in this repository work particularly well for simple audio files (where there is a single instrument playing with constant tempo and fairly differentiated notes). It is also worth noting that depending on the value of some parameters (e.g. downsapling parameters or sempling frequency) the extracted notes frome the audio file can be at different frequency (e.g. in the sample song in the `fur_elise` folder the resulting notes listed in `extracted_notes.txt` are half a tone below the original). Since the techniques used are based primarely on frequency analysis these differences between original audio file and extracted notes are to be expected.

### What's in here?
- Two folders `fur_elise` and `fra_martino` 
- Each folder contains the original audio tracks, matlab scripts needed to execute the tasks `furElise_script.m` and `framartino_script.m`, some auxiliary functions and the extracted notes in a txt file togheter with a matlab presentation in mlx format

### Disclamair 
This project was part of a course of Signal Processing for Big Data at Sapienza University of Rome held by Prof. S. Barbarossa and Prof P. Di Lorenzo. 
