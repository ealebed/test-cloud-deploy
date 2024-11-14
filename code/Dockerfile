# Use an official Python runtime as a parent image
FROM python:3.8-slim

RUN pip install flask

# Set the working directory in the container
WORKDIR /app

# Copy the local directory contents into the container at /app
COPY . /app

# Make port 8080 available to the world outside this container
EXPOSE 8080

# Run Python script when the container launches
CMD ["python", "hello_world.py"]
