ARG BASE_IMAGE=python:3.6-alpine
FROM ${BASE_IMAGE}

# This dockerfile requires build context from https://github.com/mihaTrajbaric/generic_docker_build_context.git

COPY python/hello_world.py hello_world.py

CMD ["python", "hello_world.py"]