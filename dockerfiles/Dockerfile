FROM pytorch/pytorch:2.5.1-cuda12.4-cudnn9-devel 

RUN apt-get update && apt-get install -y build-essential python3-dev gcc cmake

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 8501

