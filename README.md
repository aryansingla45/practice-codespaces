# practice-codespaces

[![Python application test with Github Actions](https://github.com/aryansingla45/practice-codespaces/actions/workflows/testing-ci.yml/badge.svg)](https://github.com/aryansingla45/practice-codespaces/actions/workflows/testing-ci.yml)


This repository contains a simple Python file that demonstrates the use of GitHub Actions for continuous integration.

## Project Structure

- `hello.py`: Main Python script.
- `test_hello.py`: Test script for `hello.py`.
- `Makefile`: Contains commands to setup environment, run tests, and lint and format code.
- `requirements.txt`: Python dependencies file.
- `.github/workflows/testing-ci.yaml`: GitHub Actions workflow file for CI.


### Installation

1. CLone the repository
   `https://github.com/aryansingla45/practice-codespaces.git`

2. Create and activate a virtual environment
  `python3 -m venv .venv
source .venv/bin/activate`

3. Install the dependencies:
   `pip install -r requirements.txt` or `make install`

### Usage 

Run `python hello.py`

### Running Tests

`make test` or `python test_hello.py`

### License 

This repository uses MIT License.

