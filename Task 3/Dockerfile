FROM python:3.10.12-slim

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt --no-cache-dir

COPY Task_3.py .
ENTRYPOINT [ "python", "./Task_3.py", "--lr", "0.0001104", "--adam_epsilon",  "8.1781995e-07", "--weight_decay",  "0.0062933" ]