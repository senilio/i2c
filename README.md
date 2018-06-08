### What:
This tool will launch a new iTerm2 window and create split panes for each session. By broadcasting commands (alt+cmd+i) you have a perfect clusterssh tool.

I used to use https://github.com/wouterdebie/i2cssh for clustering. It's dependant on Ruby and also tends to break on each OSX/Ruby upgrade. I got tired of this, so I made my own version which relies only on python (sys, subprocess) and the built in OSX osascript binary.

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

Once you have a window with multiple sessions, hit ALT+CMD+i to send to all sessions in window.
