# nginx-docker
nginx in docker

## Requirement
1. docker 19.03.8
2. dokcer-compose 1.25.5

## Start nginx
```shell
docker-compose up -d
```

## Directory Struture
```shell
docker
├── docker-compose.yml
├── letsencrypt
├── html
│   └── index.html
├── nginx
│   ├── conf.d
│   │   └── default.conf
│   ├── sited-enabled  # add server config in this directory
│   │   └── uwsgi.conf
│   └── nginx.conf
└── nginx.conf
```