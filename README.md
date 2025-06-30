# FastAPI Hello World

This repository contains a minimal [FastAPI](https://fastapi.tiangolo.com/) application that returns a JSON greeting.

## Setup

1. It is recommended to use a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the app

Start the server using `uvicorn`:

```bash
uvicorn main:app --reload
```

The application will be available at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).
Sending a `GET` request to the root path will return:

```json
{"message": "Hello World"}
```
