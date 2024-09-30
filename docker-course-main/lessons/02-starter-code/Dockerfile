## 1. Which base image do you want to use?
FROM python:3.8-slim
## 2. Set the working directory inside the container.
WORKDIR /src/app/
## 3. Copy your source code file to the working directory inside the container.
COPY python-app.py .
## 4. Define the command to run when the container starts.
CMD ["python","/src/app/python-app.py"]