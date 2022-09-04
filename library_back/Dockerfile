FROM python:3.9  

WORKDIR /code/

COPY requirements.txt /code/

RUN pip install -r requirements.txt

COPY . /code/

RUN chmod +x /entrypoint.sh

CMD [ "./entrypoint.sh" ]
