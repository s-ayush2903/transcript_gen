# Transcript Generator

A web client that generates transcripts of students via parsing data from specific files and makes it available to download as zip.
* Generation of transcript in specified range of roll numbers is supported!

## Running the website
Given instructions should be followed in the order which they are given below:
* Create a new [venv](https://docs.python.org/3/library/venv.html) via `python3 -m venv ./cenv`(`cenv` can be replaced by _any_ name which you want, it is the name of the virtual env you want to create).
* Activate the venv via `source cenv/bin/activate`
* Now install dependencies via `pip3 install -r rex`
* Execute `python3 uiImpl.py` and the server will start at the shown port
* `^Z` / `^C` to stop the server
* `deactivate` to exit from the created venv

