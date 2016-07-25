# Sunshine
This utility will help killing the lockscreen when Apple Remote Desktop accidentally locked you out. 

# How to compile
First make sure xcode is installed. Then fireup a terminal and run the following commands:

```bash
git clone https://github.com/mattlavine/sunshine-ard.git
cd sunshine-ard
clang -framework Foundation main.c -o stop_lockscreen
```
Running `./stop_lockscreen` should now stop the lockscreen.

This repository was automatically exported from code.google.com/p/sunshine-ard
