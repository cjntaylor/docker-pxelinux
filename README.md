PXELINUX Binaries
=================

Core pxelinux binaries are copied to /pxelinux. Mount a docker volume to the
container and execute a copy as follows:

    docker --volume=<host_vol>:/output:rw cjntaylor/pxelinux:latest cp -a /pxelinux/* /output
