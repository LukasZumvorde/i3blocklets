# i3blocklets
A collection of my blocklets for i3blocks.


## cpu_usage
A simple bash script to calculate and return the current CPU usage in percent. Requires only top, grep, and awk. It should work on most linux distros out of the box.
It assumes you to have 4 CPUs.

```
[cpu_usage]
command=~/.i3/i3blocks/cpu_usage
interval=10
label=CPU
```

## music
Designed to work with MOC (Music on Console) but can easyly be adapted to several palyers. 
Returns the currently played filename or "none" if nothing is playing. Adds mouse controlls to the blocklet. 

```
[music]
command=~/.i3/i3blocks/music
interval=10
label=♫
color=#cc33ff
```
