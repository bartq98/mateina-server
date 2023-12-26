FROM python:3.12.1-bookworm

WORKDIR /mateina

COPY ./requirements.cfg /mateina/requirements.txt

RUN pip install --no-cache-dir --upgrade pip

RUN pip install --no-cache-dir --upgrade -r /mateina/requirements.txt

CMD [ "uvicorn", "app.src.main:app", "--host", "0.0.0.0", "--port", "80",]
