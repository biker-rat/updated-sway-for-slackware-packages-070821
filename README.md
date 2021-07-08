# updated-sway-for-slackware-packages-070821
I just updated my swaym packages/builds for slackware64-current/15.0 today (July 8, 2021).
I added libseat as it is a new hard dependency for wlroots. My libseat package does not include seatd and does include elogind support.
I added a startsway wrapper bash script to the sway executable that prefixes dbus-launch.
I upgraded wlroots version from 0.13.0 to 0.14.1 and swaywm version from 1.6.0 to 1.6.1.
I plan to rebase the slackbuilds to slackbuild.org template in near future.
