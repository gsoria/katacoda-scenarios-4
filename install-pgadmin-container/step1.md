This tutorial will use the official pgAdmin 4 container from
[Docker Hub](https://cloud.docker.com/repository/docker/dpage/pgadmin4). We will execute the
**docker run** command, passing the required parameters for a basic pgAdmin
configuration. For more details on the available configuration options, see the
[pgAdmin Documentation](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html).

The command to run is shown below. Click it or copy and paste it into the
terminal window to launch the container:

`docker run \
    -p 80:80 \
    -e "PGADMIN_DEFAULT_EMAIL=user@domain.com" \
    -e "PGADMIN_DEFAULT_PASSWORD=SuperSecret" \
    -d dpage/pgadmin4:4.12`{{execute}}

* **-p 80:80** - This directive maps port 80 of the container to port 80 of the
  host.
* **-e "PGADMIN_DEFAULT_EMAIL=user@domain.com"** - This directive sets the
  initial username to login to pgAdmin with.
* **-e "PGADMIN_DEFAULT_PASSWORD=SuperSecret"** - This directive sets the
  initial password to login to pgAdmin with.  
* **-e "-d dpage/pgadmin4:latest"** - This directive specifies the container
  and tag to run.

Once the command has completed and the command prompt is shown again, click
**Continue** to move to the next step.
