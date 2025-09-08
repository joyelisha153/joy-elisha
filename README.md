FROM python:3.10-slim 
# Set the working directory 
WORKDIR /app 
# Copy app file 
COPY app.py . 
# Command to run the app 
CMD ["python", "app.py"] 
