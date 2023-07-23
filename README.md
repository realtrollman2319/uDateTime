# uDateTime [![](https://img.shields.io/github/downloads/realtrollman2319/uDateTime/total.svg)](https://github.com/realtrollman2319/uDateTime/releases)
DateTime class for uScript2, it has some of the methods in DateTime and DateTimeOffset.

# Sample code:
```
utcNow = uTime.utcNow;
now = uTime.now;
print("UTC Current time: {0} | Unix time: {1}".format(utcNow.toString("MMMM dd yyyy (dddd) hh:mm:ss tt"), utcNow.toUnixTimeSeconds()));
print("Current local time: {0} | Unix time: {1}".format(now.toString("MMMM dd yyyy (dddd) hh:mm:ss tt"), now.toUnixTimeSeconds()));
```

# Documentation:
```
uTime [Class]:
    +utcNow          [get]      : DateTime
    +now             [get]      : DateTime
```
