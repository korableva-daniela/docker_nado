FROM python:3
ENV PYTHONUNBUFFERED 1
WORKDIR /app
ADD . /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "manage.py", "runserver", "0.0.0.0:8000"]
