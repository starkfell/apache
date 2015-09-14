## apache
Apache Server running on Ubuntu Server 14.04.

Use the following command below to run in Docker

`docker run -d -t -p 80:80 starkfell/apache`

Use the following command to attach run commands within the Container after it is running

`docker exec -ti <CONTAINER_ID> /bin/bash`

