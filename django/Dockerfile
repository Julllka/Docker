FROM python:3.9-alpine

WORKDIR /crud

COPY ./crud /crud

RUN pip install -r /crud/requirements.txt

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]