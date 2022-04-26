# syntax=docker/dockerfile:1
FROM python:latest
COPY requirements.txt /tmp
RUN pip install --no-cache-dir -r /tmp/requirements.txt
COPY api.py /srv
CMD ["python", "/srv/api.py"]
