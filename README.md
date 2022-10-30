# NanoPi-LEDE-CPKG
## About this repository
This is an alternative to getting my self-compiled packages, because I don't have enough money to rent a server for downloading :(  
If you can provide a server or have any good ideas, please let me know.  
## How to use this repository
First, check your version number. For example:  
```
$ ssh root@192.168.2.1
     _________
    /        /\      _    ___ ___  ___
   /  LE    /  \    | |  | __|   \| __|
  /    DE  /    \   | |__| _|| |) | _|
 /________/  LE  \  |____|___|___/|___|
 \        \   DE /
  \    LE  \    /  -------------------------------------------
   \  DE    \  /    IFVWRT v1.0.0-0911 STABLE
    \________\/    -------------------------------------------

root@IFVWRT:~#
```
Here, you can see the version number is `v1.0.0-0911`. So you should add your feeds like this:  
`/etc/opkg/customfeeds.conf`
```
src/gz ifvwrt_core https://github.com/Ra2-IFV/NanoPi-LEDE-CPKG/raw/main/v1.0.0-0911/
```
### [WIP] Use my script to generate feeds
