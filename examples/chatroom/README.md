How to build:
=============

1) Compile first.jai
2) Copy the os (win/mac/linux) binary files (\*.dll/\*.so) into the same folder as first.exe
```
* os\GameNetworkingSockets.dll
* os\libcrypto-1_1-x64.dll
* os\libprotobuf-lite.dll
* os\libprotobuf.dll
* os\libprotoc.dll
* os\libssl-1_1-x64.dll
```

How to run:
===========

1) Run local host via .cmd files

```
run 1 time:  chatroom_localhost_server.cmd <- Starts up a chatooom server listening for clients on the default port.
run N times: chatroom_localhost_client.cmd <- Starts up a chatroom client connecting to a local host on the default port.
```

*OR*

2) Enter your own command line arguments for first.exe:
```
+------------------------------------------------------------+
|  //             <ip>        <port>                         |
|  -client server 192.168.0.1:12345                          |
|  -client server 192.168.0.1       // Defaults to port 6789 |
|                                                            |
|  // local host    <port>                                   |
|  -client loopback 12345                                    |
|  -client loopback                 // Defaults to port 6789 |
|                                                            |
|  //      <port>                                            |
|  -server 12345                                             |
|  -server                          // Defaults to port 6789 |
+------------------------------------------------------------+
```