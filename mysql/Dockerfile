FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
ADD scripts/*.sql /docker-entrypoint-initdb.d 
    # MYSQL_DATABASE=transactions \
    # MYSQL_USER=expense \
    # MYSQL_PASSWORD=ExpenseApp@1


# scripts lo vunde anni .sql files keeping in this folder (/docker-entrypoint-initdb.d). 
# while running this, mysql image will run everything from that folder.
