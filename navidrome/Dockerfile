FROM garethflowers/ftp-server:0.7.0

RUN sed -i -r "s/0.0.0.0/192.168.1.21/g" /etc/vsftpd.conf && sed -i "/pasv_addr_resolve/d" /etc/vsftpd.conf
