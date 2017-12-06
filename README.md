# -cnpm

# Using

    $ docker pull hbrls/cnpm:latest
    $ docker run -d -p 7001:7001 -p 7002:7002 -v /cnpm/config:/var/app/cnpmjs.org/config  -v /cnpm/readme.md:/var/app/cnpmjs.org/docs/web/readme.md -v /cnpm/storage:/var/www  --name cnpm notices/cnpm:latest

# Openshift