FROM python
WORKDIR /usr/backend/
COPY ./requirements.txt .
COPY ./app.py .
RUN pip install -r requirements.txt
CMD ["python3", "-m", "app.py"]