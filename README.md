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
