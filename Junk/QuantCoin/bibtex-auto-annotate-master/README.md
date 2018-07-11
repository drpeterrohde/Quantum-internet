bibtex_auto_annotate
====================

BibTeX auto annotator. Uses [Crossref](https://www.crossref.org)'s API.

## Features
Annotates all BibTeX records with:
  - [DOI](https://en.wikipedia.org/wiki/Digital_object_identifier)s

## Installation
Ensure [Python](https://www.python.org/downloads) and [`pip`](https://pip.pypa.io/en/stable/installing) are installed, then from your command-line interface run:

    pip install https://api.github.com/repos/SamuelMarks/bibtex-auto-annotate/zipball

## Usage

    python -m bibtex_auto_annotate -h
    usage: bibtex_auto_annotate [-h] [-v] [-f FILE] [-o OUTFILE]

    BibTeX auto annotator
    
    optional arguments:
      -h, --help            show this help message and exit
      -v, --version         show program's version number and exit
      -f FILE, --files FILE
                            One or more BibTeX files. Accepts * as wildcard for
                            directories or filenames
      -o OUTFILE, --output-file OUTFILE
                            Output BibTeX file


## Development
Tested with Python 2.7. Should work on Python 3+ also.

### Install dependencies

    pip install -r requirements.txt

### Install package

    pip install .

### Test package

    python setup.py test

### TODO

  - Finish implementing glob support
  - Implement multiple output files, and putting multiple input files into one output
  - in-place output
