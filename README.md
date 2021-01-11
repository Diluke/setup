# Setup script for Redash with Docker on PhotonOS 3.0 Revision 3.

This is a fork setup script for Redash on a single PhotonOS machine, which uses Docker and Docker Compose for deployment and management.

* `setup.sh` is the script that installs everything and creates the directories.
* `docker-compose.yml` is the Docker Compose setup file.

## FAQ

### How do You upgrade to newer versions of Redash?

First step is to see [Upgrade Guide] at (https://redash.io/help/open-source/admin-guide/how-to-upgrade).

### How do You use `setup.sh` on a different operating system?

You adapt, or search for what you need.
I bet you there is alot of forks for other systems, This one is actualy from Ubuntu 18.04.
Basicaly you can take docker-compose.yml and spin up your own container just about anywhere.
