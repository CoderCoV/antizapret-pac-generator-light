with some fixes and adds for selfusing

crontab -e

 0 1 */3 * * /root/antizapret-pac-generator-light/doall.sh && cp /root/antizapret-pac-generator-light/result/proxy-host-ssl.pac /var/www/pac

lighttpd.conf /etc/lighttpd/lighttpd.conf

Resulting PAC files is

https://raw.githubusercontent.com/runalsh/antizapret-pac-generator-light/main/result/proxy-host-nossl.pac

https://raw.githubusercontent.com/runalsh/antizapret-pac-generator-light/main/result/proxy-host-ssl.pac

original https://bitbucket.org/anticensority/antizapret-pac-generator-light