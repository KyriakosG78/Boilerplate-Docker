# Simple Boilerplate Web Development Environment with Docker

## Before you start

1. You must have Docker installed on your pc.
   https://www.docker.com/products/docker-desktop
1. Copy all files to your project folder.
1. Change settings on {.env} file with your preferences.
1. Run Docker compose command for docker-compose.yml
   1. From command line go to project folder and run
      >docker-compose -f "docker-compose.yml" up -d --build
   1. With help of Docker extension
      >https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker

## Components

### Web Server with PHP

- Apache with php 7.4 version

### DataBase

- mysql 8.0 version

### Database Manager

- phpmyadmin

## Extras

- You can fix some settings in php.ini file before you start server.
- .env file have default username and passwords. You must change  it.