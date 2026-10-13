# Multithreaded TCP Port Scanner 🔍

A lightweight, concurrent network reconnaissance tool built in Python to identify active services and open ports on a target IP address or domain.

**Features:**
* Utilizes Python's `socket` library to execute native TCP Connect scans.
* Implements `concurrent.futures.ThreadPoolExecutor` to dispatch up to 200 connection threads simultaneously, drastically reducing scan times across large port ranges.
* Includes dynamic service resolution (mapping standard IANA port numbers to their associated protocols like HTTP, SSH, FTP).
* Features a thread-safe Tkinter GUI with a real-time output console and a manual execution kill-switch.

*Built as a core Network Security component of a 30-Day Cybersecurity portfolio streak.*
