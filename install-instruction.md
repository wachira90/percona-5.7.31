wget https://www.percona.com/downloads/Percona-Server-5.7/Percona-Server-5.7.31-34/binary/redhat/7/x86_64/Percona-Server-5.7.31-34-r2e68637-el7-x86_64-bundle.tar

tar xvf Percona-Server-5.7.31-34-r2e68637-el7-x86_64-bundle.tar

$ ls *.rpm

Percona-Server-57-debuginfo-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-client-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-devel-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-rocksdb-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-server-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-shared-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-shared-compat-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-test-57-5.7.31-34.1.el7.x86_64.rpm
Percona-Server-tokudb-57-5.7.31-34.1.el7.x86_64.rpm



rpm -ivh Percona-Server-server-57-5.7.31-34.1.el7.x86_64.rpm \
Percona-Server-client-57-5.7.31-34.1.el7.x86_64.rpm \
Percona-Server-shared-57-5.7.31-34.1.el7.x86_64.rpm


TokuDB storage engine, adding => Percona-Server-tokudb-57-5.7.31-34.1.el7.x86_64.rpm
https://www.percona.com/doc/percona-server/5.7/tokudb/tokudb_installation.html#tokudb-installation


MyRocks storage engine, adding => Percona-Server-rocksdb-57-5.7.31-34.1.el7.x86_64.rpm
https://www.percona.com/doc/percona-server/5.7/myrocks/install.html#myrocks-install

