# instructions for setting up rshiny on BNHM server

shiny doesn't like reverse proxy, running for now directly on port 80 with apache
not listening there.


= Install R
```
yum install R
```

= Markdown installation
our server doesn't allow executables to stored under /tmp, so:
as sudo:
```
%mkdir ~{user}/tmp
%export TMPDIR=~{user}/tmp
% R
R-promt% install.packages("rmarkdown")
```
= Starting and stopping server
stop shiny-server
start shiny-server

= Shiny configuration 
Shiny configuration file is at: /etc/shiny-server/shiny-server.conf 
  * change to port 80
  * specify application locations as /srv/shiny-server-{application_name}
  * specify log directores as /var/log/shiny-server/{application_name}


