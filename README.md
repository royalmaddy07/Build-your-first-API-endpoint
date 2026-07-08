# First API Endpoint

This project is my first backend assignment for the FlyRank.ai Backend AI Engineering Internship.

## Objective

Build a minimal backend server with two JSON endpoints that can be accessed from a browser or using `curl`.

## Tech Stack

- Python 3
- FastAPI
- Uvicorn

## Project Structure

```
first-api/
├── main.py
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository

```bash
git clone <your-repository-url>
cd first-api
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the server

```bash
uvicorn main:app --reload
```

The server will start at:

```
http://127.0.0.1:8000
```

## API Endpoints

### GET /

Returns a welcome message.

Example response:

```json
{
  "message": "Welcome to my first API"
}
```

---

### GET /hello

Returns a greeting.

Example response:

```json
{
  "message": "Hello World!"
}
```

## Testing

Using a browser:

- http://127.0.0.1:8000/
- http://127.0.0.1:8000/hello

Using curl:

```bash
curl http://127.0.0.1:8000/
curl http://127.0.0.1:8000/hello
```

## Interactive API Documentation

FastAPI automatically generates interactive API documentation.

Visit:

```
http://127.0.0.1:8000/docs
```

## Author

Yash Patel