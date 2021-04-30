# Golang Template with Docker/Docker Compose

## Environment

- [Golang](https://golang.org/) ... 1.16.3

## How to compile and run source code with Docker/Docker Compose

1. Please run `docker-compose up` then use `docker-compose exec` command after build is done.

```sh
% docker-compose up -d --build 
% docker-compose exec app bash
```

2. Move into `app` directory and you can run with below command.

```sh
/app＃ cd hello
/app/hello＃ go run .
```
