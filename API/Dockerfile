FROM python:3.9

EXPOSE 8000

COPY . /test

WORKDIR /test

RUN git clone https://github.com/Svirin-S/apu_with_restrictions.git

RUN pip3 install -r /test/apu_with_restrictions/requirements.txt

WORKDIR /test/apu_with_restrictions

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]
