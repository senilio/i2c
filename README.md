### What:
This is more or less a copy of https://github.com/wouterdebie/i2cssh, which has many more features. It's dependant on Ruby and also tends to break on each OSX upgrade. So I made my own version which only relies on sys, subprocess and the built in osascript binary.

### Usage:
```
./i2c
Usage: ./i2c server(s)
```

Examples:
```
./i2c root@10.0.0.{1..5}
```

```
./i2c 10.0.0.1 10.0.0.2 10.0.0.3 10.0.0.4 .....
```

Currently accepts no flags :)
