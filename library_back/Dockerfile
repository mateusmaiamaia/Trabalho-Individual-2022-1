FROM python:3.9  

WORKDIR /code/

COPY requirements.txt /code/

RUN pip install -r requirements.txt

COPY . /code/

COPY entrypoint.sh /code/

#RUN chmod +x code/entrypoint.sh

CMD [ "sh","entrypoint.sh" ]
