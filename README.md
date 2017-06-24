# SQUID3 + OPENSSH DOCKER
> docker run --name injector -dit -p 80:80 -p 3128:3128 -p 1025:22 magumbo/mgia-3g && docker exec injector bash -c 'service squid3 restart ; service ssh restart'

Setting up a Squid proxy user:

> htpasswd -c /etc/squid3/passwords username_you_like

> service squid3 restart
