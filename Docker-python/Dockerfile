FROM python:latest

#  make a dir for app to run
WORKDIR /app

# install dependencies 
COPY requirements.txt .

RUN pip install -r requirements.txt
# import python code

COPY /docker-python .

# run the python app
CMD ["python", "app.py"]