FROM python

WORKDIR /docker-mysql

COPY mysql.py .

RUN pip install pymysql
RUN pip install cryptography

CMD ["python", "mysql.py"] 