FROM php:5.6-fpm-alpine
 
RUN rm -rf ar/wwwml/*
 
COPY ./files ar/wwwml
 
EXPOSE 80
 
WORKDIR ar/wwwml
CMD ["php", "-S", "0.0.0.0:80"]