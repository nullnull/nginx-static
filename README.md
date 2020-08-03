# Static Web Server by nginx (Docker)

## How to use
```sh
# build
$ docker build -t static-nginx .

# run
$ docker run -p 3000:80 -v $(pwd)/public:/root/public static-nginx
$ open http://localhost:3000/
```