
# DevOps catch-up exam task

You receive a Python application in the [./server.py](./server.py) file.

## Instructions

Clone this repository and run the application locally with Python:

```
python server.py
```

Open http://localhost:8080 in your browser.

Run by configuring a port.

```
PORT=2000 python server.py
```

Open http://localhost:2000 in your browser.

## Tasks

1. Containerize this application with Docker (create a Dockerfile).
2. Run a container exposing a http-server to outside.
3. Create a `docker-compose.yml` file and run a container with Docker Compose.
3. Bonus: Run another container by configuring the inside http-port using `PORT` environment variable.

## Author

Sergei Kudinov
