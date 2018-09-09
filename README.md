# Red-and-white-conky
A fullscreen conky(tested only on 1366x768 resolution) in red and white theme. It contains various monitoring stuff and has rhythmbox integeration.

For conky installation instructions and other related information please refer to: https://linuxconfig.org/system-monitoring-on-ubuntu-18-04-linux-with-conky.

Changes required for this configuration file to work properly on your system:
-------------------------------------------------------------
For displaying used capacity of another partation you need to change the mount location on line number 82

For displaying internet traffic properly you need to change your device from line number 91 to line number 93, my device is wlp1s0

Also if you are downloading the conkyrc file make sure you rename it to '.conkyrc'.
