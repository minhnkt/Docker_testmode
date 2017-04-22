FROM centos:6

MAINTAINER VPSSIM <minhnkt@live.com>

#run update and install vpssim
RUN yum -y update && \
	yum -y install \
	epel-release wget htop



#VOLUME ["/var/www/html"]

#chuyển thư mục làm việc vào đường dẫn bên dưới
WORKDIR /root/

#Cổng dịch vụ sẽ chạy của container
EXPOSE 9000

#lệnh thực thi ngay khi khởi chạy container
CMD ["nginx"]
#CMD ["apache"]
#CMD ["/user/sbin/php7-fpm"]


