# chat-electron-client

Desktop client for the server project [chat-nodejs-service](https://github.com/juanlizarazo/chat-nodejs-service)

![Preview](https://github.com/juanlizarazo/chat-electron-client/raw/master/screenshot.png)

## Stack

Electron wrapping copy of static assets (html/css/js) from web version.
It connects to web version server through sockets (socket.io), in other words, you need an internet connection.

## Run from source with electron

    # clone this repo
    cd source && npm i && npm start

## Run packaged app

1. Open installers directory
2. Open the directory that matches your platform's architecture
3. Execute appropiate file


    # Linux example

    cd installers && \
    tar -zxvf  chat-electron-client-linux-x64.tar.gz chat-electron-client-linux-x64/ && \
    ./chat-electron-client
