# syntax=docker/dockerfile:1
FROM python:latest
#ENV API_BACKEND_URL=api-backend
#ENV API_BACKEND_PORT=8001
COPY requirements.txt /tmp
RUN pip install --no-cache-dir -r /tmp/requirements.txt
COPY api.py /srv
CMD ["python", "/srv/api.py"]
