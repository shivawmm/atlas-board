# Atlas Board

Atlas Board is a simple Flask-based task management application.

## Features

- Add tasks
- View tasks
- Simple frontend and backend
- Built using Flask

## Run Locally

### Create virtual environment

```bash
python -m venv venv

## Docker Commands

### Build Image

```bash
docker build -t atlas-board:v1 .
```

### Run Container

```bash
docker run -d -p 5000:5000 --name atlas-board-container atlas-board:v1
```

### DockerHub Image

```bash
docker pull YOUR_DOCKERHUB_USERNAME/atlas-board:v1
```

