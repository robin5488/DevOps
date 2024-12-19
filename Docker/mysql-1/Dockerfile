FROM python

WORKDIR /docker-mysql

COPY mysql.py .

RUN pip install pymysql
RUN pip install cryptography

CMD ["python", "mysql.py"]


#docker network create my-net
#docker run -d --env MYSQL_ROOT_PASSWORD="root" --env MYSQL_DATABASE="userinfo" --name mysqldb --network my-net mysql
#docker run -it --rm --network my-net mysql-code