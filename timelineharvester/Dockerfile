FROM python:3

WORKDIR /usr/src/timelineharvester

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "./new-user-listener.py" ]
