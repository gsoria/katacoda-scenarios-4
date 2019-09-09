Before PostgreSQL can be installed, the **apt.postgresql.org** package
repository must be setup on the machine. This tutorial is based on Ubuntu
18.04; for the appropriate commands for other Ubuntu versions, please visit
https://www.postgresql.org/download/linux/ubuntu/. Instructions for Debian
Linux can be found at https://www.postgresql.org/download/linux/debian/.

The first step is to create a repository configuration file:

`echo "deb http://apt.postgresql.org/pub/repos/apt/ bionic-pgdg main" > /etc/apt/sources.list.d/pgdg.list`{{execute}}
