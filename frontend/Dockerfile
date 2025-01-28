FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
#COPY expense.conf /etc/nginx/conf.d/expense.conf


# we have given the expense.conf code in the nginx.conf so last line is not needed.