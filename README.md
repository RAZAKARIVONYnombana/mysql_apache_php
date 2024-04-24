# mysql_apache_php
Instalation

#MYSQL
```
cd emplacement_source_mysql
tar -zxvf mysql-8.3.0.tar.gz
cd mysql-8.3.0
```
```
sudo apt install cmake
```
```
mkdir dossier
cd dossier
```
```
sudo apt-get upgrade
```

```
sudo apt-get install libssl-dev
```
```
sudo apt-get install openssl
```
````
cmake ..
```

```
sudo make
```
```
sudo make install
```

#APACHE
```
cd emplacement_source_http2.4.59.tar.gz
tar -xvf httpd-2.4.59.tar.gz
cd httpd-2.4.59
```
```
./config
```
```
sudo apt-get install libapr1-dev
```
```
sudo apt-get install libpcre-posix2 libpcre2-dev
```
```
./config
```
```
sudo make
```
```
sudo make install
```

#PHP
```
cd emplacement_source_php-8.3.6.tar.gz
tar -xvf php-8.3.6.tar.gz
cd php-8.3.6
```
```
./configure
```
```
sudo apt install pkg-config
```
```
sudo apt install libxml2-dev
```
```
sudo apt install libsqlite3-dev
```
```
./configure
```
```
sudo make
```
sudo make install
```

