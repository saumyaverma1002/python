FROM python:3

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt 

RUN cd devops

CMD ["python3", "manage.py" , "runserver" , "0.0.0.0:8000" ]
