# Containerize a FastAPI app with Docker

## Getting started

Build the container, providing a tag
`docker build -t fastapi-hello-world:0.1 .`

Then you can run the container, passing in a name for the container, and the previously used tag
`docker run -p 8000:8000 --name my-api fastapi-hello-world:0.1`
