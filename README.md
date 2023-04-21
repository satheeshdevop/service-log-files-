 # sudo su -
# systemctl start httpd.service
# systemctl status  httpd.service               if  errorcode is there
# joutnalctl-u httpd.servie                          httpd: cloud not open the configuration 
# ls /etc/httpd/conf                  op:  httpd.conf.bkup       magic
# mv /etc/httpd/conf/httpd.conf.bkup /etc/httpd/conf/httpd.conf
# systemctl restart httpd.service
# systemctl status httpd.service
# elinks http://localhost                           [Yes]       


