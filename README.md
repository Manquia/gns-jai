# gns-jai

Simplified Jai binding for ValvE's GameNetworkingSockets C/C++ networking library.

GameNetworkingSockets github repository: https://github.com/ValveSoftware/GameNetworkingSockets

Module Install Instructions:
============================

These bindings are done such that you can drop them into the modules folder. It is recommended you clone the repository into the modules folder with the folder name "GameNetworkingSockets". This name designation is not required, but the provided samples are expecting a module called "GameNetworkingSockets".

Provided binary/API details:
```
OS      | Build Setup    | Tested                 | Notes
--------+----------------+------------------------+---------
windows | vcpkg/msvc     | Win_10=working         |
linux   | ninja/gcc      | Mint_20.1=may not work | apt-get install libgl-dev
mac     | not included   | none tested            |

https://github.com/ValveSoftware/GameNetworkingSockets/releases/tag/v1.2.0
Release v1.2.0
commit 5fe10494e27be722d18c443dc70f851541e5d554
```

This project is in development and will change a fair amount as it matures. If you have any questions feel free to ask me on twitter https://twitter.com/MicahRust