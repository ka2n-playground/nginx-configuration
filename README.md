nginx-configuration
-------------------------

Sandbox for configrating nginx.
Test your nginx configration in Docker container.

    .
    ├── README.md
    ├── Dockerfile
    ├── bin
    │   └── build
    └── etc
        └── nginx


How to use
--------------------------

    $ ./bin/build

This will build and run new container from official `nginx` and copy configurations from `./etc/nginx` to `/etc/nginx` in the container.
Finally container's port `80` will be attached to host's port `8080`.
