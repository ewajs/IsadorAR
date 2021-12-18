# How to start a local development version and test from the phone

## Install NodeJS
If you don't have it already, [Install NodeJS](https://nodejs.org/en/) from it's homepage, choose an LTS version.

## Run a Dev Server 
In the terminal, navigate to the folder you wish to serve through the server (in this example, the folder that contains this file, you can change directories in the terminal by doing `cd FolderName`) and then run the command `npx http-server` a server should start running and print it's IP Address and Port. You'll see some output like this:
```
ezequielwajs@Ezequiels-MacBook-Pro ModelViewerDemo % cd MovelViewer
ezequielwajs@Ezequiels-MacBook-Pro ModelViewerDemo % npx http-server
npx: installed 34 in 5.038s
Starting up http-server, serving ./

http-server version: 14.0.0

http-server settings: 
CORS: disabled
Cache: 3600 seconds
Connection Timeout: 120 seconds
Directory Listings: visible
AutoIndex: visible
Serve GZIP Files: false
Serve Brotli Files: false
Default File Extension: none

Available on:
  http://127.0.0.1:8081
  http://192.168.0.12:8081
Hit CTRL-C to stop the server
```

## Accessing From the Phone
The 2 lines at the bottom show the IP Addresses and Ports to which the server is listening, **Do not use `127.0.0.1`** as that is only accesible from your own computer, the other IP can be accessed by the phone as long as it is connected to the same Wi-Fi as the computer.
