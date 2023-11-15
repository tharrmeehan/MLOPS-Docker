FROM python:3.10.12

WORKDIR /app

RUN pip install -q torch torchaudio transformers pytorch_lightning==1.9.5 datasets torchmetrics wandb scipy scikit-learn

COPY Task_2.py .
ENTRYPOINT [ "python", "./Task_2.py", "--lr", "0.0001104", "--adam_epsilon",  "8.1781995e-07", "--weight_decay",  "0.0062933" ]