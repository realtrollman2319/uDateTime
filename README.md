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
    +utcNow          [get]      : DateTimeOffset
    +now             [get]      : DateTimeOffset

DateTimeOffset [Class]:
    Constructor: DateTimeOffset(double seconds)
    Constructor: DateTimeOffset(DateTime dateTime)
    Constructor: DateTimeOffset(double ticks, TimeSpan offset)
    Constructor: DateTimeOffset(DateTime dateTime, TimeSpan offset)
    Constructor: DateTimeOffset(int32 year, int32 month, int32 day, int32 hour, int32 minute, int32 second, TimeSpan offset)
    Constructor: DateTimeOffset(int32 year, int month, int32 day, int32 hour, int32 minute, int32 second, in32 millisecond, TimeSpan offset)
    +add(TimeSpam timeSpan)                          [get]      : DateTimeOffset
    +addYears(int32 years)                           [get]      : DateTimeOffset
    +addMonths(int32 months)                         [get]      : DateTimeOffset
    +addDays(double days)                            [get]      : DateTimeOffset
    +addHours(double hours)                          [get]      : DateTimeOffset
    +addMinutes(double minutes)                      [get]      : DateTimeOffset
    +addSeconds(double seconds)                      [get]      : DateTimeOffset
    +addMilliseconds(double milliseconds)            [get]      : DateTimeOffset
    +addTicks(double ticks)                          [get]      : DateTimeOffset
    +toString(string format)                         [get]      : string
    +toString()                                      [get]      : string
    +toUnixTimeSeconds()                             [get]      : double
    +toUnixTimeMilliseconds()                        [get]      : double
    +year                                            [get]      : int32
    +month                                           [get]      : int32
    +day                                             [get]      : int32
    +dayOfYear                                       [get]      : int32
    +hour                                            [get]      : int32
    +minute                                          [get]      : int32
    +second                                          [get]      : int32
    +millisecond                                     [get]      : int32
    +ticks                                           [get]      : double
    +totalDays                                       [get]      : double
    +totalHours                                      [get]      : double
    +totalMinutes                                    [get]      : double
    +totalSeconds                                    [get]      : double
    +totalMilliseconds                               [get]      : double

TimeSpan [Class]:
    Constructor: DateTimeOffset(double ticks)
    Constructor: DateTimeOffset(int32 hours, int32 minutes, int32 seconds)
    Constructor: DateTimeOffset(int32 days, int32 hours, int32 minutes, int32 seconds)
    Constructor: DateTimeOffset(int32 days, int32 hours, int32 minutes, int32 seconds, int32 milliseconds)
    +subtract(TimeSpan timeSpan)                [get]      : TimeSpan
    +toString(string format)                    [get]      : string
    +toString()                                 [get]      : string
    +ticksPerMillisecond                        [get]      : double
    +ticksPerSecond                             [get]      : double
    +ticksPerMinute                             [get]      : double
    +ticksPerHour                               [get]      : double
    +ticksPerDay                                [get]      : double
    +totalDays                                  [get]      : double
    +totalHours                                 [get]      : double
    +totalMinutes                               [get]      : double
    +totalSeconds                               [get]      : double
    +totalMilliseconds                          [get]      : double
    +days                                       [get]      : int32
    +hours                                      [get]      : int32
    +minutes                                    [get]      : int32
    +seconds                                    [get]      : int32
    +milliseconds                               [get]      : int32
    +ticks                                      [get]      : double
    +zero                                       [get]      : TimeSpan
    +minValue                                   [get]      : TimeSpan
    +maxValue                                   [get]      : TimeSpan
```
