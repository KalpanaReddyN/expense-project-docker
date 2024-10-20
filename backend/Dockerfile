FROM node:20
EXPOSE 8080
ENV DB_HOST="mysql"           # mysql ip address is changing so we can give the mysql container name
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node", "index.js"]    # ENTRYPOINT we didnot write here, after testing we can use.

