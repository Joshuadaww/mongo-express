Check list images from Official Image
<br>URL "https://hub.docker.com/_/mongo-express"
<br>&emsp;$ docker search mongo-express
<br>
<br>
Command :
<br>&emsp;build and run container : $ docker-compose up -d
<br>&emsp;check list container : $ docker ps --format "table{{.ID}}\t{{.Names}}\t{{.Status}}\t{{.Ports}}"
<br>
<br>
Docker's container log
<br>&emsp;$ docker logs mongo-express
<br>


## ----------------------------------------------------------------------
# Check mongo version :
># mongo --version
op:
MongoDB shell version v5.0.3
Build Info: {
    "version": "5.0.3",
    "gitVersion": "657fea5a61a74d7a79df7aff8e4bcf0bc742b748",
    "openSSLVersion": "OpenSSL 1.1.1f  31 Mar 2020",
    "modules": [],
    "allocator": "tcmalloc",
    "environment": {
        "distmod": "ubuntu2004",
        "distarch": "x86_64",
        "target_arch": "x86_64"
    }
}


