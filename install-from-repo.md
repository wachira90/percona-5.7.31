# Installing Percona Server for MySQL 5.7

## key

https://downloads.percona.com/downloads/RPM-GPG-KEY-percona

## repo

yum install https://repo.percona.com/yum/percona-release-latest.noarch.rpm

## install Percona Server for MySQL with SELinux policies

yum install http://repo.percona.com/centos/7/RPMS/x86_64/Percona-Server-selinux-57-5.7.31-rel84.2.el7.noarch.rpm


## Testing the repository

yum list | grep percona

## Install percona

yum install Percona-Server-server-57  Percona-Server-client-57 -y


Files => Location

mysqld server => /usr/bin

Configuration => /etc/my.cnf

Data directory =>  /var/lib/mysql

Logs => /var/log/mysqld.log


from => https://www.percona.com/doc/percona-server/5.7/installation/yum_repo.html
