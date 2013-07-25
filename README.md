portcheck
=========

This script based on Kim Naim Lesmer (kim@bitflop.com) portcheck. In the FreeBSD port tree, this port was deprecate due no more public distfiles (http://www.freshports.org/ports-mgmt/portcheck/). Basically, this script fetch to updated port tress, check need-for-upgrade ports, then check if a port has vulnerabilities.

This repository just offer two scripts

Original Script
-------------------------

* You can look at [`portcheck-orig.sh`](portcheck-orig.sh)
* This original script created by Kim Naim Lesmer

My Fork Script
-------------------------

* You can look at [`portcheck.sh`](portcheck.sh)
* Added posibilities to run portcheck via crontab. Yeah, I love this thing run everynight and report to me when a package has vulnerabilities</dd>
