FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=udemy \
  MYSQL_USER=udemyuser \
  MYSQL_PASSWORD=udemypass \
  MYSQL_ROOT_PASSWORD=udemyroot \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf
