# FastAPI Project

A simple FastAPI project that exposes a basic endpoint.

## Requirements

- Python 3.8+

## Steps to run the project

1. Clone this repository.
2. Navigate to the project directory.
3. Create a virtual environment and install dependencies:


## Create a virtual environment
```
python3 -m venv .venv
source .venv/bin/activate
```

## Install the required packages
```
pip install -r requirements.txt
```

## Run the FastAPI app using Uvicorn (Development)
```
uvicorn app.main:app --host 0.0.0.0 --reload
```