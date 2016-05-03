sa-netdata
==========

[![Build Status](https://travis-ci.org/softasap/sa-netdata.svg?branch=master)](https://travis-ci.org/softasap/sa-netdata)

Usage example:

<pre>


     - {
         role: "sa-netdata"
       }


</pre>



netdata is a extremely optimized Linux utility that provides real-time (per second) performance monitoring for Linux systems, applications, SNMP devices, etc. and shows full interactive charts that absolutely render all collected values over the web browser to analyze them.


It has been developed to be installed on each Linux system, without interrupting the current running application on it. You can use this tool to monitor and get overview of what is happening in real-time and what just happened, on your Linux systems and applications.

This is what it monitors:

Total and Per Core CPU usage, interrupts, softirqs and frequency.
Total Memory, RAM, Swap and Kernel usage.
Disk I/O (per disk: bandwidth, operations, backlog, utilization, etc).
Monitors Network interfaces including: bandwidth, packets, errors, drops, etc).
Monitors Netfilter / iptables Linux firewall connections, events, errors, etc.
Processes (running, blocked, forks, active, etc).
System Applications with the process tree (CPU, memory, swap, disk reads/writes, threads, etc).
Apache and Nginx Status monitoring with mod_status.
MySQL database monitoring: queries, updates, locks, issues, threads, etc.
Postfix email server message queue.
Squid proxy server bandwidth and requests monitoring.
Hardware sensors (temperature, voltage, fans, power, humidity, etc).
SNMP devices.
