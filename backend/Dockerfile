# Use Python base image
FROM python:3.12-slim

# Set working directory
WORKDIR /code

# Install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt

# Copy the application code
COPY . .

# Run the Flask app
CMD ["python", "app.py"]
