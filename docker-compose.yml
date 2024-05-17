version: '3.8'

services:
  fastapi-app:
    build:
      context: .
    volumes:
      # Mount the local app directory to the /code/app directory in the container    
      - ./app:/code/app
    ports:
      - "8080:8080"
    environment:
      - PYTHONUNBUFFERED=1
      - MODE
