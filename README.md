# Speech-Recognition
Speech recognition is an interdisciplinary subfield of computational linguistics that develops methodologies and technologies that enables the recognition and translation of spoken language into text by computers.

## Overview
In this exercise we try our very own speech-to-text model using Python in this article. The ability to weave deep learning skills with NLP is a coveted one in the industry. 

We will use a real-world dataset and build this speech-to-text model.


## Introduction
This will sound familiar to anyone who has owned a smartphone in the last decade. I can’t remember the last time I took the time to type out the entire query on Google Search. I simply ask the question – and Google lays out the entire weather pattern for me.

It saves me a ton of time and I can quickly glance at my screen and get back to work. A win-win for everyone! But how does Google understand what I’m saying? And how does Google’s system convert my query into text on my phone’s screen?

This is where the beauty of speech-to-text models comes in. Google uses a mix of deep learning and Natural Language Processing (NLP) techniques to parse through our query, retrieve the answer and present it in the form of both audio and text.

The same speech-to-text concept is used in all the other popular speech recognition technologies out there, such as Amazon’s Alexa, Apple’s Siri, and so on. The semantics might vary from company to company, but the overall idea remains the same.

## Understanding the Problem Statement for our Speech-to-Text Project
Let’s understand the problem statement of our project before we move into the implementation part.

We might be on the verge of having too many screens around us. It seems like every day, new versions of common objects are “re-invented” with built-in wifi and bright touchscreens. A promising antidote to our screen addiction is voice interfaces. 

TensorFlow recently released the Speech Commands Datasets. It includes 65,000 one-second long utterances of 30 short words, by thousands of different people. We’ll build a speech recognition system that understands simple spoken commands.

## Important steps to repeat the exercise:

### Packages needed
1. SpeechRecognition
2. pyAudio

### How to install packages in python
1. Using cmd:
pip install package_name

2. On Jupyter Notebook:
import sys
!{sys.executable} -m pip install package_name

## Installing pyAudio package:
This step is an important one. While most packages load easily, pyAudio when installed throws error for some system as it is unable to find the required .whl files needed to successfully listen to the audio.

In case you get the same error on trying any of the first two ways of installing packeges, follow the below steps and you will be fine.

1. Identify whether your system has a 32-bit python or a 64-bit python. To do this go to run and type cmd. Then just type 'python' and press enter. You will find the details.

2. Then use the details to identify the right .whl file from the link - https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio and download it. Go the folder where you have it saved and copy the file.
Thanks to Christoph Gohlke, Laboratory for Fluorescence Dynamics, University of California, Irvine.

3. Once done, go to run and type - %appdata% and press enter. Go back in the folder hierarchy by a step and then paste the file from step 2.

4. Use the address bar to copy the path. The path would be like - folder name/<file_name>

5. Pick the any of the two steps to install a package and paste the entire path from step 4 as the package_name

6. Run: import pyaudio
