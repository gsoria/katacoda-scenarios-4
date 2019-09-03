Finally, we can go ahead and install PostgreSQL 11 using **apt-get**:

`apt-get -y install postgresql-11`{{execute}}

PostgreSQL packages on Ubuntu (and Debian) Linux will automatically initialise
the database cluster and start the service. Once the installation has completed,
examine the process list to see if the server is running as expected:

`ps -ef | grep postgres`{{execute}}
