# Quick_Summarizer
We're building a naive summarizer that works based off word frequency scoring. We will be utilizing NLTK Python library to build our pipeline.
Argparse Python module is used to create a command line program as an entry point to our summarizer.

## Prerequisites 
Python 3.2 or greater must be installed

## Setup Virtualenv
Virtualenv is a Python library that allows you to create virtual Python environments and avoid isues with shared library versioning. This step is not required but highly reccomended.
<p><code> $ mkdir simple-summarizer && cd simple-summarizer </code></p>
<p><code> $ virtualenv venv --python=python3.6 </p></code>
<p><code> $ source venv/bin/activate </code></p>
 
## Installing NLTK
<p><code> pip install nltk </code></p>

## Code 
See [summarize.py](https://github.com/Euno257/Quick_Summarizer/blob/master/summarizer/summarize.py)

## Run on command line 
<p><code> (venv) $ python Summarizer/Summarizer.py data/Greenland-Melting-Full.txt </code></p>

## Custom input
Place your custom input text file into the 'data' folder. And make changes in CLI command.
