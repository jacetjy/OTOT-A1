FROM nginx:alpine

# Create app directory
WORKDIR /nginx-sample

RUN rm /etc/nginx/nginx.conf

COPY . .

COPY ./nginx.conf /etc/nginx/nginx.conf