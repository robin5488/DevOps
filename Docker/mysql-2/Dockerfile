FROM python

WORKDIR /docker-mysql

COPY mysql.py .

RUN pip install pymysql
RUN pip install cryptography

CMD ["python", "mysql.py"] 

#docker run -d --env MYSQL_ROOT_PASSWORD="root" --env MYSQL_DATABASE="userinfo" --name mysqldb mysql
#docker run -it --rm  mysql-code