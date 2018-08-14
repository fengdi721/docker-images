FROM nginx
# Set the timezone of Image
RUN echo "Asia/Shanghai" > /etc/timezone
RUN echo "Asia/Shanghai" > /etc/timezone_test
RUN dpkg-reconfigure -f noninteractive tzdata

RUN echo '<h1>Hello, Docker!</h1>' > /usr/share/nginx/html/index.html

