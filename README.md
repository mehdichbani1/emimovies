# Simple 1ngularjs + Node.js + Docker Web app that you can test

Simple movie catalog web App developed using Angularjs

## Files

- simple/
  - server.js      Example Express web server.
  - Dockerfile        Script file for building our Docker image.
  - package.json      Node.js package file, specifies npm dependencies.

## Setup

You need Node.js and Docker installed.

First change to the directory and install dependencies:

```bash
cd backend
npm install
```

## Directly run

The example Node.js application is a web app, you run it directly like this:


## Build and run using Docker

To build the Docker image:

```bash
npm run docker:build
```

To run the Docker image:

```bash
npm run docker:run
```



To see what Docker containers you have running:

```bash
docker ps
```

To stop the container:

```bash
npm run docker:stop
```
To remove the container:

```bash
docker rm hellomehdi
```
