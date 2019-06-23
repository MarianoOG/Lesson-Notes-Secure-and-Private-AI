# Lesson Notes Secure and Private AI

This are my personal notes from the [course of udacity](https://eu.udacity.com/course/secure-and-private-ai--ud185) part of the [Facebook Scholarship Challenge](https://eu.udacity.com/facebook-AI-scholarship). This notes are forked from the original notes of the course but with some comments and notes added.

## Tips and Suggestions for this course

Because of work I have been strugging to get time to work in this course. Few sleep and not as much progress as I would love to do. This is the list of thing I have done so far and that will probably help you as well to go trough this course (or others).

### Speed up

Use speed 2x or 3x in the videos (or as fast as you can handle), most of them have really long explanations or even pauses so it will be fine. If you struggle slow down if you are getting bored speed up. I recommend video control speed extension for chrome cause it lets you go beyond 2x that youtube offers natively.

### Skip not needed content

If you already have experience in some topic don't mind skipping parts or the whole video, theres no point in doing things double. If you have experience with machine learning probably Lesson 1 (intro to pytorch) its a bit slow for you, if you don't know about pytorch in specific but have used another framework whatch some tutorials instead on how to use the basic functions and then discover the rest when you need them.

### Watch videos fast program slow

You get your hands dirty, at least I like to do it. I learn more while tying to do stuff for myself so watch videos fast to get the idea but truly understand while doing the exercises, fork this notes or the original ones if you need. One of the things that were the most annoying for me is that the notes don't work as a standalone information, I always needed to refer to the video for explanations and details which took longer in the switching. At the end I either concentrate completly on watching or completly on doing. I will try to keep this notes self explanatory to make the work faster even without videos.

### Use the comunity as a curated search engine

If you don't get it in the first google search, ask somebody else that may know it. This will substantialy reduce the time it takes you to understand some concept tough the eyes of someone that already processed and used it succesfully.

### Search for questions on the matter and answer them

This is a hard step, only use it when you have certain confidence on the topic and you already got some code working. Doing this will bring you new insights on problems you may not tought about and/or different solutions. It will also make you revisit concepts to properly explain to others not only how but why something works in a certain way.

## How to use the jupyter files

To run these notebooks you'll need to install Python 3.6+, PySyft, Numpy, PyTorch 1.0, and Jupyter Notebooks. The easiest way for all of this is to create a conda environment:

```bash
conda create -n pysyft python=3
conda activate pysyft
conda install numpy jupyter notebook
conda install pytorch torchvision -c pytorch
pip install syft
```
