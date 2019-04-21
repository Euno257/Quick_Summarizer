# Quick_Summarizer
We're building a naive summarizer that works based off word frequency scoring. We will be utilizing NLTK Python library to build our pipeline.
Argparse Python module is used to create a command line program as an entry point to our summarizer.

## Prerequisites 
Python 3.2 or greater must be installed

## Setup Virtualenv
Virtualenv is a Python library that allows you to create virtual Python environments and avoid isues with shared library versioning. This step is not required but highly reccomended.
<p><code> $ mkdir simple-summarizer && cd simple-summarizer
$ virtualenv venv --python=python3.6
  $ source venv/bin/activate </code></p>
 
## Installing NLTK
<p><code> pip install nltk </code></p>

## Code 
See summarize.py 

## Run on command line 
<p><code> (venv) $ python Summarizer/Summarizer.py data/Greenland-Melting-Full.txt </code></p>
