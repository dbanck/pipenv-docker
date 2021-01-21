# Pipenv Docker Image

This is based on the original [pipenv Dockerfile](https://github.com/pypa/pipenv/blob/master/Dockerfile), but with an updated base image and Python 3.8.

## Usage

```Dockerfile
FROM dbanck/pipenv

COPY . /app

# -- Replace with the correct path to your app's main executable
CMD python3 main.py
```
