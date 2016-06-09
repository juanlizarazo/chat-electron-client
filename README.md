# chat-electron-client

Desktop client for the server project [chat-nodejs-serice](https://github.com/juanlizarazo/chat-nodejs-serice)

## Stack

Electron wrapping copy of static assets (html/css/js) from web version.
It connects to web version server

## Run from source with electron

    # clone this repo
    cd source && npm i && npm start

## Run packaged app

1. Open installers directory
2. Open the directory that matches your platform's architecture
3. Execute appropiate file

    # Linux example
    cd installers/chat-electron-client-linux-x64 && \
    ./chat-electron-client
