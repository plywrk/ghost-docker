# Ghost Docker Compose

Run Ghost Blogging platform on Docker with `docker-compose` using latest version of Ghost.

## How to use it

- Install [Docker Desktop](https://www.docker.com/products/docker-desktop)
- Clone this repo
- Run `docker-compose up`
- Open <http://localhost:2368/ghost> in the browser and setup your Ghost

## Generated files

`docker-compose up` will generate,

```ssh
config.development.json
./ghost/
    |- /content/
        |- /data/
        |- /themes/
```

## Start Development

You can start installing themes and edit theme files inside `./ghost/content/themes/` folder.

Edit configuration file in `config.development.json`

Everytime you change files, you need to run `docker-compose restart`