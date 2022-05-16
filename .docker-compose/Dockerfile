FROM  phpdockerio/php74-fpm

RUN   apt update && \
      apt install -y php7.4-mysql php7.4-ldap php7.4-gd nano mysql-client iputils-ping && \
      apt-get autoremove -y && \
      rm -rf /var/lib/apt/lists/*
