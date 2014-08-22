postgresql-9.3-docker
=====================

A project to create Postgresql 9.3 Docker image. 

The image create a database user odoodba whose password is odoodba. 
It also create a database odoodba owned by odoodba. 

It exposes three volumes: 

* /etc/postgresql          # configuration files
* /var/log/postgresql      # log files
* /var/lib/postgresql      # database files

The database directory is /var/lib/postgresql/9.3/data. 

