PXELINUX Binaries
=================

Core pxelinux binaries are copied to /pxelinux. Mount a docker volume to the
container and execute a copy as follows:

    docker run --name pxelinux --volume=<host_dir>:/output:rw --rm cjntaylor/pxelinux:latest sh -c 'cd /pxelinux && cp -a * /output'
