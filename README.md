# AI Project 1 - Search

This repository contains the solution for Artificial Intelligence I - Project 1 (Search), based on the UC Berkeley Pacman projects.

## Requirements

- Python 3.11
- uv

## Setup

### Install Python 3.11

```bash
uv python install 3.11
``` 

### Create the virtual environment

```bash
uv venv 
```

### Activate the environment

#### Nushell

```nu
overlay use .venv/bin/activate.nu
```

#### Bash / Zsh

```bash
source .venv/bin/activate 
```

### Verify the installation

```bash
python --version 
```

Expected output:

```bash
text Python 3.11.x 
```

## Running Pacman

```bash
python pacman.py 
```

## Running the Autograder

```bash
python autograder.py 
```

## Notes

- Do not modify files other than search.py and searchAgents.py.
- Do not add unnecessary third-party dependencies.
- The .venv directory should not be committed to Git.
