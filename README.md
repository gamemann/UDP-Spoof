# UDP Spoof Program
## Description
A small C program I made to send out spoofed/non-spoofed UDP packets via raw sockets. This program includes setting the data string and timeout as well.

## Usage
Please use the following:

```
./UDP_Spoof <Source IP> <Source Port> <Destination IP> <Destination Port> [<Time out> <Data>]
```

Example:

```
./UDP_Spoof 10.50.0.3 12345 10.50.0.4 12345 1 "HELLO!"
```

## Credits
* [Roy](https://gflclan.com/profile/1-roy/) (Christian Deacon) - Creator.