# Pynash Meetup: Pytest Features

This repo is the code examples used in the pynash talk of March 16, 2023.

You can see the different code examples under the branches in this repo.

Each branch with tests has a file `.justfile`. See that file for the commands to run the tests in that branch, e.g.
```bash
pytest .
```
or
```bash
PYTHONPATH=src pytest .
```

## Set Up

in terminal, run:

``` bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```