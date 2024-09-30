## 1. Which base image do you want to use?
FROM python:3.8-slim

## 2. Set the working directory in the container.
WORKDIR "/src/wonwoo"

## 3. Copy the project files into the working directory.
COPY . . 

## 4. Install the dependencies
RUN pip install -r flask-demo/requirements.txt

## 5. Document and inform the developer that the application will use PORT 5000 of the container.
EXPOSE 5000

## 6. Define the command to run when the container starts.
CMD ["python","flask-demo/app.py"]