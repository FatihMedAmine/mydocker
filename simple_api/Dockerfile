FROM python:3.8-buster

LABEL maintainer="Anas Ichmawin anasichmawin87@gmail.com, Personne 2 <email2@example.com>, Personne 3 <email3@example.com>"

WORKDIR /

COPY student_age.py requirements.txt student_age.json /

RUN pip install -r requirements.txt

CMD ["python3", "./student_age.py"]