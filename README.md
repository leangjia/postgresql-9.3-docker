postgresql-9.3-docker
=====================

A project to create Postgresql 9.3 Docker image. 

The image create a database user odoodba whose password is odoodba. 
It also create a database odoodba owned by odoodba. 

It exposes two volumes: 

* /var/log/postgresql
* /var/lib/postgresql

The database directory is /var/lib/postgresql/9.3/data. 

