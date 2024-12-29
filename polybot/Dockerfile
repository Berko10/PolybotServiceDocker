FROM python:3.9-alpine

# Set work directory
WORKDIR /app

# Copy requirements file
COPY requirements.txt /app/

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy application files
COPY . /app/

# Expose port (replace 8081 with your app's port if different)
EXPOSE 8081

# Run the application
CMD ["python", "app.py"]
